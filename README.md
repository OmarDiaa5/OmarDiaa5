# Hi, I'm Omar Diaa-Eldeen Fawzy! 👋

### 🚀 Machine Learning & Computer Vision Engineer | AI Practitioner | Leader

I am a passionate **Machine Learning & Computer Vision Engineer** studying at the **Faculty of Computers and Information, Benha National University (BNU)**. My work spans deep spatial-temporal perception (such as drone-based tracking and real-time driver behavior monitoring), natural language processing (explainable transformers and RAG architectures), and predictive modeling.

Alongside engineering, I serve as the **Vice President of the BNU Computer Science Student Union**, leading a community of over 1,000 students across 7 committees, and work as the **Media Lead & Innovation Ambassador** for BNU's Innovation & Entrepreneurship Sector.

---

## 🛠️ Technical Arsenal

<p align="left">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-for-the-badge&logo=react&logoColor=61DAFB" />
  
  <br/>
  
  <!-- Machine Learning & Deep Learning -->
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-17B890?style=flat-for-the-badge&logo=xgboost&logoColor=white" />
  
  <br/>
  
  <!-- Computer Vision -->
  <img src="https://img.shields.io/badge/YOLO%20(v11%20/%2011s)-00C4CC?style=flat-for-the-badge&logo=yolo&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/Vision%20Transformers-4B32C3?style=flat-for-the-badge" />
  
  <br/>
  
  <!-- NLP & GenAI -->
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/RAG%20(FAISS)-326CE5?style=flat-for-the-badge" />
  <img src="https://img.shields.io/badge/Prompt%20Engineering-4A154B?style=flat-for-the-badge" />
  <img src="https://img.shields.io/badge/Groq%20%2F%20Llama%203-010101?style=flat-for-the-badge" />
  
  <br/>
  
  <!-- MLOps & Tools -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-012A4A?style=flat-for-the-badge&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20AI-0089D6?style=flat-for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Gradio-FF9E0F?style=flat-for-the-badge" />
</p>

---

## 🚀 Selected Engineering Feats

