<div align="center">
  <h1>Hi there, I'm Abhivanth R 👋</h1>
  <p>
    <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&pause=1000&color=8B5CF6&center=true&vCenter=true&width=600&lines=AI+Engineer+%7C+Freelancer;Machine+Learning+%7C+Computer+Vision;IoT+Developer+%7C+Researcher;Building+Intelligent+Systems" alt="Typing SVG" />
  </p>

  <p>
    <a href="https://abhivanth-r.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
    <a href="https://www.linkedin.com/in/abhivanth-r-223b2b281"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:abhicoder39@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  </p>
</div>

---

## 🚀 About Me

I am an **AI Engineer** specializing in **Machine Learning**, **Computer Vision**, and **Intelligent Systems**. I build production-grade solutions leveraging LLMs, computer vision, and IoT integration. As a published researcher with hands-on experience deploying AI systems, I thrive at the intersection of research and real-world application.

* **Current Focus**: LLM internals, AI agents, self-supervised learning architectures (JEPA), computer vision for defect detection, and edge ML systems.
* **Goal**: Building the future with AI, one scalable and intelligent system at a time.

---

## 🏆 Featured Projects

### 🧠 AI & Machine Learning

<details open>
<summary><b>🔍 JEPA Exhibit Defect Detection</b></summary>
<br>

