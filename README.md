# 🛠️ AIML Club OCT Workshops Hub

> Interactive Jupyter notebooks, lecture slides, datasets, and practical coding exercises from hands-on technical bootcamps conducted by the **AI & Machine Learning Club – Oriental College of Technology, Bhopal**.

[![AIML Club OCT](https://img.shields.io/badge/AIML_Club-OCT_Bhopal-0052CC?style=flat-square)](https://aimlcluboct.in)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](./LICENSE)
[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](#running-notebooks-in-the-cloud)

---

## Overview

The **Workshops** repository houses the code, slide decks, datasets, and interactive notebooks developed for AIML Club OCT's live coding sessions, weekend bootcamps, and technical workshops.

Unlike abstract lecture slides, every workshop folder provides **reproducible code** and **self-contained environments** that attendees can run locally or directly in their browsers using Google Colab.

---

## 🧭 Workshop Catalog by Level

Explore workshop materials based on your experience:

- 🟢 [**Beginner Workshops (`beginner/`)**](./beginner/):
  - **1. Python for AI & Vectorized Computing** ([`01_python_numpy_basics.ipynb`](./beginner/notebooks/01_python_numpy_basics.ipynb)) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AIMLCLUBOCT/Workshops/blob/main/beginner/notebooks/01_python_numpy_basics.ipynb)
  - **2. Exploratory Data Analysis & Visual Storytelling** ([`02_exploratory_data_analysis.ipynb`](./beginner/notebooks/02_exploratory_data_analysis.ipynb)) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AIMLCLUBOCT/Workshops/blob/main/beginner/notebooks/02_exploratory_data_analysis.ipynb)
  - **3. Intro to Machine Learning: From Zero to Classification** ([`03_intro_machine_learning.ipynb`](./beginner/notebooks/03_intro_machine_learning.ipynb)) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AIMLCLUBOCT/Workshops/blob/main/beginner/notebooks/03_intro_machine_learning.ipynb)
  - **4. NLP & Sentiment Analysis: Text Classification with Scikit-Learn** ([`04_nlp_sentiment_analysis.ipynb`](./beginner/notebooks/04_nlp_sentiment_analysis.ipynb)) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AIMLCLUBOCT/Workshops/blob/main/beginner/notebooks/04_nlp_sentiment_analysis.ipynb)
- 🟡 [**Intermediate Workshops (`intermediate/`)**](./intermediate/):
  - *Deep Learning Fundamentals with PyTorch*
  - *Real-Time Computer Vision & Object Detection with OpenCV and YOLO*
  - *Modern Natural Language Processing with Hugging Face*
- 🔴 [**Advanced Workshops (`advanced/`)**](./advanced/):
  - *Building Retrieval-Augmented Generation (RAG) Systems*
  - *Autonomous AI Agents with Tool-Calling & LangGraph*
  - *Deploying ML Models as Microservices with FastAPI & Docker*
- 🧩 [**Workshop Blueprint Template (`templates/`)**](./templates/):
  - Standard template for instructors and workshop leads.

---

## ☁️ Running Notebooks in the Cloud

You do not need a high-end GPU or complex local installations to get started!

1. Navigate to any notebook file (`.ipynb`) in this repository.
2. Replace `github.com` with `colab.research.google.com/github` in the URL, or click the **Open In Colab** badge provided in each workshop's README.
3. In Colab, select **Runtime > Change runtime type > T4 GPU** to access free hardware acceleration.

---

## 💻 Local Installation & Setup

If you prefer running workshops on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AIMLCLUBOCT/Workshops.git
   cd Workshops
   ```

2. **Create and activate a virtual environment:**
   ```bash
   # Windows PowerShell
   python -m venv .venv
   .venv\Scripts\Activate.ps1

   # Linux / macOS
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies and launch Jupyter:**
   ```bash
   pip install jupyterlab numpy pandas matplotlib scikit-learn torch
   jupyter lab
   ```

---

## 📋 Standard Workshop Structure

Every workshop directory follows this structure:

```text
Workshops/[level]/[workshop-name]/
├── README.md              # Workshop syllabus, prerequisites, and timeline
├── slides/                # Lecture slides (PDF format)
├── notebooks/
│   ├── 01_starter.ipynb   # Interactive student exercises with TODOs
│   └── 02_solution.ipynb  # Complete instructor reference solution
├── data/                  # Small sample datasets or synthetic generators
└── requirements.txt       # Exact dependencies needed for the session
```

---

## 🤝 Contributing Workshop Content

Are you leading a club workshop or proposing a hands-on session? Please review our [Contributing Guidelines](./CONTRIBUTING.md) and use the [Workshop Template](./templates/WORKSHOP_TEMPLATE.md).

---

## 🌐 Connect with the Community

- **Official Website:** [aimlcluboct.in](https://aimlcluboct.in)
- **Digital Hub & Socials:** [social.aimlcluboct.in](https://social.aimlcluboct.in)
- **Upcoming Workshops:** [aimlcluboct.in/events](https://aimlcluboct.in/events)
- 📸 **Workshop Moments & Photo Gallery:** [Google Drive Photo Archive](https://drive.google.com/drive/folders/1-_byssQsFS1pw02iDxyt40_n2CdCBaOk?usp=sharing)
- **Suggest a Workshop Topic:** [voice.aimlcluboct.in](https://voice.aimlcluboct.in)
- **Email:** [aimlcluboct@gmail.com](mailto:aimlcluboct@gmail.com)