### Checkpoints:
Dreamshaper ver. 8 - https://civitai.com/models/4384/dreamshaper

AbsoluteReality - https://civitai.com/models/81458/absolutereality

DreamshaperXL - https://civitai.com/models/112902/dreamshaper-xl

### VAE:
vae-ft-mse-840000-ema-pruned.safetensors
https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main

temporaldiff-v1-animatediff.ckpt (Optional, not used in demo workflows)
https://huggingface.co/CiaraRowles/TemporalDiff/tree/main


### Custom Nodes:
Must Get: https://github.com/ltdrdata/ComfyUI-Manager - This helps you find and load "missing" Node types via a GUI!
Put this inside: custom_nodes


https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved

Models for ComfyUI-AnimateDiff-Evolved:
Put inside:  custom_nodes\ComfyUI-AnimateDiff-Evolved\models
mm-Stabilized_high.pth
mm-Stabilized_mid.pth
https://huggingface.co/manshoety/AD_Stabilized_Motion/tree/main

Also:
temporaldiff-v1-animatediff.safetensors
https://huggingface.co/CiaraRowles/TemporalDiff/tree/main
 

### upscale_models:

4xUltrasharp_4xUltrasharpV10.pt
Origionally - https://openmodeldb.info/models/4x-UltraSharp
But you can get it from: 
https://huggingface.co/vclansience/SD_lora/tree/main

### LoRA:
https://civitai.com/models/91775/neofuturistic-tech-world-morph

https://civitai.com/models/122563/lora-moon

https://civitai.com/models/355518/cute-collectible

### Embeddings:
FastNegativeV2.pt
https://civitai.com/models/71961
Put: (FastNegativeEmbedding:0.9) in the Negative prompt only

negative_hand-neg.pt
https://civitai.com/models/56519/negativehand-negative-embedding
Fix bad hands, put (negative_hand) in the Negative prompt only