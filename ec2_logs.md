# SmolLM2 Training Log

**Training Started:** 2025-06-16 19:13:54

## Configuration
- Model: SmolLM2-1.7B
- Dataset: Cosmopedia-100k
- Batch Size: 1
- Gradient Accumulation: 64
- Effective Batch Size: 64
- Max Sequence Length: 2048
- Total Steps: 300,000
- Log Interval: 50 steps
- Checkpoint Interval: 200 steps
- Checkpoint Storage: /mnt/ebs/checkpoints

## Training Progress

**2025-06-16 19:13:54** - Training started on EC2 with EBS storage

**2025-06-16 19:13:54** - Checkpoint directory: /mnt/ebs/checkpoints

**2025-06-16 19:13:54** - Log file: /mnt/ebs/training_log.md

**2025-06-16 19:13:54** - Starting training from scratch - no existing checkpoints found

| Step | Epoch | Loss | Learning Rate | GPU Memory |
|------|-------|------|---------------|------------|
**2025-06-16 19:13:54** - EPOCH 1 STARTED

| Step 50/300,000 | Epoch 1 | Loss: 10.9137 | LR: 0.00e+00 | GPU: 7.1GB |
| Step 100/300,000 | Epoch 1 | Loss: 10.9948 | LR: 5.00e-09 | GPU: 13.9GB |
| Step 150/300,000 | Epoch 1 | Loss: 10.9458 | LR: 1.00e-08 | GPU: 13.9GB |
| Step 200/300,000 | Epoch 1 | Loss: 11.0534 | LR: 1.50e-08 | GPU: 13.9GB |
**2025-06-16 19:16:54** - CHECKPOINT: Saved at step 200, loss 10.8703

| Step 250/300,000 | Epoch 1 | Loss: 10.8267 | LR: 1.50e-08 | GPU: 13.9GB |
| Step 300/300,000 | Epoch 1 | Loss: 10.9181 | LR: 2.00e-08 | GPU: 13.9GB |
| Step 350/300,000 | Epoch 1 | Loss: 10.9606 | LR: 2.50e-08 | GPU: 13.9GB |
| Step 400/300,000 | Epoch 1 | Loss: 10.8974 | LR: 3.00e-08 | GPU: 13.9GB |
**2025-06-16 19:19:50** - CHECKPOINT: Saved at step 400, loss 11.1619

| Step 450/300,000 | Epoch 1 | Loss: 10.9288 | LR: 3.50e-08 | GPU: 13.9GB |
| Step 500/300,000 | Epoch 1 | Loss: 11.0475 | LR: 3.50e-08 | GPU: 13.9GB |
| Step 550/300,000 | Epoch 1 | Loss: 10.7715 | LR: 4.00e-08 | GPU: 13.9GB |
| Step 600/300,000 | Epoch 1 | Loss: 10.8651 | LR: 4.50e-08 | GPU: 13.9GB |
**2025-06-16 19:22:46** - CHECKPOINT: Saved at step 600, loss 11.0699

| Step 650/300,000 | Epoch 1 | Loss: 10.9421 | LR: 5.00e-08 | GPU: 13.9GB |
| Step 700/300,000 | Epoch 1 | Loss: 10.9308 | LR: 5.00e-08 | GPU: 13.9GB |
| Step 750/300,000 | Epoch 1 | Loss: 10.9620 | LR: 5.50e-08 | GPU: 13.9GB |
| Step 800/300,000 | Epoch 1 | Loss: 11.0318 | LR: 6.00e-08 | GPU: 13.9GB |
**2025-06-16 19:25:42** - CHECKPOINT: Saved at step 800, loss 10.6405

| Step 850/300,000 | Epoch 1 | Loss: 11.1323 | LR: 6.50e-08 | GPU: 13.9GB |
| Step 900/300,000 | Epoch 1 | Loss: 10.9818 | LR: 7.00e-08 | GPU: 13.9GB |
| Step 950/300,000 | Epoch 1 | Loss: 10.9602 | LR: 7.00e-08 | GPU: 13.9GB |
| Step 1,000/300,000 | Epoch 1 | Loss: 10.9506 | LR: 7.50e-08 | GPU: 13.9GB |
**2025-06-16 19:28:38** - CHECKPOINT: Saved at step 1,000, loss 10.1234

| Step 1,050/300,000 | Epoch 1 | Loss: 10.9438 | LR: 8.00e-08 | GPU: 13.9GB |
| Step 1,100/300,000 | Epoch 1 | Loss: 10.9227 | LR: 8.50e-08 | GPU: 13.9GB |
| Step 1,150/300,000 | Epoch 1 | Loss: 11.0424 | LR: 8.50e-08 | GPU: 13.9GB |
| Step 1,200/300,000 | Epoch 1 | Loss: 10.9531 | LR: 9.00e-08 | GPU: 13.9GB |
**2025-06-16 19:31:49** - CHECKPOINT: Saved at step 1,200, loss 11.5027

**2025-06-16 19:31:50** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_200.pt

| Step 1,250/300,000 | Epoch 1 | Loss: 10.8680 | LR: 9.50e-08 | GPU: 13.9GB |
| Step 1,300/300,000 | Epoch 1 | Loss: 10.9213 | LR: 1.00e-07 | GPU: 13.9GB |
| Step 1,350/300,000 | Epoch 1 | Loss: 10.8891 | LR: 1.05e-07 | GPU: 13.9GB |
| Step 1,400/300,000 | Epoch 1 | Loss: 11.0903 | LR: 1.05e-07 | GPU: 13.9GB |
**2025-06-16 19:34:55** - CHECKPOINT: Saved at step 1,400, loss 11.3214

**2025-06-16 19:34:56** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_400.pt

| Step 1,450/300,000 | Epoch 1 | Loss: 10.7954 | LR: 1.10e-07 | GPU: 13.9GB |
| Step 1,500/300,000 | Epoch 1 | Loss: 11.0184 | LR: 1.15e-07 | GPU: 13.9GB |
| Step 1,550/300,000 | Epoch 1 | Loss: 10.9385 | LR: 1.20e-07 | GPU: 13.9GB |
| Step 1,600/300,000 | Epoch 1 | Loss: 10.9129 | LR: 1.25e-07 | GPU: 10.5GB |
**2025-06-16 19:37:58** - CHECKPOINT: Saved at step 1,600, loss 10.5911

**2025-06-16 19:37:59** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_600.pt

| Step 1,650/300,000 | Epoch 1 | Loss: 10.9546 | LR: 1.25e-07 | GPU: 13.9GB |
| Step 1,700/300,000 | Epoch 1 | Loss: 10.8671 | LR: 1.30e-07 | GPU: 13.9GB |
| Step 1,750/300,000 | Epoch 1 | Loss: 11.0359 | LR: 1.35e-07 | GPU: 13.9GB |
| Step 1,800/300,000 | Epoch 1 | Loss: 10.8385 | LR: 1.40e-07 | GPU: 13.9GB |
**2025-06-16 19:40:57** - CHECKPOINT: Saved at step 1,800, loss 10.9120

**2025-06-16 19:40:58** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_800.pt

| Step 1,850/300,000 | Epoch 1 | Loss: 11.0552 | LR: 1.40e-07 | GPU: 13.9GB |
| Step 1,900/300,000 | Epoch 1 | Loss: 10.9150 | LR: 1.45e-07 | GPU: 13.9GB |
| Step 1,950/300,000 | Epoch 1 | Loss: 10.8584 | LR: 1.50e-07 | GPU: 13.9GB |
| Step 2,000/300,000 | Epoch 1 | Loss: 10.9407 | LR: 1.55e-07 | GPU: 13.9GB |
**2025-06-16 19:43:59** - CHECKPOINT: Saved at step 2,000, loss 10.3129

**2025-06-16 19:44:00** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_1000.pt

| Step 2,050/300,000 | Epoch 1 | Loss: 10.9712 | LR: 1.60e-07 | GPU: 13.9GB |
| Step 2,100/300,000 | Epoch 1 | Loss: 10.9082 | LR: 1.60e-07 | GPU: 13.9GB |
| Step 2,150/300,000 | Epoch 1 | Loss: 10.9119 | LR: 1.65e-07 | GPU: 13.9GB |
| Step 2,200/300,000 | Epoch 1 | Loss: 10.9740 | LR: 1.70e-07 | GPU: 13.9GB |
**2025-06-16 19:47:01** - CHECKPOINT: Saved at step 2,200, loss 11.0496

**2025-06-16 19:47:02** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_1200.pt

| Step 2,250/300,000 | Epoch 1 | Loss: 10.8796 | LR: 1.75e-07 | GPU: 13.9GB |
| Step 2,300/300,000 | Epoch 1 | Loss: 10.9768 | LR: 1.75e-07 | GPU: 13.9GB |
| Step 2,350/300,000 | Epoch 1 | Loss: 10.9210 | LR: 1.80e-07 | GPU: 13.9GB |
| Step 2,400/300,000 | Epoch 1 | Loss: 10.9682 | LR: 1.85e-07 | GPU: 13.9GB |
**2025-06-16 19:50:00** - CHECKPOINT: Saved at step 2,400, loss 10.6029

**2025-06-16 19:50:01** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_1400.pt

| Step 2,450/300,000 | Epoch 1 | Loss: 11.0107 | LR: 1.90e-07 | GPU: 13.9GB |
| Step 2,500/300,000 | Epoch 1 | Loss: 10.8711 | LR: 1.95e-07 | GPU: 13.9GB |
| Step 2,550/300,000 | Epoch 1 | Loss: 10.9658 | LR: 1.95e-07 | GPU: 13.9GB |
| Step 2,600/300,000 | Epoch 1 | Loss: 11.0060 | LR: 2.00e-07 | GPU: 13.9GB |
**2025-06-16 19:52:58** - CHECKPOINT: Saved at step 2,600, loss 10.3692

**2025-06-16 19:52:59** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_1600.pt

| Step 2,650/300,000 | Epoch 1 | Loss: 11.0489 | LR: 2.05e-07 | GPU: 13.9GB |
| Step 2,700/300,000 | Epoch 1 | Loss: 10.9593 | LR: 2.10e-07 | GPU: 13.9GB |
| Step 2,750/300,000 | Epoch 1 | Loss: 10.9497 | LR: 2.10e-07 | GPU: 13.9GB |
| Step 2,800/300,000 | Epoch 1 | Loss: 10.8795 | LR: 2.15e-07 | GPU: 13.9GB |
**2025-06-16 19:55:56** - CHECKPOINT: Saved at step 2,800, loss 10.2563

**2025-06-16 19:55:56** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_1800.pt

| Step 2,850/300,000 | Epoch 1 | Loss: 10.9131 | LR: 2.20e-07 | GPU: 13.9GB |
| Step 2,900/300,000 | Epoch 1 | Loss: 10.9207 | LR: 2.25e-07 | GPU: 13.9GB |
| Step 2,950/300,000 | Epoch 1 | Loss: 10.8974 | LR: 2.30e-07 | GPU: 13.9GB |
| Step 3,000/300,000 | Epoch 1 | Loss: 10.7855 | LR: 2.30e-07 | GPU: 13.9GB |
**2025-06-16 19:58:53** - CHECKPOINT: Saved at step 3,000, loss 10.9444

| Step 3,050/300,000 | Epoch 1 | Loss: 10.9216 | LR: 2.35e-07 | GPU: 13.9GB |
| Step 3,100/300,000 | Epoch 1 | Loss: 10.8584 | LR: 2.40e-07 | GPU: 13.9GB |
| Step 3,150/300,000 | Epoch 1 | Loss: 11.0285 | LR: 2.45e-07 | GPU: 13.9GB |
| Step 3,200/300,000 | Epoch 1 | Loss: 11.0037 | LR: 2.50e-07 | GPU: 10.5GB |
**2025-06-16 20:01:53** - CHECKPOINT: Saved at step 3,200, loss 10.4889

**2025-06-16 20:01:54** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_2200.pt

| Step 3,250/300,000 | Epoch 1 | Loss: 10.8641 | LR: 2.50e-07 | GPU: 13.9GB |
| Step 3,300/300,000 | Epoch 1 | Loss: 10.9435 | LR: 2.55e-07 | GPU: 13.9GB |
| Step 3,350/300,000 | Epoch 1 | Loss: 11.0860 | LR: 2.60e-07 | GPU: 13.9GB |
| Step 3,400/300,000 | Epoch 1 | Loss: 10.8692 | LR: 2.65e-07 | GPU: 13.9GB |
**2025-06-16 20:04:50** - CHECKPOINT: Saved at step 3,400, loss 10.0976

