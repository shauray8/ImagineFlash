# ImagineFlash
A minimal repro for SDXL + ImageFlash : Accelerating Emu Diffusion Models with Backward Distillation 

## From the Paper
Rather then accelerating EMU Diffusion which is a text-to-image model from Meta (I guess) here we concentrate on making SDXLs faster with Backward distillation 

1. uses backward distillation - addresses the discrepancy between training and inference distribution of diffusion models. 
during conventional forward distillation the student learns to denoise latents that contain information from the ground truth signal leading to a mismatch during inference when the student relies on its own prediction 

2. Noise Correction 

3. shifted reconstruction loss 




