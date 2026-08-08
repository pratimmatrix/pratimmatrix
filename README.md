<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=250&section=header&text=Pratim%20Mistry&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%2FML%20Engineer%20%7C%20Software%20Engineer%20%7C%20Builder&descAlignY=55&descAlign=50" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=%2BSoftware+Engineering;AI%2FML+Engineer+%7C+Computer+Vision;Building+GPT-2+from+Scratch+in+NumPy;Open+to+Software+%2F+AI+Internships" alt="Typing SVG" />
</a>

<br/>

![Academic](https://img.shields.io/badge/B.E.-Mechanical%20Engineering-6D28D9?style=for-the-badge&logo=studyverse&logoColor=white)
![University](https://img.shields.io/badge/Panjab%20University-Chandigarh-4C1D95?style=for-the-badge&logo=googlescholar&logoColor=white)
![Location](https://img.shields.io/badge/📍-Chandigarh,%20India-8B5CF6?style=for-the-badge)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pratim-mistry-822984322)
[![Email](https://img.shields.io/badge/Email-5B21B6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pratimofficial108@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pratimmatrix)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=pratimmatrix&color=8B5CF6&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/pratimmatrix?color=A78BFA&style=for-the-badge&label=FOLLOWERS&labelColor=1e1b2e)
![Stars](https://img.shields.io/github/stars/pratimmatrix?color=7C3AED&style=for-the-badge&label=STARS&labelColor=1e1b2e)

</div>

<br/>

## 🪐 About Me

<img align="right" width="300" src="https://raw.githubusercontent.com/gist/vn7n24fzkq1/main/wave.gif" />

```yaml
name: "Pratim Mistry"
role: "AI/ML Engineer · Software Engineer · Computer Vision Enthusiast"
background: "Mechanical Engineering foundation, self-driven into Software & AI"
focus:
  - Building ML systems end-to-end, from raw math to working applications
  - Deep systems understanding — implemented GPT-2 inference from raw NumPy
  - Computer Vision & Object Detection (YOLO-based real-time systems)
  - Full-stack product engineering with Python/FastAPI backends
mindset: "Engineer first, ML practitioner second — I care about how things
          work under the hood, not just calling an API"
```

I'm an engineering student who traded pure mechanical systems for computational ones — currently building AI-powered applications that ship, not just notebooks that demo. My work spans **from-scratch transformer inference engines** and **real-time computer vision systems**. I care deeply about correctness — validating implementations token-for-token against reference models rather than assuming they work.

**🎯 Open To:** AI/ML Engineering Internships · Software Engineering Roles · Computer Vision Projects · Open Source Collaboration

---

## 🧠 Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,c,cpp,html,css&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=html,css,js,react&theme=dark" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=fastapi,python,sqlite,mysql&theme=dark" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=aws,git,github,vscode,vercel&theme=dark" />

**ML / Data Stack**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,sklearn&theme=dark" />

</div>

---

## 🔬 AI/ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:--|:--:|:--|
| **Deep Learning & Transformers** | ⭐⭐⭐⭐☆ | Built GPT-2 inference engine from scratch in NumPy — attention, KV-cache, LayerNorm, MLP |
| **Computer Vision** | ⭐⭐⭐⭐☆ | Real-time object detection (YOLO) for gym equipment recognition using OpenCV + PyTorch |
| **NLP & Tokenization** | ⭐⭐⭐☆☆ | Implemented byte-pair-encoding (BPE) tokenizer and nucleus/top-k/top-p sampling from scratch |
| **Data Engineering & Visualization** | ⭐⭐⭐☆☆ | Pandas-driven data workflows, Plotly-based interactive analytics |
| **Applied Data Analytics** | ⭐⭐⭐☆☆ | Hands-on practice via Forage job simulations (Goldman Sachs, Tata, Deloitte, BCG X) |

</div>

---

## 🚀 Featured Projects

<details>
<summary><b>🏋️ Gym Whale — AI-Powered Gym Equipment Scanner</b></summary>
<br/>

Real-time gym equipment recognition app that identifies machines like bench press, lat pulldown, cable machines, and dumbbells directly from camera input, then surfaces exercise instructions, target muscles, and safety tips instantly.

| Category | Details |
|:--|:--|
| **Stack** | Python, FastAPI, PyTorch, OpenCV, YOLO |
| **Scale** | Real-time single-frame inference pipeline |
| **Performance** | Low-latency object detection tuned for live camera feed |
| **Security** | Local inference — no external data transmission |
| **Impact** | Instant equipment identification + safety guidance for gym users |
| **Repository** | [View Repo](https://github.com/pratimmatrix/gym-whale) |

Built as an end-to-end computer vision product rather than a research prototype — the backend is designed around FastAPI to keep inference and API concerns cleanly separated, with OpenCV handling the video pipeline and PyTorch driving the detection model. The detector is trained to recognize multiple equipment classes, mapping each detection to target-muscle information and safety guidance.

</details>

<details>
<summary><b>🧮 GPT-2 Inference Engine — Pure NumPy</b></summary>
<br/>

A GPT-2 inference engine engineered entirely in NumPy — no PyTorch or TensorFlow at inference time — implementing causal multi-head self-attention with KV-caching, layer normalization, and the MLP block as raw matrix operations.

| Category | Details |
|:--|:--|
| **Stack** | Python, NumPy, custom BPE tokenizer |
| **Scale** | Full GPT-2 architecture reproduction at the matrix-operation level |
| **Performance** | Verified full-sequence vs incremental KV-cache generation match (max diff 1e-12) |
| **Security** | N/A — local research/education-grade engine |
| **Impact** | Token-for-token logit parity validated against reference HuggingFace GPT-2 |
| **Repository** | [View Repo](https://github.com/pratimmatrix/gpt2-numpy) |

This project strips away high-level framework abstractions to prove a from-first-principles understanding of transformer internals — including a from-scratch BPE tokenizer and temperature / top-k / top-p sampling strategies, with profiling work to isolate matrix-multiplication bottlenecks from Python-level overhead.

</details>

---

## 🤝 Leadership & Extracurricular

<div align="center">

| Role | Organization | Duration |
|:--|:--|:--:|
| Co-Convener | Programming Club (P Club), UIET Panjab University | 2025 – 2026 |
| Co-Convener | SAE Collegiate Club, UIET Panjab University | 2025 – 2026 |
| Co-Convener | Entrepreneurship Development Cell (EDC), UIET Panjab University | 2025 – 2026 |

</div>

---

## 📜 Certifications

**Forage Job Simulations**

[![Goldman Sachs](https://img.shields.io/badge/Goldman%20Sachs-Operations%20Job%20Simulation-6D28D9?style=for-the-badge&logo=forage&logoColor=white)](https://www.linkedin.com/feed/update/urn:li:activity:7490406987923468288/)
[![Tata](https://img.shields.io/badge/Tata-GenAI%20Powered%20Data%20Analytics-5B21B6?style=for-the-badge&logo=forage&logoColor=white)](https://www.linkedin.com/feed/update/urn:li:activity:7490407516778938369/)
[![Deloitte](https://img.shields.io/badge/Deloitte%20Australia-Data%20Analytics%20Job%20Simulation-7C3AED?style=for-the-badge&logo=forage&logoColor=white)](https://www.linkedin.com/feed/update/urn:li:activity:7490407944644120576/)
[![BCG X](https://img.shields.io/badge/BCG%20X-Data%20Science%20Job%20Simulation-8B5CF6?style=for-the-badge&logo=forage&logoColor=white)](https://www.linkedin.com/feed/update/urn:li:activity:7490408404054831104/)

</div>

---

## 💻 Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-Solve%20%26%20Grind-4C1D95?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/pratimmatrix)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-Profile-5B21B6?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://geeksforgeeks.org/user/pratimmatrix)
[![HackerRank](https://img.shields.io/badge/HackerRank-Profile-6D28D9?style=for-the-badge&logo=hackerrank&logoColor=white)](https://hackerrank.com/pratimmatrix)
[![CodeChef](https://img.shields.io/badge/CodeChef-Profile-7C3AED?style=for-the-badge&logo=codechef&logoColor=white)](https://codechef.com/users/pratimmatrix)

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=pratimmatrix&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9C9C9"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pratimmatrix&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9C9C9"/>

<img src="https://streak-stats.demolab.com?user=pratimmatrix&theme=radical&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA"/>

</div>

---

## 🏅 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=pratimmatrix&theme=radical&no-frame=true&no-bg=true&margin-w=15&column=7"/>

</div>

---

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=pratimmatrix&theme=react-dark&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C4B5FD&area=true&hide_border=true"/>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/pratimmatrix/pratimmatrix/output/github-contribution-grid-snake-dark.svg"/>

</div>

---

## 🎯 Current Focus

```yaml
Learning:
  - Advanced Transformer architectures & inference optimization
  - Systems-level deep learning (CUDA fundamentals, kernel-level thinking)
  - Full-stack product engineering patterns

Building:
  - Gym Whale — real-time computer vision fitness app
  - Expanding the NumPy GPT-2 engine toward fine-tuning support

Exploring:
  - MLOps & production deployment patterns
  - Edge inference optimization for CV models

Open To:
  - AI/ML Engineering Internships
  - Software Engineering Roles
  - Open Source Collaboration
```

---

## 📫 Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-pratimofficial108%40gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pratimofficial108@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pratim-mistry-822984322)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pratimmatrix)
[![X](https://img.shields.io/badge/X-Follow-A78BFA?style=for-the-badge&logo=x&logoColor=white)](https://x.com/pratimmatrix)

</div>

---

<div align="center">

*"Engineering is not about knowing the answer — it's about building the system that finds it."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
