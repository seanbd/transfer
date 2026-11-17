In Python
conda create -n comfyui python=3.13
conda activate comfyui

Extract ComfyUI.zip file
Extract ComfyUI_wheels
in ComfyUI_wheels:
pip install -r requirements.txt

Launch ComfyUI with
python main.py --cpu

install the following in ComfyUI

ComfyUI-
		|-custom_nodes
			|-aspect_ratio_preset
			|-ComfyUI-Chatterbox
		|-models
			|-diffusion_models
				flux2_dev_fp8mixed.safetensors (from DMX)
			|-vae


once running drag and drop the workflows into the gui