**2025-06-16 20:04:51** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_2400.pt

| Step 3,450/300,000 | Epoch 1 | Loss: 10.9183 | LR: 2.65e-07 | GPU: 13.9GB |
| Step 3,500/300,000 | Epoch 1 | Loss: 10.8940 | LR: 2.70e-07 | GPU: 13.9GB |
| Step 3,550/300,000 | Epoch 1 | Loss: 10.9036 | LR: 2.75e-07 | GPU: 13.9GB |
| Step 3,600/300,000 | Epoch 1 | Loss: 10.8210 | LR: 2.80e-07 | GPU: 13.9GB |
**2025-06-16 20:07:48** - CHECKPOINT: Saved at step 3,600, loss 11.4658

**2025-06-16 20:07:49** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_2600.pt

| Step 3,650/300,000 | Epoch 1 | Loss: 10.9730 | LR: 2.85e-07 | GPU: 13.9GB |
| Step 3,700/300,000 | Epoch 1 | Loss: 10.8855 | LR: 2.85e-07 | GPU: 13.9GB |
| Step 3,750/300,000 | Epoch 1 | Loss: 11.0546 | LR: 2.90e-07 | GPU: 13.9GB |
| Step 3,800/300,000 | Epoch 1 | Loss: 10.8360 | LR: 2.95e-07 | GPU: 13.9GB |
**2025-06-16 20:10:44** - CHECKPOINT: Saved at step 3,800, loss 11.0104

**2025-06-16 20:10:45** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_2800.pt

| Step 3,850/300,000 | Epoch 1 | Loss: 10.9524 | LR: 3.00e-07 | GPU: 13.9GB |
| Step 3,900/300,000 | Epoch 1 | Loss: 10.8097 | LR: 3.00e-07 | GPU: 13.9GB |
| Step 3,950/300,000 | Epoch 1 | Loss: 11.1155 | LR: 3.05e-07 | GPU: 13.9GB |
| Step 4,000/300,000 | Epoch 1 | Loss: 10.9995 | LR: 3.10e-07 | GPU: 13.9GB |
**2025-06-16 20:13:41** - CHECKPOINT: Saved at step 4,000, loss 10.3357

**2025-06-16 20:13:42** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_3000.pt

| Step 4,050/300,000 | Epoch 1 | Loss: 10.9547 | LR: 3.15e-07 | GPU: 13.9GB |
| Step 4,100/300,000 | Epoch 1 | Loss: 10.7927 | LR: 3.20e-07 | GPU: 13.9GB |
| Step 4,150/300,000 | Epoch 1 | Loss: 10.9454 | LR: 3.20e-07 | GPU: 13.9GB |
| Step 4,200/300,000 | Epoch 1 | Loss: 10.8500 | LR: 3.25e-07 | GPU: 13.9GB |
**2025-06-16 20:16:38** - CHECKPOINT: Saved at step 4,200, loss 10.2183

**2025-06-16 20:16:39** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_3200.pt

| Step 4,250/300,000 | Epoch 1 | Loss: 10.9351 | LR: 3.30e-07 | GPU: 13.9GB |
| Step 4,300/300,000 | Epoch 1 | Loss: 10.8391 | LR: 3.35e-07 | GPU: 13.9GB |
| Step 4,350/300,000 | Epoch 1 | Loss: 10.8960 | LR: 3.35e-07 | GPU: 13.9GB |
| Step 4,400/300,000 | Epoch 1 | Loss: 10.8295 | LR: 3.40e-07 | GPU: 13.9GB |
**2025-06-16 20:19:35** - CHECKPOINT: Saved at step 4,400, loss 10.6961

**2025-06-16 20:19:36** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_3400.pt

| Step 4,450/300,000 | Epoch 1 | Loss: 10.8970 | LR: 3.45e-07 | GPU: 13.9GB |
| Step 4,500/300,000 | Epoch 1 | Loss: 10.8450 | LR: 3.50e-07 | GPU: 13.9GB |
| Step 4,550/300,000 | Epoch 1 | Loss: 10.9755 | LR: 3.55e-07 | GPU: 13.9GB |
| Step 4,600/300,000 | Epoch 1 | Loss: 10.8826 | LR: 3.55e-07 | GPU: 13.9GB |
**2025-06-16 20:22:32** - CHECKPOINT: Saved at step 4,600, loss 10.7139

**2025-06-16 20:22:32** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_3600.pt

| Step 4,650/300,000 | Epoch 1 | Loss: 11.0698 | LR: 3.60e-07 | GPU: 13.9GB |
| Step 4,700/300,000 | Epoch 1 | Loss: 10.9570 | LR: 3.65e-07 | GPU: 13.9GB |
| Step 4,750/300,000 | Epoch 1 | Loss: 10.9181 | LR: 3.70e-07 | GPU: 13.9GB |
| Step 4,800/300,000 | Epoch 1 | Loss: 10.8820 | LR: 3.75e-07 | GPU: 10.5GB |
**2025-06-16 20:25:29** - CHECKPOINT: Saved at step 4,800, loss 11.1758

**2025-06-16 20:25:30** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_3800.pt

| Step 4,850/300,000 | Epoch 1 | Loss: 10.8227 | LR: 3.75e-07 | GPU: 13.9GB |
| Step 4,900/300,000 | Epoch 1 | Loss: 10.9899 | LR: 3.80e-07 | GPU: 13.9GB |
| Step 4,950/300,000 | Epoch 1 | Loss: 10.7843 | LR: 3.85e-07 | GPU: 13.9GB |
| Step 5,000/300,000 | Epoch 1 | Loss: 10.9608 | LR: 3.90e-07 | GPU: 13.9GB |
**2025-06-16 20:28:25** - CHECKPOINT: Saved at step 5,000, loss 11.5304

| Step 5,050/300,000 | Epoch 1 | Loss: 10.9002 | LR: 3.90e-07 | GPU: 13.9GB |
| Step 5,100/300,000 | Epoch 1 | Loss: 10.8492 | LR: 3.95e-07 | GPU: 13.9GB |
| Step 5,150/300,000 | Epoch 1 | Loss: 11.0294 | LR: 4.00e-07 | GPU: 13.9GB |
| Step 5,200/300,000 | Epoch 1 | Loss: 10.9135 | LR: 4.05e-07 | GPU: 13.9GB |
**2025-06-16 20:31:21** - CHECKPOINT: Saved at step 5,200, loss 10.9310

**2025-06-16 20:31:22** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_4200.pt

| Step 5,250/300,000 | Epoch 1 | Loss: 10.7361 | LR: 4.10e-07 | GPU: 13.9GB |
| Step 5,300/300,000 | Epoch 1 | Loss: 10.9228 | LR: 4.10e-07 | GPU: 13.9GB |
| Step 5,350/300,000 | Epoch 1 | Loss: 10.9347 | LR: 4.15e-07 | GPU: 13.9GB |
| Step 5,400/300,000 | Epoch 1 | Loss: 10.9707 | LR: 4.20e-07 | GPU: 13.9GB |
**2025-06-16 20:34:18** - CHECKPOINT: Saved at step 5,400, loss 10.9880

**2025-06-16 20:34:19** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_4400.pt

| Step 5,450/300,000 | Epoch 1 | Loss: 10.8853 | LR: 4.25e-07 | GPU: 13.9GB |
| Step 5,500/300,000 | Epoch 1 | Loss: 10.9840 | LR: 4.25e-07 | GPU: 13.9GB |
| Step 5,550/300,000 | Epoch 1 | Loss: 10.8542 | LR: 4.30e-07 | GPU: 13.9GB |
| Step 5,600/300,000 | Epoch 1 | Loss: 10.8598 | LR: 4.35e-07 | GPU: 13.9GB |
**2025-06-16 20:37:15** - CHECKPOINT: Saved at step 5,600, loss 11.5484

**2025-06-16 20:37:16** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_4600.pt

| Step 5,650/300,000 | Epoch 1 | Loss: 10.7932 | LR: 4.40e-07 | GPU: 13.9GB |
| Step 5,700/300,000 | Epoch 1 | Loss: 10.8398 | LR: 4.45e-07 | GPU: 13.9GB |
| Step 5,750/300,000 | Epoch 1 | Loss: 10.9337 | LR: 4.45e-07 | GPU: 13.9GB |
| Step 5,800/300,000 | Epoch 1 | Loss: 10.8596 | LR: 4.50e-07 | GPU: 13.9GB |
**2025-06-16 20:40:12** - CHECKPOINT: Saved at step 5,800, loss 10.6256

**2025-06-16 20:40:13** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_4800.pt

| Step 5,850/300,000 | Epoch 1 | Loss: 10.8100 | LR: 4.55e-07 | GPU: 13.9GB |
| Step 5,900/300,000 | Epoch 1 | Loss: 10.8752 | LR: 4.60e-07 | GPU: 13.9GB |
| Step 5,950/300,000 | Epoch 1 | Loss: 10.8001 | LR: 4.60e-07 | GPU: 13.9GB |
| Step 6,000/300,000 | Epoch 1 | Loss: 10.8678 | LR: 4.65e-07 | GPU: 13.9GB |
**2025-06-16 20:43:09** - CHECKPOINT: Saved at step 6,000, loss 10.7849

**2025-06-16 20:43:10** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_5000.pt

| Step 6,050/300,000 | Epoch 1 | Loss: 10.7820 | LR: 4.70e-07 | GPU: 13.9GB |
| Step 6,100/300,000 | Epoch 1 | Loss: 10.8246 | LR: 4.75e-07 | GPU: 13.9GB |
| Step 6,150/300,000 | Epoch 1 | Loss: 10.8061 | LR: 4.80e-07 | GPU: 13.9GB |
| Step 6,200/300,000 | Epoch 1 | Loss: 10.8334 | LR: 4.80e-07 | GPU: 13.9GB |
**2025-06-16 20:46:06** - CHECKPOINT: Saved at step 6,200, loss 10.4307

**2025-06-16 20:46:06** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_5200.pt

| Step 6,250/300,000 | Epoch 1 | Loss: 10.7588 | LR: 4.85e-07 | GPU: 13.9GB |
| Step 6,300/300,000 | Epoch 1 | Loss: 10.7103 | LR: 4.90e-07 | GPU: 13.9GB |
| Step 6,350/300,000 | Epoch 1 | Loss: 10.9226 | LR: 4.95e-07 | GPU: 13.9GB |
| Step 6,400/300,000 | Epoch 1 | Loss: 10.8337 | LR: 5.00e-07 | GPU: 10.5GB |
**2025-06-16 20:49:02** - CHECKPOINT: Saved at step 6,400, loss 11.2857

**2025-06-16 20:49:03** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_5400.pt

| Step 6,450/300,000 | Epoch 1 | Loss: 10.9166 | LR: 5.00e-07 | GPU: 13.9GB |
| Step 6,500/300,000 | Epoch 1 | Loss: 10.7979 | LR: 5.05e-07 | GPU: 13.9GB |
| Step 6,550/300,000 | Epoch 1 | Loss: 10.8072 | LR: 5.10e-07 | GPU: 13.9GB |
| Step 6,600/300,000 | Epoch 1 | Loss: 10.7949 | LR: 5.15e-07 | GPU: 13.9GB |
**2025-06-16 20:51:59** - CHECKPOINT: Saved at step 6,600, loss 10.8867

**2025-06-16 20:52:00** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_5600.pt

| Step 6,650/300,000 | Epoch 1 | Loss: 10.8927 | LR: 5.15e-07 | GPU: 13.9GB |
| Step 6,700/300,000 | Epoch 1 | Loss: 10.8261 | LR: 5.20e-07 | GPU: 13.9GB |
| Step 6,750/300,000 | Epoch 1 | Loss: 10.8582 | LR: 5.25e-07 | GPU: 13.9GB |
| Step 6,800/300,000 | Epoch 1 | Loss: 10.7610 | LR: 5.30e-07 | GPU: 13.9GB |
**2025-06-16 20:54:56** - CHECKPOINT: Saved at step 6,800, loss 10.7766

