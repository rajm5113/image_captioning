# Image Captioning AI Web App

This project is a simple web application that generates meaningful captions for your photos using an AI model. The app uses the BLIP image captioning model and provides an easy-to-use interface powered by Gradio.

## Features

- **Image Captioning:** Upload an image and receive an AI-generated caption.
- **User-Friendly Web Interface:** Built with [Gradio](https://gradio.app/).

## How It Works

- The app uses the [Salesforce BLIP Image Captioning Base](https://huggingface.co/Salesforce/blip-image-captioning-base) model from Hugging Face.
- When you upload an image, the model generates a descriptive caption for it.

## Usage

1. **Install Requirements**
    - Python 3.8 or higher
    - Install dependencies:
      ```
      pip install gradio transformers pillow
      ```

2. **Run the App**
    - Open `image_cap.ipynb` in Jupyter Notebook and run all cells.
    - Or, convert the notebook to a Python script and run:
      ```
      python image_cap.py
      ```
    - The Gradio interface will open in your browser.

3. **Upload an Image**
    - Use the web interface to upload your image.
    - View the generated caption.

## File Structure

- `image_cap.ipynb` — Main notebook containing all code.
- `README.md` — Project documentation.

## Credits

- [Salesforce BLIP Model](https://huggingface.co/Salesforce/blip-image-captioning-base)
- [Gradio](https://gradio.app/)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)

---

**Give meaningful names to your photos with AI!**