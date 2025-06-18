# Session 30 - Capstone project - LLM Pre-Training

## SmolLM2 Training Pipeline

🚀 **Train SmolLM2-1.7B on Cosmopedia-100k dataset from scratch**

## Overview
Complete training pipeline for SmolLM2-1.7B using the Cosmopedia-100k dataset. Trained from random weights with comprehensive logging and checkpointing.

## Project Structure
```
├── README.md                   # Project documentation
├── smollm2-refind.ipynb        # Main training notebook
├── smollm2.ipynb               # Draft notebook version
├── ec2_logs.md                 # EC2 training logs 
├── training_loss.md            # Loss trend analysis
```

## Notebook Structure
```
Cell 1: Install requirements (transformers, datasets, accelerate, matplotlib, etc.)
Cell 2: Environment setup and imports  
Cell 3: GPU setup and random seeds
Cell 4: Load Cosmopedia-100k dataset
Cell 5: Load SmolLM2 tokenizer
Cell 6: Dataset preprocessing  
Cell 7: Model initialization and training components (optimizer, scheduler, random weights)
Cell 8: Next-word prediction testing
Cell 9: GPU memory analysis
Cell 10: Production training loop with EBS storage
```

## Configuration
- **Model**: SmolLM2-1.7B (random weights)
- **Dataset**: Cosmopedia-100k (~100k samples)
- **Batch Size**: 1 (effective: 16 with gradient accumulation)
- **Sequence Length**: 2048 tokens
- **Target**: 300,000 steps (3 epochs)
- **Current Progress**: 27,000 steps completed
- **Learning Rate**: 3e-5 (cosine schedule, 2% warmup)

## Training Progress
- **Loss Trend**: From ~11.0 to ~3.3 (see [training_loss.md](training_loss.md))
- **Detailed Logs**: Average loss every 50 steps (see [ec2_logs.md](ec2_logs.md))
- **Checkpoints**: Saved every 200 steps to EBS storage
- **Status**: Training successfully running on EC2

## Features
✅ **Auto-Resume** - Continues from latest checkpoint  
✅ **Spot Instance Ready** - Graceful interruption handling  
✅ **Comprehensive Logging** - Training progress and metrics

---
*Optimized for AWS EC2 with EBS persistence* 