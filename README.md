# Game Illustration Creation System Based on Stable Diffusion

This project is a **customized fork** of **[Stable Diffusion WebUI by AUTOMATIC1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui)**, specifically designed for creating **game illustrations** through an easy-to-use web interface. The system allows users to generate detailed visuals from text prompts and refine them iteratively using **inpainting**.

We have simplified the original repository by **removing unnecessary features** and **customizing the UI** to better suit game illustrators.

---

## Features
- **Text-to-Image Generation**: Create detailed game illustrations from text prompts.
- **Inpainting Tool**: Modify specific areas of images to refine illustrations.
- **Simplified UI**: Adjusted layout to improve usability for game illustrators.
- **Reduced Functionality**: Removed advanced features such as Hypernetwork training, LoRA customization, and batch processing.

---

## Create a virtual environment:
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate  # Windows

## Install dependencies:
pip install -r requirements.txt


## Run the web UI:
python launch.py
