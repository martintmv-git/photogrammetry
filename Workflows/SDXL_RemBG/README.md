# SDXL RemBG (IpAdapter_plus) Workflow Setup Guide

![SDXL RemBG](https://i.ibb.co/54mcdQF/Screenshot-2024-06-01-at-18-52-22.png)

## Nodes Installation

To ensure you have the correct environment setup, you'll need to install the following nodes. These nodes extend the functionality of ComfyUI, allowing for a more robust and versatile workflow:

- **ComfyUI Manager**: A tool for managing and importing workflows within ComfyUI.

  - [ComfyUI Manager](https://github.com/ltdrdata/ComfyUI-Manager)
- **IPAdapter Plus v2**: Enhances the workflow with advanced image processing capabilities.

  - [IPAdapter Plus v2](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
- **Segment Anything / Grounding Dino**: This node allows for the isolation and manipulation of subjects within images.

  - [Segment Anything / Grounding Dino GitHub](https://github.com/storyicon/comfyui_segment_anything)

## Models Installation

For this workflow to function correctly, you'll need to download and install specific models:

- **RealVis XL (SDXL Lightning)**: Used for realistic image generation with SDXL Lightning.

  - [Download RealVis XL](https://civitai.com/models/139562/realvisxl-v40?modelVersionId=361593)
- **SDXL LoRA (4 steps LoRA recommended)**: Optimizes the Stable Diffusion model for fewer steps without compromising quality.

  - [Download SDXL LoRA](https://huggingface.co/ByteDance/SDXL-Lightning)
- **ControlNet SDXL**: Provides additional control over the generated images.

  - [Download ControlNet SDXL](https://huggingface.co/lllyasviel/sd_control_collection)
- **Segment Anything / Grounding Dino models**: Essential for the Segment Anything functionality.

  - [Find Segment Anything Models Here](https://github.com/storyicon/comfyui_segment_anything)

### IPAdapter Models

If your IPAdapter v2 does not come with preinstalled models or you prefer to use custom ones, download the following:

- **IPAdapter Plus XL model**: Place it into your `\models\ipadapter` folder.

  - [Download IPAdapter Plus XL](https://huggingface.co/h94/IP-Adapter/resolve/main/sdxl_models/ip-adapter-plus_sdxl_vit-h.safetensors)
- **IPAdapter Plus 1.5 model**: Also place into `\models\ipadapter`.

  - [Download IPAdapter Plus 1.5](https://huggingface.co/h94/IP-Adapter/resolve/main/models/ip-adapter-plus_sd15.safetensors)
- **CLIPVision ViT-H model**: Compatible with IPAdapter Plus. Place it into `\models\clip_vision`.

  - [Download CLIPVision ViT-H](https://huggingface.co/h94/IP-Adapter/resolve/main/models/image_encoder/model.safetensors)
