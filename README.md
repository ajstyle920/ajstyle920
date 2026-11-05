<h1 align="center">Hi, I'm Md Altaf Jawed 👋</h1>
<h3 align="center">BS in Data Science and Applications @ IIT Madras<br/>Building end-to-end AI systems, from trained models to production apps</h3>

<p align="center">
  <img src="https://img.shields.io/badge/IIT%20Madras-BS%20Data%20Science%20%26%20Applications-8B0000?style=flat-square" />
  <img src="https://img.shields.io/badge/Internships-2×%20IIIT%20Hyderabad-1f6feb?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-ML%20%7C%20CV%20%7C%20GenAI%20%7C%20LLMs-success?style=flat-square" />
</p>

---

## 🧑‍💻 About Me

- 🎓 Pursuing a **BS in Data Science and Applications** at **IIT Madras**
- 🏢 Completed **two internships at IIIT Hyderabad**, in **Computer Vision** and **Generative AI**
- 🧠 Experienced across the stack: **classical ML, deep learning, computer vision, speech, NLP and LLM fine-tuning**
- 🚀 I like shipping ML as **real, usable products**: live apps, REST APIs and databases, not just notebooks
- 🌱 **Currently focused on:** production ML pipelines, serving models through APIs, **Generative AI, LLMs and RAG**

---

## ⭐ Featured Projects

### 📸 [SnapClass: AI-Powered Classroom Attendance](https://github.com/ajstyle920/snapclass-major-project) · [**Live Demo**](https://snapclass-proj.streamlit.app)
Takes attendance for an entire class from **a single photo** or **a short voice recording**, in seconds.
- **Face pipeline:** dlib detection and alignment → **128-D ResNet embeddings** → **linear SVM** + Euclidean distance check for **open-set recognition** (unknown faces are rejected)
- **Voice pipeline:** silence-based segmentation → **256-D Resemblyzer speaker embeddings** → cosine-similarity matching
- **FaceID login** for students, **QR-code enrollment** and a teacher review step before anything is saved
- Stores **only embeddings, never raw photos or audio**, for privacy

`Streamlit` `Supabase (PostgreSQL)` `dlib` `scikit-learn` `Resemblyzer` `librosa` `bcrypt`

### 📝 [T5 Text Summarizer](https://github.com/ajstyle920/T5-Text-Summarizer)
Abstractive text summarization app powered by a **fine-tuned T5 transformer**, served through a **FastAPI** REST API with a browser UI. Uses beam-search decoding and runs on CPU, CUDA or Apple Silicon.

`PyTorch` `Hugging Face Transformers` `FastAPI` `NLP`

### 🧠 [Minor AI Projects](https://github.com/ajstyle920/minor-ai-projects)
Five end-to-end ML and DL projects, each documented with results and insights:

| Project | What it does | Highlight |
|---------|--------------|-----------|
| 🖼️ CNN CIFAR-10 Classification | CNN from scratch in PyTorch for 10-class image classification | **74.8%** test accuracy |
| 💳 CreditWise Loan Approval | Logistic Regression vs Naive Bayes vs KNN, with precision/recall trade-off analysis | **87%** accuracy |
| ⚡ ANN Power Plant Energy | PyTorch ANN regression benchmarked against SVR and Random Forest | **R² = 0.934** |
| 🛒 SmartCart Segmentation | PCA + K-Means customer segmentation with marketing profiles | **4** customer segments |
| 🎬 RNN IMDB Sentiment | Recurrent neural network for movie-review sentiment | Sequence modeling on text |

---

## 🏢 Internship Experience

### 🎨 [Generative AI Internship, IIIT Hyderabad](https://github.com/ajstyle920/Generative-AI-Vision-Internship-IIITH)
- **LLM fine-tuning:** fine-tuned **Qwen 2.5** for logistics-domain instruction following using **LoRA/PEFT, 4-bit quantization and Unsloth**, with supervised fine-tuning via **Hugging Face TRL `SFTTrainer`**, then evaluated on unseen logistics scenarios
- **Diffusion image generation:** built node-based **ComfyUI** workflows (prompt conditioning, sampling, latent processing, VAE decoding) with **SDXL Turbo**

`LLMs` `LoRA / PEFT` `Unsloth` `Hugging Face TRL` `Diffusion Models` `ComfyUI`

### 👁️ [Computer Vision Internship, IIIT Hyderabad](https://github.com/ajstyle920/cv-internship)
- **Video processing** with ffmpeg and yt-dlp: frame extraction and reconstruction
- **Object detection** on images with **YOLO**
- **Image segmentation** with **YOLOv8**, evaluated with performance metrics
- **YOLO dataset structure** and YAML training configuration

`YOLOv8 (Ultralytics)` `OpenCV` `ffmpeg`

---

## 📚 Coursework

- [**FMML Projects & Labs**](https://github.com/ajstyle920/FMML_Project_and_Labs): labs and projects from the Foundations of Modern Machine Learning course

---

## 🛠️ Tech Stack

**Languages & Data**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

**Machine Learning & Deep Learning**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge" />
</p>

**Computer Vision & Speech**
<p>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logoColor=black" />
  <img src="https://img.shields.io/badge/dlib-008000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/librosa-4D4D4D?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white" />
</p>

**Generative AI & LLMs**
<p>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/LoRA%20%2F%20PEFT-6E40C9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Unsloth-1A1A1A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ComfyUI-2F2F2F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stable%20Diffusion-8A2BE2?style=for-the-badge" />
</p>

**Deployment & Tools**
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</p>

---

## 🎯 What I Work On

| Area | Experience |
|------|------------|
| **Classical ML** | Classification, regression, clustering, feature engineering, model evaluation |
| **Deep Learning** | ANNs, CNNs and RNNs built from scratch in PyTorch |
| **Computer Vision** | Face recognition, object detection and segmentation (YOLOv8), video processing |
| **Speech** | Speaker recognition with voice embeddings |
| **NLP & LLMs** | Sentiment analysis, transformer summarization, LoRA fine-tuning of Qwen 2.5 |
| **Generative AI** | Diffusion-based image generation with ComfyUI and SDXL Turbo |
| **Deployment** | FastAPI REST APIs, Streamlit apps, Supabase/PostgreSQL backends |

---

## 🌱 Currently Exploring

- ⚙️ **Production ML pipelines:** building reproducible pipelines from training to serving
- 🔌 **Model serving:** deploying models behind scalable APIs
- 🤖 **LLMs & RAG:** retrieval-augmented generation, embeddings and vector search
- 🎨 **Generative AI:** diffusion models and LLM fine-tuning

---

## 📫 Connect With Me

<p>
  <a href="https://github.com/ajstyle920"><img src="https://img.shields.io/badge/GitHub-ajstyle920-181717?style=for-the-badge&logo=github" /></a>
  <a href="https://snapclass-proj.streamlit.app"><img src="https://img.shields.io/badge/Live%20Demo-SnapClass-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" /></a>
  <!-- Add your LinkedIn: replace YOUR-LINKEDIN-ID and remove the comment markers -->
  <!-- <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-ID"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" /></a> -->
</p>

<p align="center"><i>Always learning, always building. ⭐ Feel free to explore my repositories!</i></p>