**2025-06-16 20:54:56** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_5800.pt

| Step 6,850/300,000 | Epoch 1 | Loss: 10.7487 | LR: 5.35e-07 | GPU: 13.9GB |
| Step 6,900/300,000 | Epoch 1 | Loss: 10.7391 | LR: 5.35e-07 | GPU: 13.9GB |
| Step 6,950/300,000 | Epoch 1 | Loss: 10.8989 | LR: 5.40e-07 | GPU: 13.9GB |
| Step 7,000/300,000 | Epoch 1 | Loss: 10.8548 | LR: 5.45e-07 | GPU: 13.9GB |
**2025-06-16 20:57:52** - CHECKPOINT: Saved at step 7,000, loss 11.1321

| Step 7,050/300,000 | Epoch 1 | Loss: 10.9121 | LR: 5.50e-07 | GPU: 13.9GB |
| Step 7,100/300,000 | Epoch 1 | Loss: 10.8739 | LR: 5.50e-07 | GPU: 13.9GB |
| Step 7,150/300,000 | Epoch 1 | Loss: 10.7220 | LR: 5.55e-07 | GPU: 13.9GB |
| Step 7,200/300,000 | Epoch 1 | Loss: 10.7728 | LR: 5.60e-07 | GPU: 13.9GB |
**2025-06-16 21:00:48** - CHECKPOINT: Saved at step 7,200, loss 11.6941

**2025-06-16 21:00:49** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_6200.pt

| Step 7,250/300,000 | Epoch 1 | Loss: 10.8706 | LR: 5.65e-07 | GPU: 13.9GB |
| Step 7,300/300,000 | Epoch 1 | Loss: 10.7723 | LR: 5.70e-07 | GPU: 13.9GB |
| Step 7,350/300,000 | Epoch 1 | Loss: 10.8393 | LR: 5.70e-07 | GPU: 13.9GB |
| Step 7,400/300,000 | Epoch 1 | Loss: 10.7808 | LR: 5.75e-07 | GPU: 13.9GB |
**2025-06-16 21:03:45** - CHECKPOINT: Saved at step 7,400, loss 10.7304

**2025-06-16 21:03:46** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_6400.pt

| Step 7,450/300,000 | Epoch 1 | Loss: 10.9232 | LR: 5.80e-07 | GPU: 13.9GB |
| Step 7,500/300,000 | Epoch 1 | Loss: 10.8256 | LR: 5.85e-07 | GPU: 13.9GB |
| Step 7,550/300,000 | Epoch 1 | Loss: 10.7758 | LR: 5.85e-07 | GPU: 13.9GB |
| Step 7,600/300,000 | Epoch 1 | Loss: 10.8623 | LR: 5.90e-07 | GPU: 13.9GB |
**2025-06-16 21:06:42** - CHECKPOINT: Saved at step 7,600, loss 11.2337

**2025-06-16 21:06:43** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_6600.pt

| Step 7,650/300,000 | Epoch 1 | Loss: 10.7948 | LR: 5.95e-07 | GPU: 13.9GB |
| Step 7,700/300,000 | Epoch 1 | Loss: 10.7401 | LR: 6.00e-07 | GPU: 13.9GB |
| Step 7,750/300,000 | Epoch 1 | Loss: 10.7576 | LR: 6.05e-07 | GPU: 13.9GB |
| Step 7,800/300,000 | Epoch 1 | Loss: 10.9450 | LR: 6.05e-07 | GPU: 13.9GB |
**2025-06-16 21:09:39** - CHECKPOINT: Saved at step 7,800, loss 11.1492

**2025-06-16 21:09:40** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_6800.pt

| Step 7,850/300,000 | Epoch 1 | Loss: 10.7627 | LR: 6.10e-07 | GPU: 13.9GB |
| Step 7,900/300,000 | Epoch 1 | Loss: 10.7586 | LR: 6.15e-07 | GPU: 13.9GB |
| Step 7,950/300,000 | Epoch 1 | Loss: 10.8937 | LR: 6.20e-07 | GPU: 13.9GB |
| Step 8,000/300,000 | Epoch 1 | Loss: 10.7478 | LR: 6.25e-07 | GPU: 10.5GB |
**2025-06-16 21:12:35** - CHECKPOINT: Saved at step 8,000, loss 11.3827

**2025-06-16 21:12:36** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_7000.pt

| Step 8,050/300,000 | Epoch 1 | Loss: 10.7717 | LR: 6.25e-07 | GPU: 13.9GB |
| Step 8,100/300,000 | Epoch 1 | Loss: 10.7394 | LR: 6.30e-07 | GPU: 13.9GB |
| Step 8,150/300,000 | Epoch 1 | Loss: 10.7733 | LR: 6.35e-07 | GPU: 13.9GB |
| Step 8,200/300,000 | Epoch 1 | Loss: 10.7532 | LR: 6.40e-07 | GPU: 13.9GB |
**2025-06-16 21:15:32** - CHECKPOINT: Saved at step 8,200, loss 10.0561

**2025-06-16 21:15:33** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_7200.pt

| Step 8,250/300,000 | Epoch 1 | Loss: 10.7281 | LR: 6.40e-07 | GPU: 13.9GB |
| Step 8,300/300,000 | Epoch 1 | Loss: 10.8028 | LR: 6.45e-07 | GPU: 13.9GB |
| Step 8,350/300,000 | Epoch 1 | Loss: 10.8431 | LR: 6.50e-07 | GPU: 13.9GB |
| Step 8,400/300,000 | Epoch 1 | Loss: 10.8149 | LR: 6.55e-07 | GPU: 13.9GB |
**2025-06-16 21:18:29** - CHECKPOINT: Saved at step 8,400, loss 10.4989

**2025-06-16 21:18:30** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_7400.pt

| Step 8,450/300,000 | Epoch 1 | Loss: 10.8436 | LR: 6.60e-07 | GPU: 13.9GB |
| Step 8,500/300,000 | Epoch 1 | Loss: 10.6028 | LR: 6.60e-07 | GPU: 13.9GB |
| Step 8,550/300,000 | Epoch 1 | Loss: 10.7117 | LR: 6.65e-07 | GPU: 13.9GB |
| Step 8,600/300,000 | Epoch 1 | Loss: 10.6783 | LR: 6.70e-07 | GPU: 13.9GB |
**2025-06-16 21:21:26** - CHECKPOINT: Saved at step 8,600, loss 11.8582

**2025-06-16 21:21:27** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_7600.pt

| Step 8,650/300,000 | Epoch 1 | Loss: 10.7294 | LR: 6.75e-07 | GPU: 13.9GB |
| Step 8,700/300,000 | Epoch 1 | Loss: 10.5772 | LR: 6.75e-07 | GPU: 13.9GB |
| Step 8,750/300,000 | Epoch 1 | Loss: 10.7244 | LR: 6.80e-07 | GPU: 13.9GB |
| Step 8,800/300,000 | Epoch 1 | Loss: 10.7083 | LR: 6.85e-07 | GPU: 13.9GB |
**2025-06-16 21:24:22** - CHECKPOINT: Saved at step 8,800, loss 10.5091

**2025-06-16 21:24:23** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_7800.pt

| Step 8,850/300,000 | Epoch 1 | Loss: 10.8196 | LR: 6.90e-07 | GPU: 13.9GB |
| Step 8,900/300,000 | Epoch 1 | Loss: 10.6419 | LR: 6.95e-07 | GPU: 13.9GB |
| Step 8,950/300,000 | Epoch 1 | Loss: 10.8011 | LR: 6.95e-07 | GPU: 13.9GB |
| Step 9,000/300,000 | Epoch 1 | Loss: 10.5797 | LR: 7.00e-07 | GPU: 13.9GB |
**2025-06-16 21:27:19** - CHECKPOINT: Saved at step 9,000, loss 9.1731

| Step 9,050/300,000 | Epoch 1 | Loss: 10.7160 | LR: 7.05e-07 | GPU: 13.9GB |
| Step 9,100/300,000 | Epoch 1 | Loss: 10.8112 | LR: 7.10e-07 | GPU: 13.9GB |
| Step 9,150/300,000 | Epoch 1 | Loss: 10.7565 | LR: 7.10e-07 | GPU: 13.9GB |
| Step 9,200/300,000 | Epoch 1 | Loss: 10.7424 | LR: 7.15e-07 | GPU: 13.9GB |
**2025-06-16 21:30:15** - CHECKPOINT: Saved at step 9,200, loss 10.2884

**2025-06-16 21:30:16** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_8200.pt

| Step 9,250/300,000 | Epoch 1 | Loss: 10.6417 | LR: 7.20e-07 | GPU: 13.9GB |
| Step 9,300/300,000 | Epoch 1 | Loss: 10.7345 | LR: 7.25e-07 | GPU: 13.9GB |
| Step 9,350/300,000 | Epoch 1 | Loss: 10.6945 | LR: 7.30e-07 | GPU: 13.9GB |
| Step 9,400/300,000 | Epoch 1 | Loss: 10.5582 | LR: 7.30e-07 | GPU: 13.9GB |
**2025-06-16 21:33:12** - CHECKPOINT: Saved at step 9,400, loss 9.5864

**2025-06-16 21:33:13** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_8400.pt

| Step 9,450/300,000 | Epoch 1 | Loss: 10.7521 | LR: 7.35e-07 | GPU: 13.9GB |
| Step 9,500/300,000 | Epoch 1 | Loss: 10.7447 | LR: 7.40e-07 | GPU: 13.9GB |
| Step 9,550/300,000 | Epoch 1 | Loss: 10.7282 | LR: 7.45e-07 | GPU: 13.9GB |
| Step 9,600/300,000 | Epoch 1 | Loss: 10.7151 | LR: 7.50e-07 | GPU: 10.5GB |
**2025-06-16 21:36:08** - CHECKPOINT: Saved at step 9,600, loss 10.3948

**2025-06-16 21:36:09** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_8600.pt

| Step 9,650/300,000 | Epoch 1 | Loss: 10.6491 | LR: 7.50e-07 | GPU: 13.9GB |
| Step 9,700/300,000 | Epoch 1 | Loss: 10.7838 | LR: 7.55e-07 | GPU: 13.9GB |
| Step 9,750/300,000 | Epoch 1 | Loss: 10.8107 | LR: 7.60e-07 | GPU: 13.9GB |
| Step 9,800/300,000 | Epoch 1 | Loss: 10.5718 | LR: 7.65e-07 | GPU: 13.9GB |
**2025-06-16 21:39:05** - CHECKPOINT: Saved at step 9,800, loss 10.8255

**2025-06-16 21:39:06** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_8800.pt

| Step 9,850/300,000 | Epoch 1 | Loss: 10.7088 | LR: 7.65e-07 | GPU: 13.9GB |
| Step 9,900/300,000 | Epoch 1 | Loss: 10.6256 | LR: 7.70e-07 | GPU: 13.9GB |
| Step 9,950/300,000 | Epoch 1 | Loss: 10.6145 | LR: 7.75e-07 | GPU: 13.9GB |
| Step 10,000/300,000 | Epoch 1 | Loss: 10.6355 | LR: 7.80e-07 | GPU: 13.9GB |
**2025-06-16 21:42:02** - CHECKPOINT: Saved at step 10,000, loss 10.0409

**2025-06-16 21:42:03** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_9000.pt

| Step 10,050/300,000 | Epoch 1 | Loss: 10.6201 | LR: 7.85e-07 | GPU: 13.9GB |
| Step 10,100/300,000 | Epoch 1 | Loss: 10.5867 | LR: 7.85e-07 | GPU: 13.9GB |
| Step 10,150/300,000 | Epoch 1 | Loss: 10.7251 | LR: 7.90e-07 | GPU: 13.9GB |
| Step 10,200/300,000 | Epoch 1 | Loss: 10.5944 | LR: 7.95e-07 | GPU: 13.9GB |
**2025-06-16 21:44:58** - CHECKPOINT: Saved at step 10,200, loss 10.5975

**2025-06-16 21:44:59** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_9200.pt

