👋 Hi, I'm Yanis Ghazi

Engineering Student · Data Science & AI · IMT Nord Europe

[LinkedIn](https://www.linkedin.com/in/yanis-ghazi213) · [Email](mailto:yanisghazi27@gmail.com)

I'm an engineering student in Data Science & AI at IMT Nord Europe, on an exchange semester at Hohai University (Nanjing) until January 2027. I love sport, football and basketball especially, and I like using computer vision and machine learning to understand it. Previously a data scientist intern at Ponticelli Frères, where I built an absence forecasting pipeline deployed on Azure.

Currently looking for a **6-month end-of-studies internship in machine learning / computer vision starting February–March 2027**, ideally in sports analytics or player tracking.

## 🛠️ Tech Stack

**Languages:** Python · SQL · Java

**Computer Vision:** PyTorch · OpenCV · Ultralytics YOLO · ByteTrack (supervision) · scikit-image

**Data & ML:** scikit-learn · XGBoost · CatBoost · pandas · NumPy · SciPy · statsmodels · Sentence-Transformers · ChromaDB

**Cloud & Infra:** Azure (Functions, Data Factory, Blob Storage) · Docker · Dagster · GitHub Actions · PostgreSQL · SQLite

**Visualization & Apps:** Streamlit · Gradio · Power BI · Matplotlib

**Human Languages:** 🇫🇷 French (native) · 🇬🇧 English (C1, TOEIC 945/990) · 🇩🇿 Arabic (academic) · 🇪🇸 Spanish (academic) · 🇨🇳 Chinese (HSK3)

## 🔭 Featured Projects

### ⚽ [Football Tracking & Tactical Analysis from Broadcast Video](https://github.com/yanis-ghazi/football-tracking-cv)

> Python · PyTorch · Ultralytics YOLO · OpenCV · ByteTrack

End-to-end pipeline on broadcast footage: player tracking (YOLOv8x + ByteTrack), team separation, a fine-tuned ball detector, and automatic per-frame pitch calibration from a 32-keypoint pose model with RANSAC (1.3 m mean reprojection error against 22 m for a fixed homography on a high-camera-motion clip). Includes a player re-identification model written in PyTorch, with a batch-hard triplet loss and labels taken from tracker IDs (rank-1 0.72 on 21 held-out tracks).

### 🔎 [RAG Scouting Tool: NBA & Premier League](https://github.com/yanis-ghazi/rag-scouting)

> Python · ChromaDB · Sentence-Transformers · Llama 3.3 70B · Gradio

Natural-language scouting over 1,047 players ("NBA point guard with 8+ assists and fewer than 3 turnovers"). An LLM turns the question into numeric filters, exact filtering handles the figures that embeddings can't compare reliably, and the answer is generated from the retrieved profiles. Built without LangChain, with a live demo on Hugging Face Spaces.

### 🧑‍🦱 Face Recognition: Handcrafted Features vs Deep Learning

> Python · scikit-learn · PyTorch · facenet-pytorch

Comparison of LBPH, Eigenfaces + SVM and FaceNet + SVM on AT&T and LFW (90.0%, 96.25% and 98.61% accuracy), with error analysis, ROC curves and t-SNE of the embeddings. Research project at IMT Nord Europe, written up as an IEEE-format report.

### 🏆 World Cup 2026 Prediction by Tournament Simulation

> Python · NumPy · SciPy · pandas

Elo ratings and a Dixon-Coles model estimated by maximum likelihood (about 460 parameters), converted into match probabilities and fed into a Monte-Carlo simulation (10,000 runs) of the 48-team tournament, including FIFA's 495-scenario table for the best third-placed teams. Backtested on the 2018 and 2022 World Cups with strict temporal separation (Brier score).

### 🏃 Text-to-Motion Retrieval

> PyTorch · Sentence-Transformers · Contrastive Learning (InfoNCE)

One-week hackathon: a BiGRU motion encoder aligned with a pre-trained sentence encoder through a symmetric InfoNCE loss, with discriminative learning rates, time-series augmentation, test-time augmentation and rank fusion across models, evaluated on Recall@10.

### 🎮 Steam Game Mechanics Ontology

> Python · scikit-learn · XGBoost · Sentence-Transformers · SQLite

Research project turning the noisy tags of more than 126,000 Steam games into a structured taxonomy: association rules (FP-Growth), community detection (Louvain), semantic analysis with embeddings, and multi-label stacking classification, across 8 documented phases with a Streamlit dashboard.


## 🌟 Interests

🏀 Basketball (R2 level) · ⚽ Football (playing, following and analysing matches) · 📹 Computer vision · 📊 Probabilistic modelling of sport
