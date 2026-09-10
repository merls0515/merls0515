
<div align="center">

# 👋 Hi, I'm Merlyn Victor

### 🎓 B.Tech CSE (Health Informatics) @ VIT | AI/ML Engineer | Data Scientist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/merlyn-victor-15391b2a6/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/merls0515)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:merlyntvictor@gmail.com)

*"Turning data into decisions, and algorithms into impact."*

</div>

---

## 🚀 About Me

I'm a passionate **AI/ML Engineer** and **Data Scientist** with a strong foundation in machine learning, deep learning, and data engineering. I specialize in building end-to-end AI solutions—from data ingestion and preprocessing to model deployment and visualization—with a focus on **healthcare**, **biomedical analytics**, and **decision-support systems**.

- 🔬 Building intelligent systems that solve real-world problems
- 📊 Transforming complex data into actionable insights
- 🏥 Passionate about AI applications in healthcare and biomedical research
- 🌱 Constantly learning and exploring cutting-edge AI technologies
- 💡 Strong believer in data-driven decision making

---

## 🛠️ Technical Arsenal

### **Languages & Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

### **AI/ML & Deep Learning**
- Machine Learning & Deep Learning (CNN, LSTM, Ensemble Methods)
- Predictive Modeling & Model Evaluation
- Natural Language Processing (NLP)
- Computer Vision & Pattern Recognition
- Statistical Analysis & Biomedical Signal Analysis

### **Data Engineering & Analytics**
- Data Pipelines & ETL Processes
- Data Cleaning, Preprocessing & Feature Engineering
- Exploratory Data Analysis (EDA)
- Database Design (MySQL, NoSQL, Firebase)
- REST APIs & Backend Development

### **Tools & Technologies**
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

**Visualization:** Matplotlib, Seaborn, Plotly  
**Other Tools:** MATLAB, WEKA, Haystack, Gradio, Excel

---

## 💼 Featured Projects


### 🩺 [Clinical Assessment Extraction Pipeline](https://github.com/merls0515/voice-to-clinical-assessment.git)

A FastAPI backend that turns a clinical session recording into a **structured, validated `FirstAssessment` JSON**.

**Pipeline:** WAV → Whisper → LangGraph → Gemini extraction → Normalization → Grounding verification → Confidence gate (≥ 0.70) → MongoDB

**Key ideas:**
- 🎙️ Local Whisper transcription
- 🕸️ Two-node LangGraph workflow (extract → verify)
- 🧬 Strict Pydantic schemas (`extra="forbid"`)
- 📏 Deterministic + LLM grounding checks
- 🚫 Fail-closed: rejects instead of silently guessing
- 💾 Separate parse/save workflow with MongoDB persistence

**Stack:** `Python` · `FastAPI` · `LangGraph` · `Gemini 2.5 Flash-Lite` · `Whisper` · `Pydantic v2` · `MongoDB`

### 🏥 [AI Clinical Discharge Summary Agent](https://github.com/merls0515/discharge-agent)

An agentic AI pipeline that converts **unstructured clinical notes into an evidence-backed clinical discharge summary** using structured extraction, validation, conflict detection, medication reconciliation, and Gemini-based generation.

**Pipeline:** Clinical Notes → Clinical Fact Extraction → Evidence Tracking → Conflict Detection → Medication Reconciliation → Missing Field Detection → Gemini Summary → Trace Log

**Key Features:**
- 📄 Extracts **diagnoses, medications, dates, allergies, pending results, and hospital course**
- 🔎 Tracks **source page numbers and supporting evidence** for extracted facts
- ⚠️ Detects and surfaces **conflicting clinical information**
- 💊 Performs **medication reconciliation** for added, stopped, and continued medications
- 🚫 Uses `MISSING` for unavailable information instead of making unsupported assumptions
- 🧾 Generates `trace.json` for **pipeline traceability and auditability**
- 🛡️ Handles extraction errors and LLM failures gracefully

**Tech Stack:** `Python` · `Pydantic` · `Gemini 2.5 Flash` · `Clinical NLP` · `Rule-Based Extraction` · `Agentic AI`


### 🔬 [BioEnquire – Biomedical Literature Chatbot](https://github.com/merls0515)
> *LLM-Powered Intelligent Biomedical Research Assistant*

- 🎯 Engineered an LLM-powered chatbot using **Haystack** and **Gradio** to retrieve and summarize PubMed literature
- 📚 Processes **35M+ articles** with **85% relevance accuracy**
- ⚡ Enables **10x faster** medical literature access for researchers
- 🧠 Integrated advanced NLP and semantic search for precise biomedical information retrieval

**Tech Stack:** `Python` `Haystack` `Gradio` `NLP` `LLM` `PubMed API`

---

### 🩺 [Breast Cancer Classification Using ML](https://github.com/merls0515)
> *Early Detection Through Ensemble Machine Learning*