| Step 10,250/300,000 | Epoch 1 | Loss: 10.6740 | LR: 8.00e-07 | GPU: 13.9GB |
| Step 10,300/300,000 | Epoch 1 | Loss: 10.6536 | LR: 8.00e-07 | GPU: 13.9GB |
| Step 10,350/300,000 | Epoch 1 | Loss: 10.6529 | LR: 8.05e-07 | GPU: 13.9GB |
| Step 10,400/300,000 | Epoch 1 | Loss: 10.6707 | LR: 8.10e-07 | GPU: 13.9GB |
**2025-06-16 21:47:55** - CHECKPOINT: Saved at step 10,400, loss 10.4791

**2025-06-16 21:47:56** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_9400.pt

| Step 10,450/300,000 | Epoch 1 | Loss: 10.5376 | LR: 8.15e-07 | GPU: 13.9GB |
| Step 10,500/300,000 | Epoch 1 | Loss: 10.5943 | LR: 8.20e-07 | GPU: 13.9GB |
| Step 10,550/300,000 | Epoch 1 | Loss: 10.6092 | LR: 8.20e-07 | GPU: 13.9GB |
| Step 10,600/300,000 | Epoch 1 | Loss: 10.5433 | LR: 8.25e-07 | GPU: 13.9GB |
**2025-06-16 21:50:52** - CHECKPOINT: Saved at step 10,600, loss 11.0148

**2025-06-16 21:50:53** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_9600.pt

| Step 10,650/300,000 | Epoch 1 | Loss: 10.5293 | LR: 8.30e-07 | GPU: 13.9GB |
| Step 10,700/300,000 | Epoch 1 | Loss: 10.7201 | LR: 8.35e-07 | GPU: 13.9GB |
| Step 10,750/300,000 | Epoch 1 | Loss: 10.4797 | LR: 8.35e-07 | GPU: 13.9GB |
| Step 10,800/300,000 | Epoch 1 | Loss: 10.4959 | LR: 8.40e-07 | GPU: 13.9GB |
**2025-06-16 21:53:49** - CHECKPOINT: Saved at step 10,800, loss 9.1670

**2025-06-16 21:53:50** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_9800.pt

| Step 10,850/300,000 | Epoch 1 | Loss: 10.8333 | LR: 8.45e-07 | GPU: 13.9GB |
| Step 10,900/300,000 | Epoch 1 | Loss: 10.5549 | LR: 8.50e-07 | GPU: 13.9GB |
| Step 10,950/300,000 | Epoch 1 | Loss: 10.6098 | LR: 8.55e-07 | GPU: 13.9GB |
| Step 11,000/300,000 | Epoch 1 | Loss: 10.6117 | LR: 8.55e-07 | GPU: 13.9GB |
**2025-06-16 21:56:46** - CHECKPOINT: Saved at step 11,000, loss 9.9379

| Step 11,050/300,000 | Epoch 1 | Loss: 10.5707 | LR: 8.60e-07 | GPU: 13.9GB |
| Step 11,100/300,000 | Epoch 1 | Loss: 10.5481 | LR: 8.65e-07 | GPU: 13.9GB |
| Step 11,150/300,000 | Epoch 1 | Loss: 10.6360 | LR: 8.70e-07 | GPU: 13.9GB |
| Step 11,200/300,000 | Epoch 1 | Loss: 10.6441 | LR: 8.75e-07 | GPU: 10.5GB |
**2025-06-16 21:59:42** - CHECKPOINT: Saved at step 11,200, loss 10.4420

**2025-06-16 21:59:43** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_10200.pt

| Step 11,250/300,000 | Epoch 1 | Loss: 10.5839 | LR: 8.75e-07 | GPU: 13.9GB |
| Step 11,300/300,000 | Epoch 1 | Loss: 10.5049 | LR: 8.80e-07 | GPU: 13.9GB |
| Step 11,350/300,000 | Epoch 1 | Loss: 10.5891 | LR: 8.85e-07 | GPU: 13.9GB |
| Step 11,400/300,000 | Epoch 1 | Loss: 10.5555 | LR: 8.90e-07 | GPU: 13.9GB |
**2025-06-16 22:02:39** - CHECKPOINT: Saved at step 11,400, loss 10.8012

**2025-06-16 22:02:40** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_10400.pt


**Training Started:** 2025-06-17 19:09:38

## Configuration
- Model: SmolLM2-1.7B
- Dataset: Cosmopedia-100k
- Batch Size: 1
- Gradient Accumulation: 16
- Effective Batch Size: 16
- Max Sequence Length: 2048
- Total Steps: 300,000
- Log Interval: 50 steps
- Checkpoint Interval: 200 steps
- Checkpoint Storage: /mnt/ebs/checkpoints

## Training Progress

**2025-06-17 19:09:38** - Training started on EC2 with EBS storage

**2025-06-17 19:09:38** - Checkpoint directory: /mnt/ebs/checkpoints

**2025-06-17 19:09:38** - Log file: /mnt/ebs/training_log.md

**2025-06-17 19:21:11** - RESUMED: From step 11,400, loss 10.8012

| Step | Epoch | Loss | Learning Rate | GPU Memory |
|------|-------|------|---------------|------------|
**2025-06-17 19:21:11** - EPOCH 1 STARTED

| Step 11,450/300,000 | Epoch 1 | Loss: 10.5287 | LR: 9.05e-07 | GPU: 13.9GB |
| Step 11,500/300,000 | Epoch 1 | Loss: 10.6078 | LR: 9.20e-07 | GPU: 13.9GB |
| Step 11,550/300,000 | Epoch 1 | Loss: 10.4758 | LR: 9.35e-07 | GPU: 13.9GB |
| Step 11,600/300,000 | Epoch 1 | Loss: 10.4207 | LR: 9.55e-07 | GPU: 10.5GB |
**2025-06-17 19:25:02** - CHECKPOINT: Saved at step 11,600, loss 10.1281

**2025-06-17 19:25:02** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_10600.pt

| Step 11,650/300,000 | Epoch 1 | Loss: 10.6171 | LR: 9.70e-07 | GPU: 13.9GB |
| Step 11,700/300,000 | Epoch 1 | Loss: 10.4642 | LR: 9.85e-07 | GPU: 13.9GB |
| Step 11,750/300,000 | Epoch 1 | Loss: 10.4410 | LR: 1.00e-06 | GPU: 13.9GB |
| Step 11,800/300,000 | Epoch 1 | Loss: 10.4700 | LR: 1.02e-06 | GPU: 13.9GB |
**2025-06-17 19:28:00** - CHECKPOINT: Saved at step 11,800, loss 10.7027

**2025-06-17 19:28:01** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_10800.pt

| Step 11,850/300,000 | Epoch 1 | Loss: 10.4018 | LR: 1.03e-06 | GPU: 13.9GB |
| Step 11,900/300,000 | Epoch 1 | Loss: 10.2961 | LR: 1.04e-06 | GPU: 13.9GB |
| Step 11,950/300,000 | Epoch 1 | Loss: 10.3910 | LR: 1.06e-06 | GPU: 13.9GB |
| Step 12,000/300,000 | Epoch 1 | Loss: 10.3538 | LR: 1.08e-06 | GPU: 10.5GB |
**2025-06-17 19:30:59** - CHECKPOINT: Saved at step 12,000, loss 11.2387

**2025-06-17 19:31:00** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_11000.pt

| Step 12,050/300,000 | Epoch 1 | Loss: 10.5135 | LR: 1.09e-06 | GPU: 13.9GB |
| Step 12,100/300,000 | Epoch 1 | Loss: 10.4238 | LR: 1.11e-06 | GPU: 13.9GB |
| Step 12,150/300,000 | Epoch 1 | Loss: 10.2285 | LR: 1.13e-06 | GPU: 13.9GB |
| Step 12,200/300,000 | Epoch 1 | Loss: 10.3704 | LR: 1.14e-06 | GPU: 13.9GB |
**2025-06-17 19:33:57** - CHECKPOINT: Saved at step 12,200, loss 11.0822

**2025-06-17 19:33:58** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_11200.pt

| Step 12,250/300,000 | Epoch 1 | Loss: 10.3253 | LR: 1.15e-06 | GPU: 13.9GB |
| Step 12,300/300,000 | Epoch 1 | Loss: 10.2851 | LR: 1.17e-06 | GPU: 13.9GB |
| Step 12,350/300,000 | Epoch 1 | Loss: 10.2643 | LR: 1.19e-06 | GPU: 13.9GB |
| Step 12,400/300,000 | Epoch 1 | Loss: 10.1718 | LR: 1.21e-06 | GPU: 10.5GB |
**2025-06-17 19:36:56** - CHECKPOINT: Saved at step 12,400, loss 10.4290

**2025-06-17 19:36:57** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_11400.pt

| Step 12,450/300,000 | Epoch 1 | Loss: 10.3286 | LR: 1.22e-06 | GPU: 13.9GB |
| Step 12,500/300,000 | Epoch 1 | Loss: 10.1819 | LR: 1.24e-06 | GPU: 13.9GB |
| Step 12,550/300,000 | Epoch 1 | Loss: 10.2121 | LR: 1.25e-06 | GPU: 13.9GB |
| Step 12,600/300,000 | Epoch 1 | Loss: 10.2301 | LR: 1.26e-06 | GPU: 13.9GB |
**2025-06-17 19:39:55** - CHECKPOINT: Saved at step 12,600, loss 9.9915

**2025-06-17 19:39:56** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_11600.pt

| Step 12,650/300,000 | Epoch 1 | Loss: 10.0697 | LR: 1.28e-06 | GPU: 13.9GB |
| Step 12,700/300,000 | Epoch 1 | Loss: 10.1866 | LR: 1.30e-06 | GPU: 13.9GB |
| Step 12,750/300,000 | Epoch 1 | Loss: 10.0008 | LR: 1.31e-06 | GPU: 13.9GB |
| Step 12,800/300,000 | Epoch 1 | Loss: 10.0395 | LR: 1.33e-06 | GPU: 10.5GB |
**2025-06-17 19:42:53** - CHECKPOINT: Saved at step 12,800, loss 10.2458

**2025-06-17 19:42:54** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_11800.pt

| Step 12,850/300,000 | Epoch 1 | Loss: 10.0479 | LR: 1.35e-06 | GPU: 13.9GB |
| Step 12,900/300,000 | Epoch 1 | Loss: 9.8856 | LR: 1.36e-06 | GPU: 13.9GB |
| Step 12,950/300,000 | Epoch 1 | Loss: 10.0998 | LR: 1.37e-06 | GPU: 13.9GB |
| Step 13,000/300,000 | Epoch 1 | Loss: 10.0267 | LR: 1.39e-06 | GPU: 13.9GB |
**2025-06-17 19:45:52** - CHECKPOINT: Saved at step 13,000, loss 9.9938

| Step 13,050/300,000 | Epoch 1 | Loss: 10.0137 | LR: 1.40e-06 | GPU: 13.9GB |
| Step 13,100/300,000 | Epoch 1 | Loss: 9.8587 | LR: 1.42e-06 | GPU: 13.9GB |
| Step 13,150/300,000 | Epoch 1 | Loss: 9.9408 | LR: 1.44e-06 | GPU: 13.9GB |
| Step 13,200/300,000 | Epoch 1 | Loss: 9.8743 | LR: 1.46e-06 | GPU: 10.5GB |
**2025-06-17 19:48:50** - CHECKPOINT: Saved at step 13,200, loss 9.7868

**2025-06-17 19:48:51** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_12200.pt

| Step 13,250/300,000 | Epoch 1 | Loss: 9.9307 | LR: 1.47e-06 | GPU: 13.9GB |
| Step 13,300/300,000 | Epoch 1 | Loss: 9.8361 | LR: 1.49e-06 | GPU: 13.9GB |
| Step 13,350/300,000 | Epoch 1 | Loss: 9.7386 | LR: 1.50e-06 | GPU: 13.9GB |
| Step 13,400/300,000 | Epoch 1 | Loss: 9.7476 | LR: 1.52e-06 | GPU: 13.9GB |
**2025-06-17 19:51:48** - CHECKPOINT: Saved at step 13,400, loss 8.8459

**2025-06-17 19:51:49** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_12400.pt

