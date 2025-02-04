##AI Image Generator using Stable Diffusion

📌 Project Overview

This project explores AI-generated images using Stable Diffusion and ComfyUI. The model generates high-quality images based on text prompts, transforming descriptions into realistic artwork.

🖼️ Generated Images

The repository contains AI-generated images created using Stable Diffusion. Some examples include:

Ancient Indian Temple in a Forest

Lakeview Sunset

🔧 How It Works

Model Used: Stable Diffusion (v1-5-pruned-emaonly)

Process Overview:

Encode text prompt (e.g., "ancient Indian temple in a forest")

Apply noise reduction using the U-Net diffusion model

Decode latent images into final images

Save outputs

📥 How to Generate Your Own Images

If you want to create similar images using Stable Diffusion and ComfyUI:

Install ComfyUI (ComfyUI GitHub)

Download the Stable Diffusion model weights

Set up your environment:

git clone https://github.com/VaibhavT04/AI-Image-Generator-Diffusion-Model-and-ComfyUI.git
cd AI-Image-Generator-Diffusion-Model-and-ComfyUI

Load your model and run ComfyUI to start generating images

📌 Future Improvements

Higher Resolution: Enhance image quality using super-resolution techniques

Optimized Performance: Reduce computational cost for faster processing

AI Ethics: Address biases in AI-generated artwork
