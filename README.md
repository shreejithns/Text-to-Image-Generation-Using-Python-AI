# 🎨 AI Text-to-Image Generator – Offline Python App with Realistic Vision V6.0

Transform any text prompt into a photorealistic image using the power of **Stable Diffusion** and **Realistic Vision V6.0 (v51 Hyper VAE)** – completely offline and free of paid APIs.

> Build your own AI-powered creativity engine in Python, with both GUI and web support.

---

## 🚀 Project Highlights

- ✅ Text-to-Image and Image-to-Image generation
- ✅ Uses **Realistic Vision V6.0 (v51 Hyper VAE)** for ultra-detailed rendering
- ✅ 100% Offline – No API keys or internet required after setup
- ✅ Dual-mode: Web Interface (Flask) + Desktop GUI (Tkinter)
- ✅ Generates **512x512 PNG** images with high realism
- ✅ Includes progress bar, output preview, and save support

---

## ⚠️ Disclaimer: Unfiltered AI Model

This project disables the default `safety_checker`.

- It may generate **NSFW**, violent, or biased outputs depending on your prompt.
- **For research & educational use only.**
- Always **review output before sharing**.

---

## 📷 What is Realistic Vision?

**Realistic Vision** is a leading Stable Diffusion model known for:

- 🤖 Hyper-realistic facial rendering
- 🧥 High detail in textures, lighting, and clothing
- 🖼️ Artistic + photographic flexibility

We're using:

- 📦 `realisticVisionV60B1_v51HyperVAE.safetensors`

This version includes **Hyper VAE** for sharper and more accurate image generation.

---

## 🛠️ Tech Stack

| Component    | Tech Used         |
|--------------|-------------------|
| Language     | Python 3.10.x     |
| AI Model     | Realistic Vision V6.0 (Stable Diffusion) |
| Interface    | Flask (Web), Tkinter (Desktop GUI) |
| Image Tools  | PIL (Pillow), OpenCV |
| Model Format | .safetensors + ONNX Runtime |
| Dependencies | Diffusers, Transformers, Torch |

---

## 📦 Prerequisites

- OS: Windows / Linux / macOS
- Python: **3.10.x**
- **8GB RAM** minimum (16GB+ recommended)
- A **CUDA-capable GPU** (optional, but speeds up generation)
- Git (optional for cloning)

---

## 🧑‍💻 Installation Steps

### 🔹 Step 1: Install Python 3.10

Download and install Python 3.10 from:

👉 https://www.python.org/downloads/release/python-3100/

Make sure to check ✅ “Add Python to PATH” during setup.

---

### 🔹 Step 2: Install Dependencies

Clone the repo and install requirements:

```bash
git clone https://github.com/yourusername/text-to-image-generator.git
cd text-to-image-generator
pip install -r requirements.txt
```

---

### 🔹 Step 3: Download the Model

Download manually from [CivitAI](https://civitai.com/models/4201/realistic-vision-v60):

- File: `realisticVisionV60B1_v51HyperVAE.safetensors`

Place it in the **project root directory** (same folder as `app.py` or `gui.py`).

---

### 🔹 Step 4: Run the App

#### Option 1: Web Interface

```bash
python app.py
```

Open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

#### Option 2: Desktop GUI

```bash
python gui.py
```

---

## 📁 Folder Structure

```
├── app.py                 # Flask web app
├── gui.py                 # Tkinter GUI
├── model/                 # Place your .safetensors model here
├── static/                # Web assets
├── templates/             # HTML templates
├── outputs/               # Generated image output
├── requirements.txt
```

---

## 📸 Output Samples

Coming soon...

---

## 📦 Optional EXE Version (No Setup Needed)

- Double-click EXE to run the app offline (4.8 GB)
- No internet, no Python installation required
- Supports full text-to-image generation

> 🔗 Link to EXE (to be added)

---

## 📜 LICENSE

This project is released under the **MIT License**.

---

## 🙋‍♂️ AUTHOR

Built with ❤️ by **Shreejith N S**  
🔗 [linkedin.com/in/shreejithnsdev](https://linkedin.com/in/shreejithnsdev)  
💻 [github.com/shreejithns](https://github.com/shreejithns)

---

## 🤝 CONTRIBUTIONS

Feel free to fork, raise issues, or submit PRs to improve this project!