| Step 13,450/300,000 | Epoch 1 | Loss: 9.6969 | LR: 1.53e-06 | GPU: 13.9GB |
| Step 13,500/300,000 | Epoch 1 | Loss: 9.7730 | LR: 1.55e-06 | GPU: 13.9GB |
| Step 13,550/300,000 | Epoch 1 | Loss: 9.7671 | LR: 1.56e-06 | GPU: 13.9GB |
| Step 13,600/300,000 | Epoch 1 | Loss: 9.6698 | LR: 1.58e-06 | GPU: 10.5GB |
**2025-06-17 19:54:47** - CHECKPOINT: Saved at step 13,600, loss 10.4357

**2025-06-17 19:54:48** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_12600.pt

| Step 13,650/300,000 | Epoch 1 | Loss: 9.4234 | LR: 1.59e-06 | GPU: 13.9GB |
| Step 13,700/300,000 | Epoch 1 | Loss: 9.6162 | LR: 1.61e-06 | GPU: 13.9GB |
| Step 13,750/300,000 | Epoch 1 | Loss: 9.6598 | LR: 1.63e-06 | GPU: 13.9GB |
| Step 13,800/300,000 | Epoch 1 | Loss: 9.6255 | LR: 1.64e-06 | GPU: 13.9GB |
**2025-06-17 19:57:45** - CHECKPOINT: Saved at step 13,800, loss 10.6356

**2025-06-17 19:57:46** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_12800.pt

| Step 13,850/300,000 | Epoch 1 | Loss: 9.4171 | LR: 1.66e-06 | GPU: 13.9GB |
| Step 13,900/300,000 | Epoch 1 | Loss: 9.3823 | LR: 1.67e-06 | GPU: 13.9GB |
| Step 13,950/300,000 | Epoch 1 | Loss: 9.3224 | LR: 1.68e-06 | GPU: 13.9GB |
| Step 14,000/300,000 | Epoch 1 | Loss: 9.3168 | LR: 1.70e-06 | GPU: 10.5GB |
**2025-06-17 20:00:44** - CHECKPOINT: Saved at step 14,000, loss 10.0013

**2025-06-17 20:00:45** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_13000.pt

| Step 14,050/300,000 | Epoch 1 | Loss: 9.3182 | LR: 1.72e-06 | GPU: 13.9GB |
| Step 14,100/300,000 | Epoch 1 | Loss: 9.2625 | LR: 1.74e-06 | GPU: 13.9GB |
| Step 14,150/300,000 | Epoch 1 | Loss: 9.2332 | LR: 1.75e-06 | GPU: 13.9GB |
| Step 14,200/300,000 | Epoch 1 | Loss: 9.1902 | LR: 1.77e-06 | GPU: 13.9GB |
**2025-06-17 20:03:42** - CHECKPOINT: Saved at step 14,200, loss 8.6913

**2025-06-17 20:03:43** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_13200.pt

| Step 14,250/300,000 | Epoch 1 | Loss: 9.2437 | LR: 1.78e-06 | GPU: 13.9GB |
| Step 14,300/300,000 | Epoch 1 | Loss: 9.4489 | LR: 1.80e-06 | GPU: 13.9GB |
| Step 14,350/300,000 | Epoch 1 | Loss: 9.2921 | LR: 1.81e-06 | GPU: 13.9GB |
| Step 14,400/300,000 | Epoch 1 | Loss: 9.1410 | LR: 1.83e-06 | GPU: 10.5GB |
**2025-06-17 20:06:41** - CHECKPOINT: Saved at step 14,400, loss 9.7185

**2025-06-17 20:06:42** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_13400.pt

| Step 14,450/300,000 | Epoch 1 | Loss: 9.0665 | LR: 1.85e-06 | GPU: 13.9GB |
| Step 14,500/300,000 | Epoch 1 | Loss: 8.8371 | LR: 1.86e-06 | GPU: 13.9GB |
| Step 14,550/300,000 | Epoch 1 | Loss: 8.9908 | LR: 1.88e-06 | GPU: 13.9GB |
| Step 14,600/300,000 | Epoch 1 | Loss: 8.8832 | LR: 1.89e-06 | GPU: 13.9GB |
**2025-06-17 20:09:39** - CHECKPOINT: Saved at step 14,600, loss 7.9301

**2025-06-17 20:09:40** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_13600.pt

| Step 14,650/300,000 | Epoch 1 | Loss: 8.8368 | LR: 1.90e-06 | GPU: 13.9GB |
| Step 14,700/300,000 | Epoch 1 | Loss: 8.9776 | LR: 1.92e-06 | GPU: 13.9GB |
| Step 14,750/300,000 | Epoch 1 | Loss: 8.7529 | LR: 1.94e-06 | GPU: 13.9GB |
| Step 14,800/300,000 | Epoch 1 | Loss: 8.8406 | LR: 1.95e-06 | GPU: 10.5GB |
**2025-06-17 20:12:37** - CHECKPOINT: Saved at step 14,800, loss 8.2461

**2025-06-17 20:12:38** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_13800.pt

| Step 14,850/300,000 | Epoch 1 | Loss: 8.7538 | LR: 1.97e-06 | GPU: 13.9GB |
| Step 14,900/300,000 | Epoch 1 | Loss: 8.6792 | LR: 1.99e-06 | GPU: 13.9GB |
| Step 14,950/300,000 | Epoch 1 | Loss: 8.7623 | LR: 2.00e-06 | GPU: 13.9GB |
| Step 15,000/300,000 | Epoch 1 | Loss: 8.3909 | LR: 2.02e-06 | GPU: 13.9GB |
**2025-06-17 20:15:36** - CHECKPOINT: Saved at step 15,000, loss 9.0460

| Step 15,050/300,000 | Epoch 1 | Loss: 8.5219 | LR: 2.03e-06 | GPU: 13.9GB |
| Step 15,100/300,000 | Epoch 1 | Loss: 8.7211 | LR: 2.04e-06 | GPU: 13.9GB |
| Step 15,150/300,000 | Epoch 1 | Loss: 8.4630 | LR: 2.06e-06 | GPU: 13.9GB |
| Step 15,200/300,000 | Epoch 1 | Loss: 8.3834 | LR: 2.08e-06 | GPU: 10.5GB |
**2025-06-17 20:18:34** - CHECKPOINT: Saved at step 15,200, loss 8.1120

**2025-06-17 20:18:35** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_14200.pt

| Step 15,250/300,000 | Epoch 1 | Loss: 8.5252 | LR: 2.09e-06 | GPU: 13.9GB |
| Step 15,300/300,000 | Epoch 1 | Loss: 8.1988 | LR: 2.11e-06 | GPU: 13.9GB |
| Step 15,350/300,000 | Epoch 1 | Loss: 8.2617 | LR: 2.12e-06 | GPU: 13.9GB |
| Step 15,400/300,000 | Epoch 1 | Loss: 8.1561 | LR: 2.14e-06 | GPU: 13.9GB |
**2025-06-17 20:21:32** - CHECKPOINT: Saved at step 15,400, loss 8.3317

**2025-06-17 20:21:33** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_14400.pt

| Step 15,450/300,000 | Epoch 1 | Loss: 8.0739 | LR: 2.16e-06 | GPU: 13.9GB |
| Step 15,500/300,000 | Epoch 1 | Loss: 7.8862 | LR: 2.17e-06 | GPU: 13.9GB |
| Step 15,550/300,000 | Epoch 1 | Loss: 7.9869 | LR: 2.19e-06 | GPU: 13.9GB |
| Step 15,600/300,000 | Epoch 1 | Loss: 7.9366 | LR: 2.21e-06 | GPU: 10.5GB |
**2025-06-17 20:24:31** - CHECKPOINT: Saved at step 15,600, loss 7.1108

**2025-06-17 20:24:32** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_14600.pt

| Step 15,650/300,000 | Epoch 1 | Loss: 8.1087 | LR: 2.22e-06 | GPU: 13.9GB |
| Step 15,700/300,000 | Epoch 1 | Loss: 7.9453 | LR: 2.23e-06 | GPU: 13.9GB |
| Step 15,750/300,000 | Epoch 1 | Loss: 7.8032 | LR: 2.25e-06 | GPU: 13.9GB |
| Step 15,800/300,000 | Epoch 1 | Loss: 7.6779 | LR: 2.26e-06 | GPU: 13.9GB |
**2025-06-17 20:27:29** - CHECKPOINT: Saved at step 15,800, loss 8.5489

**2025-06-17 20:27:30** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_14800.pt

| Step 15,850/300,000 | Epoch 1 | Loss: 7.6404 | LR: 2.28e-06 | GPU: 13.9GB |
| Step 15,900/300,000 | Epoch 1 | Loss: 7.4927 | LR: 2.30e-06 | GPU: 13.9GB |
| Step 15,950/300,000 | Epoch 1 | Loss: 7.0896 | LR: 2.31e-06 | GPU: 13.9GB |
| Step 16,000/300,000 | Epoch 1 | Loss: 7.0834 | LR: 2.33e-06 | GPU: 10.5GB |
**2025-06-17 20:30:28** - CHECKPOINT: Saved at step 16,000, loss 10.4000

**2025-06-17 20:30:29** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_15000.pt

| Step 16,050/300,000 | Epoch 1 | Loss: 7.3001 | LR: 2.34e-06 | GPU: 13.9GB |
| Step 16,100/300,000 | Epoch 1 | Loss: 7.1430 | LR: 2.36e-06 | GPU: 13.9GB |
| Step 16,150/300,000 | Epoch 1 | Loss: 7.0925 | LR: 2.38e-06 | GPU: 13.9GB |
| Step 16,200/300,000 | Epoch 1 | Loss: 7.1539 | LR: 2.39e-06 | GPU: 13.9GB |
**2025-06-17 20:33:26** - CHECKPOINT: Saved at step 16,200, loss 7.1484

**2025-06-17 20:33:27** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_15200.pt

| Step 16,250/300,000 | Epoch 1 | Loss: 6.4204 | LR: 2.40e-06 | GPU: 13.9GB |
| Step 16,300/300,000 | Epoch 1 | Loss: 6.5920 | LR: 2.42e-06 | GPU: 13.9GB |
| Step 16,350/300,000 | Epoch 1 | Loss: 6.5049 | LR: 2.43e-06 | GPU: 13.9GB |
| Step 16,400/300,000 | Epoch 1 | Loss: 6.7508 | LR: 2.45e-06 | GPU: 10.5GB |
**2025-06-17 20:36:25** - CHECKPOINT: Saved at step 16,400, loss 6.2429

**2025-06-17 20:36:25** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_15400.pt

| Step 16,450/300,000 | Epoch 1 | Loss: 6.2113 | LR: 2.47e-06 | GPU: 13.9GB |
| Step 16,500/300,000 | Epoch 1 | Loss: 6.4182 | LR: 2.48e-06 | GPU: 13.9GB |
| Step 16,550/300,000 | Epoch 1 | Loss: 6.0556 | LR: 2.50e-06 | GPU: 13.9GB |
| Step 16,600/300,000 | Epoch 1 | Loss: 5.9085 | LR: 2.52e-06 | GPU: 13.9GB |
**2025-06-17 20:39:23** - CHECKPOINT: Saved at step 16,600, loss 6.5499

**2025-06-17 20:39:24** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_15600.pt

| Step 16,650/300,000 | Epoch 1 | Loss: 6.0189 | LR: 2.53e-06 | GPU: 13.9GB |
| Step 16,700/300,000 | Epoch 1 | Loss: 5.9139 | LR: 2.54e-06 | GPU: 13.9GB |
| Step 16,750/300,000 | Epoch 1 | Loss: 5.9755 | LR: 2.56e-06 | GPU: 13.9GB |
| Step 16,800/300,000 | Epoch 1 | Loss: 5.9596 | LR: 2.58e-06 | GPU: 10.5GB |
**2025-06-17 20:42:22** - CHECKPOINT: Saved at step 16,800, loss 6.3702

**2025-06-17 20:42:23** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_15800.pt

| Step 16,850/300,000 | Epoch 1 | Loss: 5.6443 | LR: 2.59e-06 | GPU: 13.9GB |
| Step 16,900/300,000 | Epoch 1 | Loss: 5.5966 | LR: 2.61e-06 | GPU: 13.9GB |
| Step 16,950/300,000 | Epoch 1 | Loss: 5.6040 | LR: 2.62e-06 | GPU: 13.9GB |
| Step 17,000/300,000 | Epoch 1 | Loss: 5.3219 | LR: 2.64e-06 | GPU: 13.9GB |
**2025-06-17 20:45:20** - CHECKPOINT: Saved at step 17,000, loss 5.1129