> **Advanced Self-Supervised Anomaly Detection System**
* **Links**: [Video Demo](https://www.youtube.com/watch?v=QXVEDSoT5Rk) | [Portfolio Page](https://abhivanth.vercel.app/project/exhibit-defect-detection)

**About This Project**
The **JEPA Exhibit Defect Detection System** is an advanced AI backend engineered to identify anomalies or physical defects in real-time video streams, specifically designed for exhibition or CCTV environments. It operates under a self-supervised learning paradigm, eliminating the need for massively labeled sets of "defective" data by exclusively learning the patterns of "normal" behavior instead. 

**Architecture & Features**:
* At its core, the system utilizes a **Joint-Embedding Predictive Architecture (JEPA)**, which breaks down video frames into components and learns to predict future spatial and temporal representations. 
* Incorporates **Temporal Transformers** to understand both short-term actions and long-term activity contexts. 
* For spatial awareness, a **Spatial JEPA Head** cross-examines patches of video to detect localized physical anomalies. 
* Employs a **Deep SVDD (Support Vector Data Description) Energy Model** to generate a final definitive anomaly score, flagging any events or objects that heavily deviate from the learned "normal" manifold.
* Built on **FastAPI**, offering a robust and asynchronous API supporting standard video file uploads as well as live streaming.
* Real-time processing capability utilizing **WebSockets** and **Server-Sent Events (SSE)** to stream inference progress, frame-by-frame anomaly scores, and base64-encoded visual outputs directly to a frontend client.
* A **YOLO-based Human Masking** filter is integrated during the preprocessing phase to combat false positives triggered by irrelevant dynamic elements.

Ultimately, this multi-stage pipeline provides a highly configurable, latency-optimized, and deeply analytical tool for maintaining quality control and security in physical exhibition spaces.

* **Tech Stack**: `Python` `PyTorch` `FastAPI` `JEPA` `YOLO` `Transformers` `WebSockets`
</details>

<details>
<summary><b>🔬 LLM Internals Explorer</b></summary>
<br>

> **Educational platform exposing transformer architecture internals**
* **Links**: [GitHub Repo](https://github.com/Abhivanth-08/LLM_WORKFLOW) | [Live Demo](https://llm-workflow-five.vercel.app/) | [Video](https://www.youtube.com/watch?v=gXtoIvVpRog)
* Features Attention Head Personality Profiler analyzing GPT-2's 144 attention heads, 3D semantic vector arithmetic, real-time BPE tokenization, and prompt injection detection.
* **Tech Stack**: `Python` `React` `FastAPI` `PyTorch` `Transformers` `TypeScript` `Three.js`
</details>

<details>
<summary><b>🛡️ Info Redaction Agent</b></summary>
<br>

> **AI system automatically detecting and redacting PII from PDFs**
* **Links**: [GitHub Repo](https://github.com/Abhivanth-08/info_redaction_main) | [Live Demo](https://0207abhi-info-redaction.hf.space) | [Video](https://youtu.be/lrfmWWnmnu0)
* Ensures GDPR/CCPA compliance using advanced NLP pipelines.
* **Tech Stack**: `Python` `LangChain` `PyMuPDF` `Docling` `FastAPI` `TypeScript`
</details>

<details>
<summary><b>🎵 AI Foley Studio</b></summary>
<br>

> **AI-powered platform for automatic Foley sound effect generation**
* **Links**: [GitHub Repo](https://github.com/Abhivanth-08/AI-Foley-Studio) | [Live Demo](https://ai-foley-studio.vercel.app/) | [Video](https://youtu.be/p_SFvmGrAnE)
* Utilizes YOLO/MediaPipe for video analysis to synchronize generated audio with visual actions.
* **Tech Stack**: `LangChain` `Computer Vision` `MediaPipe` `YOLO` `TypeScript` `FastAPI`
</details>

<details>
<summary><b>👨‍💻 Pull Request Review Agent</b></summary>
<br>

> **Intelligent AI tool for automated code reviews**
* **Links**: [GitHub Repo](https://github.com/Abhivanth-08/PR_review) | [Live Demo](https://pr-review-phi.vercel.app) | [Video](https://youtu.be/fddj0gHc6f0)
* Features security vulnerability detection and code optimization suggestions.
* **Tech Stack**: `TypeScript` `LangChain` `FastAPI` `GitHub API`
</details>

<details>
<summary><b>📄 AI Assistants: Resume Reformer & College Chatbot</b></summary>
<br>

* **[Resume Reformer Agent](https://github.com/Abhivanth-08/Resume-Reformer)**: AI agent optimizing resumes for ATS compatibility through job description analysis.
* **[College Chatbot](https://github.com/Abhivanth-08/College_chatbot)**: AI-powered chatbot with RAG pipeline for admissions, events, and exam prep.
* **Tech Stack**: `Python` `LangChain` `Prompt Engineering` `PyMuPDF` `Docling` `LanceDB`
</details>

### 🤖 Robotics & IoT

<details>
<summary><b>🦾 Autonomous Robots: NDT & Versatile Mini Robot</b></summary>
<br>

* **[NDT Robot](https://github.com/Abhivanth-08/NDT)** | [Video Demo](https://youtu.be/ZaZC1xjsAsI): Autonomous Non-Destructive Testing robot using ultrasonic, infrared, and eddy current sensors for real-time defect detection.
* **[Versatile Mini Robot](https://github.com/Abhivanth-08/Mini_Robot)** | [Video Demo](https://youtu.be/i9UhpPylS8M): Multifunctional robot with object recognition, QR/text scanning, and virtual assistance on Raspberry Pi.
* **Tech Stack**: `Python` `OpenCV` `Raspberry Pi` `Sensors` `Machine Learning`
</details>

### 🌐 Web Development

<details>
<summary><b>🛒 E-Commerce Platform</b></summary>
<br>

* **Links**: [GitHub Repo](https://github.com/Abhivanth-08/JV_web) | [Live Demo](https://jvenerprise.vercel.app)
* Full-featured e-commerce platform with secure payments and admin dashboard.
* **Tech Stack**: `TypeScript` `Supabase` `React`
</details>

---

## 💻 Technical Skills

| Domain | Technologies |
| :--- | :--- |
| **AI/ML & Deep Learning** | `PyTorch` `Scikit-learn` `LangChain` `Transformers` `OpenCV` `CNN` `YOLO` `Azure AI` |
| **Programming Languages** | `Python` `TypeScript` `C` `Java` `R` `SQL` |
| **Backend & Tools** | `FastAPI` `Docker` `Git` `Supabase` `LanceDB` `Docling` |
| **IoT & Edge AI** | `Raspberry Pi` `Arduino` `ESP32` `Embedded Systems` |

---

## 📈 Experience & Achievements

* **💼 ML Engineer Intern** @ *Nitroware Technologies* (Jan 2025 - Feb 2025)
  * Built predictive ML models and Flask-based applications for breach event detection.
* **📚 Published Researcher**
  * *CRC Book Chapter (Accepted, Sep 2025)*: Secure and Ethical AI-Driven Approaches to Data Privacy in Sustainable Agriculture
* **🎓 Education**
  * B.E. Computer Science & Engineering (AIML), K P R Institute of Engineering and Technology (2023 - 2027) | **CGPA: 8.8**
* **🏆 Impact**
  * 10+ Production AI/ML Projects with Live Deployments.
  * Active Contributor to Open Source AI Tools.

<br />

<div align="center">
  <a href="https://github.com/Abhivanth-08">
    <img src="https://github-readme-stats.vercel.app/api?username=Abhivanth-08&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
  </a>
  <a href="https://github.com/Abhivanth-08">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Abhivanth-08&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" />
  </a>
</div>

<p align="center">
  <br />
  <i>Building the future with AI, one system at a time.</i>
</p>
