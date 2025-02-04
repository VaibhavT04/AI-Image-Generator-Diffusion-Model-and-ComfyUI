# AI Image Generator using Stable Diffusion

## 📌 Project Overview

This project explores AI-generated images using Stable Diffusion and ComfyUI. The model generates high-quality images based on text prompts, transforming descriptions into realistic artwork.

## 🖼️ Generated Images

The repository contains AI-generated images created using Stable Diffusion. Some examples include:

Ancient Indian Temple in a Forest

Lakeview Sunset

## 🚀 Usage
1. Open ComfyUI and load the provided workflow.
2. Set your text prompt and parameters.
3. Run the model to generate images.
4. Save the generated images from the output folder.

## 🧠 Working of the Project
The AI Image Generator is built on **Stable Diffusion**, a powerful deep-learning model for generating high-quality images from text descriptions. It leverages a diffusion process to iteratively refine images from random noise.

### 🔍 U-Net Architecture in Stable Diffusion
The **U-Net architecture** is a core component of Stable Diffusion, playing a crucial role in denoising images during the diffusion process. Here's how it works:
- The model starts with an image filled with noise and progressively refines it to match the input text prompt.
- U-Net consists of an **encoder-decoder structure**:
  - **Encoder:** Captures important image features through convolutional layers.
  - **Bottleneck:** Processes feature maps and applies transformations to remove noise.
  - **Decoder:** Reconstructs a clean, meaningful image from refined features.
- Skip connections help retain fine details by passing information directly from encoder to decoder layers.

This iterative refinement process ensures the generation of high-quality, realistic images while maintaining coherence with the given text prompt.

## 🖼️ Example Outputs
### ✨ Prompt: "Ancient Indian temple in the middle of a forest"

### 🌅 Prompt: "Lakeview sunset with vibrant colors"

Output images in repo above.

## 🔮 Future Improvements
- Enhancing image resolution and coherence.
- Optimizing computational efficiency.
- Addressing AI biases and ethical concerns in AI-generated art.

## 📜 License
This project is for educational and research purposes.

## 👤 Author
**Vaibhav Tatkare** 
<p align="center">
  <a href="https://github.com/VaibhavT04">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/white">
      <img alt="GitHub" title="GitHub" height="48" width="48" src="https://cdn.simpleicons.org/github"></picture></a>
  <a href="https://www.linkedin.com/in/vaibhav-tatkare-code/">
    <img alt="LinkedIn" title="LinkedIn" height="48" width="48" src="https://cdn.simpleicons.org/linkedin"></a>
</p>