| Step 17,050/300,000 | Epoch 1 | Loss: 5.3738 | LR: 2.65e-06 | GPU: 13.9GB |
| Step 17,100/300,000 | Epoch 1 | Loss: 5.2842 | LR: 2.67e-06 | GPU: 13.9GB |
| Step 17,150/300,000 | Epoch 1 | Loss: 5.2042 | LR: 2.69e-06 | GPU: 13.9GB |
| Step 17,200/300,000 | Epoch 1 | Loss: 5.0969 | LR: 2.71e-06 | GPU: 10.5GB |
**2025-06-17 20:48:18** - CHECKPOINT: Saved at step 17,200, loss 5.2160

**2025-06-17 20:48:19** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_16200.pt

| Step 17,250/300,000 | Epoch 1 | Loss: 5.0608 | LR: 2.72e-06 | GPU: 13.9GB |
| Step 17,300/300,000 | Epoch 1 | Loss: 4.7490 | LR: 2.74e-06 | GPU: 13.9GB |


**Training Started:** 2025-06-18 07:02:45

## Configuration
- Model: SmolLM2-1.7B
- Dataset: Cosmopedia-100k
- Batch Size: 1
- Gradient Accumulation: 16
- Effective Batch Size: 16
- Max Sequence Length: 2048
- Total Steps: 300,000
- Log Interval: 50 steps
- Checkpoint Interval: 200 steps
- Checkpoint Storage: /mnt/ebs/checkpoints

## Training Progress

**2025-06-18 07:02:45** - Training started on EC2 with EBS storage

**2025-06-18 07:02:45** - Checkpoint directory: /mnt/ebs/checkpoints

**2025-06-18 07:02:45** - Log file: /mnt/ebs/training_log.md

**2025-06-18 07:19:44** - RESUMED: From step 17,200, loss 5.2160

| Step | Epoch | Loss | Learning Rate | GPU Memory |
|------|-------|------|---------------|------------|
**2025-06-18 07:19:44** - EPOCH 1 STARTED

| Step 17,250/300,000 | Epoch 1 | Loss: 5.0610 | LR: 2.72e-06 | GPU: 13.9GB |
| Step 17,300/300,000 | Epoch 1 | Loss: 4.7490 | LR: 2.74e-06 | GPU: 13.9GB |
| Step 17,350/300,000 | Epoch 1 | Loss: 5.1774 | LR: 2.75e-06 | GPU: 13.9GB |
| Step 17,400/300,000 | Epoch 1 | Loss: 4.7500 | LR: 2.76e-06 | GPU: 13.9GB |
**2025-06-18 07:25:12** - CHECKPOINT: Saved at step 17,400, loss 6.3617

**2025-06-18 07:25:12** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_16400.pt

| Step 17,450/300,000 | Epoch 1 | Loss: 4.8005 | LR: 2.78e-06 | GPU: 13.9GB |
| Step 17,500/300,000 | Epoch 1 | Loss: 4.7146 | LR: 2.79e-06 | GPU: 13.9GB |
| Step 17,550/300,000 | Epoch 1 | Loss: 4.7785 | LR: 2.81e-06 | GPU: 13.9GB |
| Step 17,600/300,000 | Epoch 1 | Loss: 4.5776 | LR: 2.83e-06 | GPU: 10.5GB |
**2025-06-18 07:28:13** - CHECKPOINT: Saved at step 17,600, loss 4.6703

**2025-06-18 07:28:13** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_16600.pt

| Step 17,650/300,000 | Epoch 1 | Loss: 4.9619 | LR: 2.85e-06 | GPU: 13.9GB |
| Step 17,700/300,000 | Epoch 1 | Loss: 4.3961 | LR: 2.86e-06 | GPU: 13.9GB |
| Step 17,750/300,000 | Epoch 1 | Loss: 4.5292 | LR: 2.88e-06 | GPU: 13.9GB |
| Step 17,800/300,000 | Epoch 1 | Loss: 4.2693 | LR: 2.89e-06 | GPU: 13.9GB |
**2025-06-18 07:31:14** - CHECKPOINT: Saved at step 17,800, loss 3.0143

**2025-06-18 07:31:14** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_16800.pt

| Step 17,850/300,000 | Epoch 1 | Loss: 4.4217 | LR: 2.90e-06 | GPU: 13.9GB |
| Step 17,900/300,000 | Epoch 1 | Loss: 4.3332 | LR: 2.92e-06 | GPU: 13.9GB |
| Step 17,950/300,000 | Epoch 1 | Loss: 4.4623 | LR: 2.93e-06 | GPU: 13.9GB |
| Step 18,000/300,000 | Epoch 1 | Loss: 4.4761 | LR: 2.96e-06 | GPU: 10.5GB |
**2025-06-18 07:34:16** - CHECKPOINT: Saved at step 18,000, loss 3.6114

**2025-06-18 07:34:16** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_17000.pt

| Step 18,050/300,000 | Epoch 1 | Loss: 4.7178 | LR: 2.97e-06 | GPU: 13.9GB |
| Step 18,100/300,000 | Epoch 1 | Loss: 4.3900 | LR: 2.99e-06 | GPU: 13.9GB |
| Step 18,150/300,000 | Epoch 1 | Loss: 4.7612 | LR: 3.00e-06 | GPU: 13.9GB |
| Step 18,200/300,000 | Epoch 1 | Loss: 4.4860 | LR: 3.02e-06 | GPU: 13.9GB |
**2025-06-18 07:37:17** - CHECKPOINT: Saved at step 18,200, loss 4.9070

**2025-06-18 07:37:17** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_17200.pt

| Step 18,250/300,000 | Epoch 1 | Loss: 4.3042 | LR: 3.03e-06 | GPU: 13.9GB |
| Step 18,300/300,000 | Epoch 1 | Loss: 4.4274 | LR: 3.05e-06 | GPU: 13.9GB |
| Step 18,350/300,000 | Epoch 1 | Loss: 4.1751 | LR: 3.06e-06 | GPU: 13.9GB |
| Step 18,400/300,000 | Epoch 1 | Loss: 4.5395 | LR: 3.08e-06 | GPU: 10.5GB |
**2025-06-18 07:40:19** - CHECKPOINT: Saved at step 18,400, loss 3.1170

**2025-06-18 07:40:19** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_17400.pt

| Step 18,450/300,000 | Epoch 1 | Loss: 4.4574 | LR: 3.10e-06 | GPU: 13.9GB |
| Step 18,500/300,000 | Epoch 1 | Loss: 4.0564 | LR: 3.11e-06 | GPU: 13.9GB |
| Step 18,550/300,000 | Epoch 1 | Loss: 4.4180 | LR: 3.13e-06 | GPU: 13.9GB |
| Step 18,600/300,000 | Epoch 1 | Loss: 4.2385 | LR: 3.14e-06 | GPU: 13.9GB |
**2025-06-18 07:43:20** - CHECKPOINT: Saved at step 18,600, loss 3.2867

**2025-06-18 07:43:20** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_17600.pt

| Step 18,650/300,000 | Epoch 1 | Loss: 4.0547 | LR: 3.16e-06 | GPU: 13.9GB |
| Step 18,700/300,000 | Epoch 1 | Loss: 4.0747 | LR: 3.17e-06 | GPU: 13.9GB |
| Step 18,750/300,000 | Epoch 1 | Loss: 4.4930 | LR: 3.19e-06 | GPU: 13.9GB |
| Step 18,800/300,000 | Epoch 1 | Loss: 4.3970 | LR: 3.21e-06 | GPU: 10.5GB |
**2025-06-18 07:46:21** - CHECKPOINT: Saved at step 18,800, loss 5.1811

**2025-06-18 07:46:21** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_17800.pt

| Step 18,850/300,000 | Epoch 1 | Loss: 4.2068 | LR: 3.22e-06 | GPU: 13.9GB |
| Step 18,900/300,000 | Epoch 1 | Loss: 4.2398 | LR: 3.24e-06 | GPU: 13.9GB |
| Step 18,950/300,000 | Epoch 1 | Loss: 4.0159 | LR: 3.25e-06 | GPU: 13.9GB |
| Step 19,000/300,000 | Epoch 1 | Loss: 4.0329 | LR: 3.27e-06 | GPU: 13.9GB |
**2025-06-18 07:49:22** - CHECKPOINT: Saved at step 19,000, loss 3.2466

| Step 19,050/300,000 | Epoch 1 | Loss: 4.4978 | LR: 3.28e-06 | GPU: 13.9GB |
| Step 19,100/300,000 | Epoch 1 | Loss: 4.1968 | LR: 3.30e-06 | GPU: 13.9GB |
| Step 19,150/300,000 | Epoch 1 | Loss: 4.0678 | LR: 3.31e-06 | GPU: 13.9GB |
| Step 19,200/300,000 | Epoch 1 | Loss: 3.9786 | LR: 3.33e-06 | GPU: 10.5GB |
**2025-06-18 07:52:23** - CHECKPOINT: Saved at step 19,200, loss 3.6111

**2025-06-18 07:52:23** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_18200.pt

| Step 19,250/300,000 | Epoch 1 | Loss: 4.1488 | LR: 3.35e-06 | GPU: 13.9GB |
| Step 19,300/300,000 | Epoch 1 | Loss: 4.2989 | LR: 3.36e-06 | GPU: 13.9GB |
| Step 19,350/300,000 | Epoch 1 | Loss: 3.9661 | LR: 3.38e-06 | GPU: 13.9GB |
| Step 19,400/300,000 | Epoch 1 | Loss: 4.0707 | LR: 3.39e-06 | GPU: 13.9GB |
**2025-06-18 07:55:24** - CHECKPOINT: Saved at step 19,400, loss 3.0036

**2025-06-18 07:55:24** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_18400.pt

| Step 19,450/300,000 | Epoch 1 | Loss: 4.5002 | LR: 3.41e-06 | GPU: 13.9GB |
| Step 19,500/300,000 | Epoch 1 | Loss: 4.0916 | LR: 3.42e-06 | GPU: 13.9GB |
| Step 19,550/300,000 | Epoch 1 | Loss: 4.1185 | LR: 3.44e-06 | GPU: 13.9GB |
| Step 19,600/300,000 | Epoch 1 | Loss: 4.0291 | LR: 3.45e-06 | GPU: 10.5GB |
**2025-06-18 07:58:25** - CHECKPOINT: Saved at step 19,600, loss 3.7722

**2025-06-18 07:58:25** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_18600.pt

| Step 19,650/300,000 | Epoch 1 | Loss: 4.0978 | LR: 3.47e-06 | GPU: 13.9GB |
| Step 19,700/300,000 | Epoch 1 | Loss: 4.1362 | LR: 3.49e-06 | GPU: 13.9GB |
| Step 19,750/300,000 | Epoch 1 | Loss: 3.8614 | LR: 3.50e-06 | GPU: 13.9GB |
| Step 19,800/300,000 | Epoch 1 | Loss: 3.8579 | LR: 3.52e-06 | GPU: 13.9GB |
**2025-06-18 08:01:26** - CHECKPOINT: Saved at step 19,800, loss 3.5965

**2025-06-18 08:01:26** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_18800.pt

| Step 19,850/300,000 | Epoch 1 | Loss: 3.9614 | LR: 3.53e-06 | GPU: 13.9GB |
| Step 19,900/300,000 | Epoch 1 | Loss: 4.1876 | LR: 3.55e-06 | GPU: 13.9GB |
| Step 19,950/300,000 | Epoch 1 | Loss: 4.3751 | LR: 3.56e-06 | GPU: 13.9GB |
| Step 20,000/300,000 | Epoch 1 | Loss: 4.1861 | LR: 3.58e-06 | GPU: 10.5GB |
**2025-06-18 08:04:28** - CHECKPOINT: Saved at step 20,000, loss 6.2510

**2025-06-18 08:04:28** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_19000.pt

| Step 20,050/300,000 | Epoch 1 | Loss: 4.0851 | LR: 3.59e-06 | GPU: 13.9GB |
| Step 20,100/300,000 | Epoch 1 | Loss: 3.7435 | LR: 3.61e-06 | GPU: 13.9GB |
| Step 20,150/300,000 | Epoch 1 | Loss: 4.2052 | LR: 3.63e-06 | GPU: 13.9GB |
| Step 20,200/300,000 | Epoch 1 | Loss: 4.0689 | LR: 3.64e-06 | GPU: 13.9GB |
**2025-06-18 08:07:29** - CHECKPOINT: Saved at step 20,200, loss 4.6206