### 🛰️ custom OSTrackSmall: Efficient Aerial Single-Object Tracker
* **Repo:** [aic-2026-tracker](https://github.com/OmarDiaa5/aic-2026-tracker) | **Model Hosted:** [omardiaa05/a-eye-model](https://kaggle.com/models/omardiaa05/a-eye-model)
* **Under the Hood:** Designed and trained a self-contained custom Vision Transformer (ViT-Small) tracker using a **Mixed Attention Module (MAM)** backbone, **CornerHead** localization (sub-pixel offset regression), and **ConfidenceHead** absence detection. Deployed via Docker with a cross-check score-map fallback and EMA template updates to handle severe occlusions.
* **Results:** Submitted to the prestigious MTC-AIC4 National AI Competition, successfully meeting all 4 hardware/efficiency constraints:
  - **Computation:** **12.5 GFLOPs** (58% below the 30 GFLOPs limit)
  - **Latency:** **~15-22ms** on Tesla T4 GPU (well within the 30ms limit)
  - **Size & Parameters:** **46.45M parameters** (under 50M limit) | **88.75MB model file** (under 500MB limit)

### 🚗 YOLO11s Real-Time Driver Monitoring System
* **Repo:** [driver-drowsiness-detection](https://github.com/OmarDiaa5/driver-drowsiness-detection)
* **Under the Hood:** Co-engineered an in-cabin behavior classifier targeting 6 states (SafeDriving, Distracted, SleepyDriving, etc.) over **14,855 images**. Curated the data pipeline using stratified splitting, resolved severe class imbalances through offline synthetic augmentations (Albumentations), and fine-tuned YOLO11s on Tesla T4.
* **Results:**
  - Achieved a stellar **mAP50 of 98.9%** and **F1-score of 97.7%** across all 6 behavioral classes.
  - Optimized inference latency to a blazing **~5.6ms per frame** on Tesla T4, ready for production onboard deployment.

### 🚁 Autonomous Drone: Detection, Tracking & RL Control (DEPI Capstone)
* **Under the Hood:** Developed an aerial multi-object detection and tracking pipeline combined with active Reinforcement Learning (RL) drone navigation (currently in active development). Merged and balanced VisDrone, Aeroscapes, and UAVDT datasets across 10 aerial classes, fine-tuning YOLOv11 under a multi-stage schedule. Built a modular OOP-based Python simulation as an testing sandbox.

### 🎬 Cinematic Sentiment AI (Sentiment & Explainable RAG)
* **Repo:** [AI-Film-Reviews-Sentiment-Analysis](https://github.com/OmarDiaa5/AI-Film-Reviews-Sentiment-Analysis)
* **Under the Hood:** Co-developed a massive sentiment benchmarking pipeline across **150,000+ total reviews** (IMDB, Letterboxd, Metacritic) spanning classical ML, Deep Learning (GloVe Bi-LSTMs), and Transformer architectures. Built a custom RAG explanation layer (FAISS + sentence-transformers) powered by Groq Llama 3 agents for dynamic tool selection and classification explanations.
* **Results:** Fine-tuned **RoBERTa achieved a premier 95.75% test accuracy**, integrated seamlessly into an interactive Gradio web application.

### ⚕️ Medicine Recommendation System
* **Under the Hood:** Engineered a multi-class clinical disease predictor (41 classes) using symptom-severity weighting (replacing static binary flags with a 1–7 scale) to inject clinical domain logic. Built a custom Voting Ensemble (Logistic Regression, Random Forest, XGBoost).
* **Results:** Achieved **100% test accuracy and 1.0 Macro F1** (validated via Stratified 5-Fold Cross-Validation), outputting a full lifestyle and pharmaceutical report via Gradio.

### 📈 Telecom Customer Churn Pipeline (IBM Telco)
* **Under the Hood:** Created an end-to-end classification and clustering pipeline. Deployed K-Means clustering to discover hidden segments, revealing that new customers (<12 months) churn at **42%** (3x the loyal rate). Applied SMOTE to resolve class imbalance, training an XGBoost model optimized for business-impact Recall.
* **Results:** Boosted XGBoost recall from **0.56 to 0.91** (63% relative improvement), saving an estimated 191 customers per 1,409 evaluated.

### 🎥 Smart CCTV Analytics (Clash of Codes)
* **Under the Hood:** Co-engineered a real-time CCTV analytics pipeline featuring YOLO detection, CV tracking, ROI filtering, and zone-based analytics under an intense **5-hour time constraint** with only 2 training videos.
* **Results:** Secured **2nd Place Overall** representing BNU in the Computer Vision track, outcompeting 5 universities.

---

## 👑 Leadership & Community Engagement

* **Vice President — CS Student Union, BNU (Oct 2025 – Present):** Elected to represent the **1,000+ CS student body**. Manage strategic direction and operations across **7 specialized committees**. Awarded a **Certificate of Honor** by the Faculty Dean for outstanding leadership and served as the official keynote speaker at Freshman Orientation Day.
* **Innovation Ambassador & Media Lead — BNU Innovation & Entrepreneurship Sector:** Directed and produced cinematic documentary films highlighting BNU’s industrial partnerships and regional expansions, screened at the main university theater. Honored by the University President and Vice President for high-impact visual storytelling. Represented BNU at AUC (American University in Cairo) and Bibliotheca Alexandrina.
* **Head of Multimedia Committee — Enactus BNU:** Built and led the creative team managing visual identity, promotional branding, and campaigns for local social entrepreneurship projects.
* **Media Lead & Video Editor — GDG (Google Developer Groups) on Campus BNU:** Produced promotional visual content and video productions, driving event engagement and cross-functional student outreach.

---

## 📜 Certifications & Achievements

* **Huawei Certified ICT Associate — AI V4.0 (NTI & Huawei Academy, Aug 2025):** Scored an outstanding **98%** on the international exam covering machine learning, CNNs, RNNs, Transformers, and deployment business processes.
* **NVIDIA Deep Learning Institute — Building LLM Applications with Prompt Engineering (ITI & NVIDIA, 2026):** Certified in LLM application design, structured prompt engineering, and RAG pipelines.
* **Digital Egypt Pioneers Initiative (DEPI) — Microsoft Machine Learning Engineer Track (Nov 2025 – Present):** Pursuing intensive training in Azure AI engineering, advanced NLP, computer vision, and MLOps tools (MLflow & Hugging Face).
* **IBM Data Science Coursework (Coursera):** Completed 8 of 12 courses (123+ hours) focusing on SQL, Python libraries, data wrangling, and predictive machine learning.
* **Front-End Web Development Diploma (Route Academy, Issued Feb 2025):** Core curriculum in React, JavaScript (ES6+), and responsive CSS.

---

## 🤝 Let's Connect!

<p align="left">
  <a href="https://linkedin.com/in/omardiaalink"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:OmarDiaa177@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/OmarDiaa5"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

*Feel free to explore my repositories or reach out to discuss Computer Vision, Reinforcement Learning, Generative AI, or student leadership collaborations!*