- 🎯 Achieved **90.74% accuracy** in early breast cancer detection
- 🔍 Comprehensive comparative analysis of **SVM, Random Forest, and Neural Networks**
- 📊 Applied cross-validation and hyperparameter tuning for optimal performance
- 💡 Contributed to early cancer detection research through advanced feature engineering

**Tech Stack:** `Python` `Scikit-learn` `WEKA` `Ensemble Methods` `Cross-Validation`

---

### 📚 [RAG Chatbot – Agentic AI eBook](https://github.com/merls0515/agentic-ai-ebook-assistant.git)
> *Document-Grounded Conversational AI with Zero Hallucinations*

- 🏗️ Architected a sophisticated RAG-based agent using **LangGraph** and **Google Gemini**
- ✅ Ensures **100% document-grounded responses** from a 200+ page technical eBook
- ⚡ Optimized vector storage in **Pinecone** with **<300ms retrieval latency**
- 🔍 Implemented real-time confidence scoring and transparent context citation via **Streamlit**

**Tech Stack:** `LangGraph` `Google Gemini` `Pinecone` `HuggingFace` `Streamlit` `RAG`

---

### ❤️ [Heart Disease Survival Analysis Dashboard](https://github.com/merls0515)
> *Interactive Healthcare Analytics & Predictive Insights*

- 📊 Built interactive **Power BI dashboard** with advanced DAX calculations
- 📈 Analyzed survival trends by age, gender, and comorbidities
- ⚡ Improved analytics reporting efficiency by **60%**
- 🏥 Deployed real-time data visualization for clinical outcome assessment

**Tech Stack:** `Power BI` `DAX` `Statistical Modeling` `Data Visualization`

---

## 🏆 Achievements & Recognition

📝 **IEEE Research Publication (2024)**  
Co-authored *"Catalyzing Epilepsy Detection"* using LSTM networks and EEG signal analysis, contributing to neurological disorder detection technology.

---

## 📜 Certifications

- ✅ **AWS Certified Data Engineer – Associate** – AWS
- ✅ **Applied Machine Learning in Python** – Coursera
- ✅ **MATLAB Onramp & Simulink Onramp** – MathWorks
- ✅ **Fundamentals in AI & Machine Learning** – Vityarthi
- ✅ **Python Programming Certification** – Vityarthi
- ✅ **Computer Vision Fundamentals** – Vityarthi
- ✅ **Blockchain Fundamentals & Developer** – IBM
- ✅ **Generative AI using IBM Watsonx** – IBM

---

## 📊 GitHub Stats

<div align="center">

<!-- ─── TOP STATS ROW ─── -->
<a href="https://github.com/merls0515">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=merls0515&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github&show=reviews,discussions_started,prs_merged,prs_merged_percentage" alt="Merlyn's GitHub Stats" />
</a>
<a href="https://github.com/merls0515">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=merls0515&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&count_private=true" alt="Top Languages" />
</a>

<!-- ─── STREAK STATS ─── -->
<a href="https://github.com/merls0515">
  <img width="70%" src="https://streak-stats.demolab.com?user=merls0515&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D&mode=weekly" alt="GitHub Streak" />
</a>

<!-- ─── TROPHIES ─── -->
<a href="https://github.com/merls0515?tab=achievements">
  <img width="90%" src="https://github-profile-trophy.vercel.app/?username=merls0515&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=10&margin-h=10" alt="GitHub Trophies" />
</a>

</div>

---

## 📈 GitHub Contribution Graph

<div align="center">

<a href="https://github.com/merls0515">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=merls0515&theme=tokyo-night&area=true&hide_border=true&custom_title=Merlyn's%20Contribution%20Graph&bg_color=1a1b27&color=70a5fd&line=bf91f3&point=38bdae&title_color=70a5fd" alt="GitHub Activity Graph" />
</a>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/merls0515/merls0515/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/merls0515/merls0515/output/github-snake.svg" />
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/merls0515/merls0515/output/github-snake.svg" />
</picture>

</div>

---

## 🎯 Current Focus

- 🔭 Building advanced RAG systems and agentic AI applications
- 🌱 Exploring state-of-the-art LLMs and multimodal AI
- 👯 Open to collaborations in AI/ML, Healthcare Analytics, and Data Science
- 💬 Ask me about Machine Learning, Deep Learning, NLP, or Healthcare AI

---

## 📫 Let's Connect!

I'm always excited to collaborate on innovative AI/ML projects, discuss emerging technologies, or explore opportunities in data science and healthcare analytics.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)]([https://linkedin.com/in/merlynvictor](https://www.linkedin.com/in/merlyn-victor-15391b2a6/))
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail)](mailto:merlyntvictor@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-100000?style=for-the-badge&logo=github)](https://github.com/merls0515)

</div>

---

<div align="center">

### ⭐ *Always learning, building, and exploring the intersection of AI, data, and real-world impact* ⭐

![Profile Views](https://komarev.com/ghpvc/?username=merls0515&color=blueviolet&style=flat-square)

</div>