**2025-06-18 08:07:29** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_19200.pt

| Step 20,250/300,000 | Epoch 1 | Loss: 3.8971 | LR: 3.66e-06 | GPU: 13.9GB |
| Step 20,300/300,000 | Epoch 1 | Loss: 4.3570 | LR: 3.67e-06 | GPU: 13.9GB |
| Step 20,350/300,000 | Epoch 1 | Loss: 4.0401 | LR: 3.69e-06 | GPU: 13.9GB |
| Step 20,400/300,000 | Epoch 1 | Loss: 4.1760 | LR: 3.71e-06 | GPU: 10.5GB |
**2025-06-18 08:10:30** - CHECKPOINT: Saved at step 20,400, loss 3.9842

**2025-06-18 08:10:30** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_19400.pt

| Step 20,450/300,000 | Epoch 1 | Loss: 4.3957 | LR: 3.72e-06 | GPU: 13.9GB |
| Step 20,500/300,000 | Epoch 1 | Loss: 4.2460 | LR: 3.74e-06 | GPU: 13.9GB |
| Step 20,550/300,000 | Epoch 1 | Loss: 4.1139 | LR: 3.75e-06 | GPU: 13.9GB |
| Step 20,600/300,000 | Epoch 1 | Loss: 4.0703 | LR: 3.76e-06 | GPU: 13.9GB |
**2025-06-18 08:13:31** - CHECKPOINT: Saved at step 20,600, loss 2.7915

**2025-06-18 08:13:31** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_19600.pt

| Step 20,650/300,000 | Epoch 1 | Loss: 3.9121 | LR: 3.78e-06 | GPU: 13.9GB |
| Step 20,700/300,000 | Epoch 1 | Loss: 4.0032 | LR: 3.80e-06 | GPU: 13.9GB |
| Step 20,750/300,000 | Epoch 1 | Loss: 3.9551 | LR: 3.81e-06 | GPU: 13.9GB |
| Step 20,800/300,000 | Epoch 1 | Loss: 3.9574 | LR: 3.83e-06 | GPU: 10.5GB |
**2025-06-18 08:16:33** - CHECKPOINT: Saved at step 20,800, loss 5.4764

**2025-06-18 08:16:33** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_19800.pt

| Step 20,850/300,000 | Epoch 1 | Loss: 3.7404 | LR: 3.85e-06 | GPU: 13.9GB |
| Step 20,900/300,000 | Epoch 1 | Loss: 4.0515 | LR: 3.86e-06 | GPU: 13.9GB |
| Step 20,950/300,000 | Epoch 1 | Loss: 4.0724 | LR: 3.88e-06 | GPU: 13.9GB |
| Step 21,000/300,000 | Epoch 1 | Loss: 3.9492 | LR: 3.89e-06 | GPU: 13.9GB |
**2025-06-18 08:19:34** - CHECKPOINT: Saved at step 21,000, loss 1.6542

| Step 21,050/300,000 | Epoch 1 | Loss: 4.1410 | LR: 3.91e-06 | GPU: 13.9GB |
| Step 21,100/300,000 | Epoch 1 | Loss: 4.0590 | LR: 3.92e-06 | GPU: 13.9GB |
| Step 21,150/300,000 | Epoch 1 | Loss: 3.8027 | LR: 3.93e-06 | GPU: 13.9GB |
| Step 21,200/300,000 | Epoch 1 | Loss: 3.6460 | LR: 3.96e-06 | GPU: 10.5GB |
**2025-06-18 08:22:34** - CHECKPOINT: Saved at step 21,200, loss 4.2624

**2025-06-18 08:22:34** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_20200.pt

| Step 21,250/300,000 | Epoch 1 | Loss: 4.0601 | LR: 3.97e-06 | GPU: 13.9GB |
| Step 21,300/300,000 | Epoch 1 | Loss: 4.1061 | LR: 3.98e-06 | GPU: 13.9GB |
| Step 21,350/300,000 | Epoch 1 | Loss: 3.6735 | LR: 4.00e-06 | GPU: 13.9GB |
| Step 21,400/300,000 | Epoch 1 | Loss: 3.7881 | LR: 4.01e-06 | GPU: 13.9GB |
**2025-06-18 08:25:35** - CHECKPOINT: Saved at step 21,400, loss 3.6018

**2025-06-18 08:25:35** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_20400.pt

| Step 21,450/300,000 | Epoch 1 | Loss: 4.1720 | LR: 4.03e-06 | GPU: 13.9GB |
| Step 21,500/300,000 | Epoch 1 | Loss: 4.2033 | LR: 4.05e-06 | GPU: 13.9GB |
| Step 21,550/300,000 | Epoch 1 | Loss: 3.8525 | LR: 4.06e-06 | GPU: 13.9GB |
| Step 21,600/300,000 | Epoch 1 | Loss: 4.0513 | LR: 4.08e-06 | GPU: 10.5GB |
**2025-06-18 08:28:36** - CHECKPOINT: Saved at step 21,600, loss 7.2900

**2025-06-18 08:28:36** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_20600.pt

| Step 21,650/300,000 | Epoch 1 | Loss: 4.2598 | LR: 4.10e-06 | GPU: 13.9GB |
| Step 21,700/300,000 | Epoch 1 | Loss: 3.8821 | LR: 4.11e-06 | GPU: 13.9GB |
| Step 21,750/300,000 | Epoch 1 | Loss: 4.5434 | LR: 4.13e-06 | GPU: 13.9GB |
| Step 21,800/300,000 | Epoch 1 | Loss: 4.1878 | LR: 4.14e-06 | GPU: 13.9GB |
**2025-06-18 08:31:37** - CHECKPOINT: Saved at step 21,800, loss 5.6403

**2025-06-18 08:31:38** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_20800.pt

| Step 21,850/300,000 | Epoch 1 | Loss: 3.7652 | LR: 4.16e-06 | GPU: 13.9GB |
| Step 21,900/300,000 | Epoch 1 | Loss: 3.9810 | LR: 4.17e-06 | GPU: 13.9GB |
| Step 21,950/300,000 | Epoch 1 | Loss: 4.3929 | LR: 4.19e-06 | GPU: 13.9GB |
| Step 22,000/300,000 | Epoch 1 | Loss: 3.6008 | LR: 4.20e-06 | GPU: 10.5GB |
**2025-06-18 08:34:39** - CHECKPOINT: Saved at step 22,000, loss 2.0448

**2025-06-18 08:34:39** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_21000.pt

| Step 22,050/300,000 | Epoch 1 | Loss: 3.8773 | LR: 4.22e-06 | GPU: 13.9GB |
| Step 22,100/300,000 | Epoch 1 | Loss: 3.8061 | LR: 4.24e-06 | GPU: 13.9GB |
| Step 22,150/300,000 | Epoch 1 | Loss: 4.0480 | LR: 4.25e-06 | GPU: 13.9GB |
| Step 22,200/300,000 | Epoch 1 | Loss: 3.9454 | LR: 4.26e-06 | GPU: 13.9GB |
**2025-06-18 08:37:40** - CHECKPOINT: Saved at step 22,200, loss 3.9850

**2025-06-18 08:37:40** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_21200.pt

| Step 22,250/300,000 | Epoch 1 | Loss: 3.8433 | LR: 4.28e-06 | GPU: 13.9GB |
| Step 22,300/300,000 | Epoch 1 | Loss: 3.9763 | LR: 4.30e-06 | GPU: 13.9GB |
| Step 22,350/300,000 | Epoch 1 | Loss: 4.1104 | LR: 4.31e-06 | GPU: 13.9GB |
| Step 22,400/300,000 | Epoch 1 | Loss: 4.0406 | LR: 4.33e-06 | GPU: 10.5GB |
**2025-06-18 08:40:41** - CHECKPOINT: Saved at step 22,400, loss 3.6894

**2025-06-18 08:40:41** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_21400.pt

| Step 22,450/300,000 | Epoch 1 | Loss: 3.8674 | LR: 4.35e-06 | GPU: 13.9GB |
| Step 22,500/300,000 | Epoch 1 | Loss: 3.8222 | LR: 4.36e-06 | GPU: 13.9GB |
| Step 22,550/300,000 | Epoch 1 | Loss: 3.6524 | LR: 4.38e-06 | GPU: 13.9GB |
| Step 22,600/300,000 | Epoch 1 | Loss: 3.8547 | LR: 4.39e-06 | GPU: 13.9GB |
**2025-06-18 08:43:42** - CHECKPOINT: Saved at step 22,600, loss 5.9722

**2025-06-18 08:43:42** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_21600.pt

| Step 22,650/300,000 | Epoch 1 | Loss: 3.4123 | LR: 4.41e-06 | GPU: 13.9GB |
| Step 22,700/300,000 | Epoch 1 | Loss: 3.5373 | LR: 4.42e-06 | GPU: 13.9GB |
| Step 22,750/300,000 | Epoch 1 | Loss: 3.4826 | LR: 4.44e-06 | GPU: 13.9GB |
| Step 22,800/300,000 | Epoch 1 | Loss: 3.7142 | LR: 4.45e-06 | GPU: 10.5GB |
**2025-06-18 08:46:43** - CHECKPOINT: Saved at step 22,800, loss 4.3810

**2025-06-18 08:46:43** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_21800.pt

| Step 22,850/300,000 | Epoch 1 | Loss: 3.8752 | LR: 4.47e-06 | GPU: 13.9GB |
| Step 22,900/300,000 | Epoch 1 | Loss: 3.8226 | LR: 4.49e-06 | GPU: 13.9GB |
| Step 22,950/300,000 | Epoch 1 | Loss: 3.8008 | LR: 4.50e-06 | GPU: 13.9GB |
| Step 23,000/300,000 | Epoch 1 | Loss: 3.9250 | LR: 4.51e-06 | GPU: 13.9GB |
**2025-06-18 08:49:45** - CHECKPOINT: Saved at step 23,000, loss 3.2786

| Step 23,050/300,000 | Epoch 1 | Loss: 3.9762 | LR: 4.53e-06 | GPU: 13.9GB |
| Step 23,100/300,000 | Epoch 1 | Loss: 3.6511 | LR: 4.54e-06 | GPU: 13.9GB |
| Step 23,150/300,000 | Epoch 1 | Loss: 3.7530 | LR: 4.56e-06 | GPU: 13.9GB |
| Step 23,200/300,000 | Epoch 1 | Loss: 3.6007 | LR: 4.58e-06 | GPU: 10.5GB |
**2025-06-18 08:52:45** - CHECKPOINT: Saved at step 23,200, loss 4.0620

**2025-06-18 08:52:46** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_22200.pt

| Step 23,250/300,000 | Epoch 1 | Loss: 3.9227 | LR: 4.60e-06 | GPU: 13.9GB |
| Step 23,300/300,000 | Epoch 1 | Loss: 3.5477 | LR: 4.61e-06 | GPU: 13.9GB |
| Step 23,350/300,000 | Epoch 1 | Loss: 3.8203 | LR: 4.63e-06 | GPU: 13.9GB |
| Step 23,400/300,000 | Epoch 1 | Loss: 3.7045 | LR: 4.64e-06 | GPU: 13.9GB |
**2025-06-18 08:55:47** - CHECKPOINT: Saved at step 23,400, loss 4.4789

**2025-06-18 08:55:47** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_22400.pt

| Step 23,450/300,000 | Epoch 1 | Loss: 3.6257 | LR: 4.66e-06 | GPU: 13.9GB |
| Step 23,500/300,000 | Epoch 1 | Loss: 3.6684 | LR: 4.67e-06 | GPU: 13.9GB |
| Step 23,550/300,000 | Epoch 1 | Loss: 3.6968 | LR: 4.69e-06 | GPU: 13.9GB |
| Step 23,600/300,000 | Epoch 1 | Loss: 3.6663 | LR: 4.70e-06 | GPU: 10.5GB |
**2025-06-18 08:58:48** - CHECKPOINT: Saved at step 23,600, loss 6.5850

**2025-06-18 08:58:48** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_22600.pt

