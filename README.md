# 🖼️ Text-to-Image Generation using Stable Diffusion XL

A Generative AI project that converts **natural language text prompts into AI-generated images** using **Stable Diffusion XL (SDXL)** and Hugging Face.

## 🌟 Project Overview

Have you ever wondered how AI tools can create an image just from a few words?

I became curious about this after using **Meta AI on WhatsApp**, where I could type a prompt and instantly get an AI-generated image. I wanted to understand how this technology actually works, so I built my own **Text-to-Image Generation project**.

This project takes a text prompt as input and uses a pre-trained **Stable Diffusion XL** model to generate an image based on that description.

## ✨ Features

- 📝 Generate images from natural language prompts
- 🤖 Uses Stable Diffusion XL (SDXL)
- 🎨 Creates detailed AI-generated images
- 💬 Supports different types of text prompts
- ⚡ GPU-based inference for faster generation
- ☁️ Designed to run in Google Colab
- 🤗 Uses Hugging Face for model access

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **Hugging Face**
- **Diffusers**
- **Transformers**
- **Stable Diffusion XL**
- **PyTorch**
- **Accelerate**
- **Safetensors**

## 🔄 How It Works

```text
User Text Prompt
       ↓
Prompt Processing
       ↓
Stable Diffusion XL
       ↓
Image Generation
       ↓
AI Generated Image
```

For example:

```text
Input:
"A beautiful Pakistani mountain village surrounded by snow-covered mountains"

Output:
An AI-generated image based on the given description.
```

## 🚀 Getting Started

### 1. Open the Notebook

Open the `.ipynb` notebook in **Google Colab**.

### 2. Enable GPU

In Google Colab, go to:

**Runtime → Change runtime type → T4 GPU**

GPU is recommended for running Stable Diffusion XL efficiently.

### 3. Install Dependencies

Run the first cell of the notebook to install the required libraries.

### 4. Hugging Face Authentication

Create a Hugging Face access token with **Read** permission and add it to Google Colab Secrets.

Use:

```text
Name: HF_TOKEN
```

Keep your token private and never upload it directly to GitHub.

### 5. Run the Notebook

Run the cells from top to bottom.

Once the model is loaded, provide a text prompt and the model will generate an image.

## 📸 Example Prompts

You can experiment with prompts such as:

```text
A futuristic city at night with neon lights and flying cars
```

```text
A beautiful Pakistani mountain village surrounded by snow-covered mountains
```

```text
A peaceful sunset over a lake surrounded by mountains
```

The quality and style of the generated image depend heavily on the prompt.

## 📂 Project Structure

```text
Text-to-Image-Generation/
│
├── Text_to_image_reusebale.ipynb
└── README.md
```

## 🎯 Learning Outcomes

Through this project, I learned about:

- Generative AI
- Text-to-Image generation
- Diffusion models
- Stable Diffusion XL
- Hugging Face models
- Prompt engineering
- GPU-based model inference
- Running AI models in Google Colab

## 💡 Why I Built This

This project started with a simple question:

> **"How can a few words turn into an actual image?"**

Instead of just wondering about it, I decided to build it myself.

It was exciting to see something that once felt like magic actually work through code. 🤖✨

This is one of the steps in my journey of exploring **Artificial Intelligence and Generative AI**, and I hope to keep learning, experimenting, and building more projects.

## 🔮 Future Improvements

Some possible improvements for this project include:

- Adding a simple web interface
- Allowing users to download generated images
- Adding image-to-image generation
- Supporting different Stable Diffusion models
- Improving prompt controls
- Adding negative prompts and advanced generation settings

## 👩‍💻 Author

**Alisha Noor**

Aspiring AI/LLM Developer | Data Analyst | Prompt Engineering Enthusiast

---

⭐ If you find this project interesting, feel free to explore the notebook and experiment with your own prompts!
