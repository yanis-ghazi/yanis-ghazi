<h1 align="center">😄 Hi there, I'm Yanis</h1>

<p align="center"><b>Engineering Student · Data Science &amp; AI · IMT Nord Europe</b></p>

<p align="center">
  <a href="https://www.linkedin.com/in/yanis-ghazi213"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:yanisghazi27@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

I'm an engineering student in **Data Science & Artificial Intelligence** at **IMT Nord Europe**, currently on an exchange semester at **Hohai University** (Nanjing) until January 2027. I love sport, football and basketball especially, and I like using computer vision and machine learning to understand it. Previously a data scientist intern at Ponticelli Frères, where I built an absence forecasting pipeline deployed on Azure.

Currently looking for a **6-month end-of-studies internship in machine learning / computer vision starting February–March 2027**, ideally in sports analytics or player tracking.

---

## 🛠️ Tech Stack

#### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-5C7C99?style=flat-square) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

#### Computer Vision

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![Ultralytics YOLO](https://img.shields.io/badge/Ultralytics%20YOLO-111F68?style=flat-square) ![ByteTrack](https://img.shields.io/badge/ByteTrack-555555?style=flat-square) ![scikit-image](https://img.shields.io/badge/scikit--image-4C8CBF?style=flat-square)

#### Data & ML

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square) ![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black&labelColor=FFCC00) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![statsmodels](https://img.shields.io/badge/statsmodels-4A6FA5?style=flat-square) ![Sentence-Transformers](https://img.shields.io/badge/Sentence--Transformers-6B4FBB?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-E8590C?style=flat-square)

#### Cloud & Infra

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

#### Visualization & Apps

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white)

**Human Languages** 🇫🇷 French (Native) · 🇬🇧 English (C1, TOEIC 945/990) · 🇸🇦 Arabic (academic) · 🇪🇸 Spanish (academic) · 🇨🇳 Chinese (HSK3)

---

## 🔭 Featured Projects

### ⚽ [Football Tracking & Tactical Analysis from Broadcast Video](https://github.com/yanis-ghazi/football-tracking-cv)

> Python · PyTorch · Ultralytics YOLO · OpenCV · ByteTrack

End-to-end pipeline on broadcast footage: player tracking (YOLOv8x + ByteTrack), team separation, a fine-tuned ball detector, and automatic per-frame pitch calibration from a 32-keypoint pose model with RANSAC (1.3 m mean reprojection error against 22 m for a fixed homography on a high-camera-motion clip). Includes a player re-identification model written in PyTorch, with a batch-hard triplet loss and labels taken from tracker IDs (rank-1 0.72 on 21 held-out tracks).

### 🔎 [RAG Scouting Tool: NBA & Premier League](https://github.com/yanis-ghazi/rag-scouting)

> Python · ChromaDB · Sentence-Transformers · Llama 3.3 70B · Gradio

Natural-language scouting over 1,047 players ("NBA point guard with 8+ assists and fewer than 3 turnovers"). An LLM turns the question into numeric filters, exact filtering handles the figures that embeddings can't compare reliably, and the answer is generated from the retrieved profiles. Built without LangChain, with a live demo on Hugging Face Spaces.

### 🧑 Face Recognition: Handcrafted Features vs Deep Learning

> Python · Scikit-learn · PyTorch · facenet-pytorch

Comparison of LBPH, Eigenfaces + SVM and FaceNet + SVM on AT&T and LFW (90.0%, 96.25% and 98.61% accuracy), with error analysis, ROC curves and t-SNE of the embeddings. Written up as an IEEE-format report.

### 🎮 Steam Game Mechanics Ontology

> Python · Scikit-learn · XGBoost · Sentence-Transformers · SQLite

Research project turning the noisy tags of more than 126,000 Steam games into a structured taxonomy: association rules (FP-Growth), community detection (Louvain), semantic analysis with embeddings, and multi-label stacking classification, across 8 documented phases with a Streamlit dashboard.


### 🏆 World Cup 2026 Prediction by Tournament Simulation

> Python · NumPy · SciPy · Pandas

Elo ratings and a Dixon-Coles model estimated by maximum likelihood (about 460 parameters), converted into match probabilities and fed into a Monte-Carlo simulation (10,000 runs) of the 48-team tournament, including FIFA's 495-scenario table for the best third-placed teams. Backtested on the 2018 and 2022 World Cups with strict temporal separation (Brier score).

### 🏃 Text-to-Motion Retrieval

> PyTorch · Sentence-Transformers · Contrastive Learning (InfoNCE)

One-week hackathon: a BiGRU motion encoder aligned with a pre-trained sentence encoder through a symmetric InfoNCE loss, with discriminative learning rates, time-series augmentation, test-time augmentation and rank fusion across models, evaluated on Recall@10.



---

## 🌟 Interests

🏀 Basketball (R2 level) · ⚽ Football (playing, following and analysing matches) · 📹 Computer vision · 📊 Probabilistic modelling of sport