| Step 23,650/300,000 | Epoch 1 | Loss: 3.3707 | LR: 4.72e-06 | GPU: 13.9GB |
| Step 23,700/300,000 | Epoch 1 | Loss: 3.7289 | LR: 4.73e-06 | GPU: 13.9GB |
| Step 23,750/300,000 | Epoch 1 | Loss: 3.6281 | LR: 4.75e-06 | GPU: 13.9GB |
| Step 23,800/300,000 | Epoch 1 | Loss: 3.9158 | LR: 4.77e-06 | GPU: 13.9GB |
**2025-06-18 09:01:49** - CHECKPOINT: Saved at step 23,800, loss 3.7653

**2025-06-18 09:01:49** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_22800.pt

| Step 23,850/300,000 | Epoch 1 | Loss: 3.6635 | LR: 4.78e-06 | GPU: 13.9GB |
| Step 23,900/300,000 | Epoch 1 | Loss: 3.5174 | LR: 4.79e-06 | GPU: 13.9GB |
| Step 23,950/300,000 | Epoch 1 | Loss: 3.6645 | LR: 4.81e-06 | GPU: 13.9GB |
| Step 24,000/300,000 | Epoch 1 | Loss: 3.5547 | LR: 4.83e-06 | GPU: 10.5GB |
**2025-06-18 09:04:51** - CHECKPOINT: Saved at step 24,000, loss 3.9836

**2025-06-18 09:04:51** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_23000.pt

| Step 24,050/300,000 | Epoch 1 | Loss: 3.5785 | LR: 4.85e-06 | GPU: 13.9GB |
| Step 24,100/300,000 | Epoch 1 | Loss: 3.5784 | LR: 4.86e-06 | GPU: 13.9GB |
| Step 24,150/300,000 | Epoch 1 | Loss: 3.7358 | LR: 4.87e-06 | GPU: 13.9GB |
| Step 24,200/300,000 | Epoch 1 | Loss: 3.6124 | LR: 4.89e-06 | GPU: 13.9GB |
**2025-06-18 09:07:52** - CHECKPOINT: Saved at step 24,200, loss 3.8996

**2025-06-18 09:07:52** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_23200.pt

| Step 24,250/300,000 | Epoch 1 | Loss: 3.2724 | LR: 4.91e-06 | GPU: 13.9GB |
| Step 24,300/300,000 | Epoch 1 | Loss: 3.8093 | LR: 4.92e-06 | GPU: 13.9GB |
| Step 24,350/300,000 | Epoch 1 | Loss: 3.5350 | LR: 4.94e-06 | GPU: 13.9GB |
| Step 24,400/300,000 | Epoch 1 | Loss: 3.6226 | LR: 4.95e-06 | GPU: 10.5GB |
**2025-06-18 09:10:53** - CHECKPOINT: Saved at step 24,400, loss 2.8176

**2025-06-18 09:10:54** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_23400.pt

| Step 24,450/300,000 | Epoch 1 | Loss: 3.4690 | LR: 4.97e-06 | GPU: 13.9GB |
| Step 24,500/300,000 | Epoch 1 | Loss: 4.1166 | LR: 4.98e-06 | GPU: 13.9GB |
| Step 24,550/300,000 | Epoch 1 | Loss: 3.5302 | LR: 5.00e-06 | GPU: 13.9GB |
| Step 24,600/300,000 | Epoch 1 | Loss: 3.5266 | LR: 5.02e-06 | GPU: 13.9GB |
**2025-06-18 09:13:54** - CHECKPOINT: Saved at step 24,600, loss 3.6146

**2025-06-18 09:13:55** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_23600.pt

| Step 24,650/300,000 | Epoch 1 | Loss: 3.3803 | LR: 5.03e-06 | GPU: 13.9GB |
| Step 24,700/300,000 | Epoch 1 | Loss: 3.4897 | LR: 5.04e-06 | GPU: 13.9GB |
| Step 24,750/300,000 | Epoch 1 | Loss: 3.2782 | LR: 5.06e-06 | GPU: 13.9GB |
| Step 24,800/300,000 | Epoch 1 | Loss: 3.6209 | LR: 5.08e-06 | GPU: 10.5GB |
**2025-06-18 09:16:56** - CHECKPOINT: Saved at step 24,800, loss 5.2137

**2025-06-18 09:16:56** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_23800.pt

| Step 24,850/300,000 | Epoch 1 | Loss: 3.5132 | LR: 5.10e-06 | GPU: 13.9GB |
| Step 24,900/300,000 | Epoch 1 | Loss: 3.5988 | LR: 5.11e-06 | GPU: 13.9GB |
| Step 24,950/300,000 | Epoch 1 | Loss: 3.3944 | LR: 5.13e-06 | GPU: 13.9GB |
| Step 25,000/300,000 | Epoch 1 | Loss: 3.5472 | LR: 5.14e-06 | GPU: 13.9GB |
**2025-06-18 09:19:57** - CHECKPOINT: Saved at step 25,000, loss 2.7946

| Step 25,050/300,000 | Epoch 1 | Loss: 3.5966 | LR: 5.16e-06 | GPU: 13.9GB |
| Step 25,100/300,000 | Epoch 1 | Loss: 3.4231 | LR: 5.17e-06 | GPU: 13.9GB |
| Step 25,150/300,000 | Epoch 1 | Loss: 3.7821 | LR: 5.19e-06 | GPU: 13.9GB |
| Step 25,200/300,000 | Epoch 1 | Loss: 3.3388 | LR: 5.21e-06 | GPU: 10.5GB |
**2025-06-18 09:22:58** - CHECKPOINT: Saved at step 25,200, loss 5.5049

**2025-06-18 09:22:58** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_24200.pt

| Step 25,250/300,000 | Epoch 1 | Loss: 3.6416 | LR: 5.22e-06 | GPU: 13.9GB |
| Step 25,300/300,000 | Epoch 1 | Loss: 3.3971 | LR: 5.23e-06 | GPU: 13.9GB |
| Step 25,350/300,000 | Epoch 1 | Loss: 3.4718 | LR: 5.25e-06 | GPU: 13.9GB |
| Step 25,400/300,000 | Epoch 1 | Loss: 3.2824 | LR: 5.26e-06 | GPU: 13.9GB |
**2025-06-18 09:25:59** - CHECKPOINT: Saved at step 25,400, loss 0.9918

**2025-06-18 09:25:59** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_24400.pt

| Step 25,450/300,000 | Epoch 1 | Loss: 3.1557 | LR: 5.28e-06 | GPU: 13.9GB |
| Step 25,500/300,000 | Epoch 1 | Loss: 3.3515 | LR: 5.30e-06 | GPU: 13.9GB |
| Step 25,550/300,000 | Epoch 1 | Loss: 3.2668 | LR: 5.31e-06 | GPU: 13.9GB |
| Step 25,600/300,000 | Epoch 1 | Loss: 3.3934 | LR: 5.33e-06 | GPU: 10.5GB |
**2025-06-18 09:29:01** - CHECKPOINT: Saved at step 25,600, loss 2.4106

**2025-06-18 09:29:01** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_24600.pt

| Step 25,650/300,000 | Epoch 1 | Loss: 3.3550 | LR: 5.35e-06 | GPU: 13.9GB |
| Step 25,700/300,000 | Epoch 1 | Loss: 3.6433 | LR: 5.36e-06 | GPU: 13.9GB |
| Step 25,750/300,000 | Epoch 1 | Loss: 3.6294 | LR: 5.38e-06 | GPU: 13.9GB |
| Step 25,800/300,000 | Epoch 1 | Loss: 3.3537 | LR: 5.39e-06 | GPU: 13.9GB |
**2025-06-18 09:32:02** - CHECKPOINT: Saved at step 25,800, loss 5.3193

**2025-06-18 09:32:02** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_24800.pt

| Step 25,850/300,000 | Epoch 1 | Loss: 3.2332 | LR: 5.40e-06 | GPU: 13.9GB |
| Step 25,900/300,000 | Epoch 1 | Loss: 3.4768 | LR: 5.42e-06 | GPU: 13.9GB |
| Step 25,950/300,000 | Epoch 1 | Loss: 3.3099 | LR: 5.44e-06 | GPU: 13.9GB |
| Step 26,000/300,000 | Epoch 1 | Loss: 3.4110 | LR: 5.46e-06 | GPU: 10.5GB |
**2025-06-18 09:35:03** - CHECKPOINT: Saved at step 26,000, loss 1.9232

**2025-06-18 09:35:03** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_25000.pt

| Step 26,050/300,000 | Epoch 1 | Loss: 3.5179 | LR: 5.47e-06 | GPU: 13.9GB |
| Step 26,100/300,000 | Epoch 1 | Loss: 3.5042 | LR: 5.49e-06 | GPU: 13.9GB |
| Step 26,150/300,000 | Epoch 1 | Loss: 3.2180 | LR: 5.50e-06 | GPU: 13.9GB |
| Step 26,200/300,000 | Epoch 1 | Loss: 3.3999 | LR: 5.51e-06 | GPU: 13.9GB |
**2025-06-18 09:38:04** - CHECKPOINT: Saved at step 26,200, loss 2.5703

**2025-06-18 09:38:04** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_25200.pt

| Step 26,250/300,000 | Epoch 1 | Loss: 3.2488 | LR: 5.53e-06 | GPU: 13.9GB |
| Step 26,300/300,000 | Epoch 1 | Loss: 3.3479 | LR: 5.54e-06 | GPU: 13.9GB |
| Step 26,350/300,000 | Epoch 1 | Loss: 3.3389 | LR: 5.56e-06 | GPU: 13.9GB |
| Step 26,400/300,000 | Epoch 1 | Loss: 3.2846 | LR: 5.58e-06 | GPU: 10.5GB |
**2025-06-18 09:41:05** - CHECKPOINT: Saved at step 26,400, loss 3.5635

**2025-06-18 09:41:05** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_25400.pt

| Step 26,450/300,000 | Epoch 1 | Loss: 3.1632 | LR: 5.59e-06 | GPU: 13.9GB |
| Step 26,500/300,000 | Epoch 1 | Loss: 3.2364 | LR: 5.61e-06 | GPU: 13.9GB |
| Step 26,550/300,000 | Epoch 1 | Loss: 2.9764 | LR: 5.63e-06 | GPU: 13.9GB |
| Step 26,600/300,000 | Epoch 1 | Loss: 3.3152 | LR: 5.64e-06 | GPU: 13.9GB |
**2025-06-18 09:44:06** - CHECKPOINT: Saved at step 26,600, loss 3.3310

**2025-06-18 09:44:06** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_25600.pt

| Step 26,650/300,000 | Epoch 1 | Loss: 3.0938 | LR: 5.66e-06 | GPU: 13.9GB |
| Step 26,700/300,000 | Epoch 1 | Loss: 3.2565 | LR: 5.67e-06 | GPU: 13.9GB |
| Step 26,750/300,000 | Epoch 1 | Loss: 3.3365 | LR: 5.68e-06 | GPU: 13.9GB |
| Step 26,800/300,000 | Epoch 1 | Loss: 3.2796 | LR: 5.71e-06 | GPU: 10.5GB |
**2025-06-18 09:47:07** - CHECKPOINT: Saved at step 26,800, loss 3.7161

**2025-06-18 09:47:08** - CLEANUP: Removed checkpoint /mnt/ebs/checkpoints/checkpoint_step_25800.pt

| Step 26,850/300,000 | Epoch 1 | Loss: 3.4610 | LR: 5.72e-06 | GPU: 13.9GB |
| Step 26,900/300,000 | Epoch 1 | Loss: 3.4403 | LR: 5.74e-06 | GPU: 13.9GB |
| Step 26,950/300,000 | Epoch 1 | Loss: 3.2964 | LR: 5.75e-06 | GPU: 13.9GB |
| Step 27,000/300,000 | Epoch 1 | Loss: 3.2761 | LR: 5.77e-06 | GPU: 13.9GB |
**2025-06-18 09:50:08** - CHECKPOINT: Saved at step 27,000, loss 2.4894


**2025-06-18 09:58:58** - FINAL: Training ended at step 27,000

**2025-06-18 09:58:58** - Training completed successfully. Total steps: 27,000

**2025-06-18 09:58:58** - Available checkpoints: 18 files

