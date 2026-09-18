<h1 align="center">Hi, I'm Manmay Ghosh 👋</h1>
<h3 align="center">M.Tech CS @ NIT Calicut · Full-Stack & Applied ML</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/manmay-ghosh-b13b0321a/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="https://leetcode.com/u/Manmay_Ghosh/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white" /></a>
  <a href="https://www.geeksforgeeks.org/profile/manmayghoojsm"><img src="https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=flat&logo=geeksforgeeks&logoColor=white" /></a>
  <a href="mailto:manmay.m250868cs@nitc.ac.in"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
</p>

---

### About Me

- 🎓 M.Tech in Computer Science and Engineering, **NIT Calicut**
- 🔬 Researching multimodal stress assessment on wearable physiological signals (ECG + EDA), with a focus on **explainable AI (Grad-CAM)** — advised by Dr. Anu Mary Chacko
- 🛠️ Build and deploy full-stack applications end-to-end — MERN stack, containerized with Docker, shipped to production (Render/Vercel), several with a real trained ML or LLM component wired in
- 🧮 350+ problems solved on LeetCode (**Knight** badge) — C++ and Python
- 🌱 Aiming to pursue a **PhD in Machine Learning**

---

### 🔭 Current Research

**Multimodal Learning for Automated Stress Assessment**
A 1D-ResNet pipeline for binary stress classification on the WESAD dataset (chest ECG + EDA, 700Hz), evaluated under subject-independent Leave-One-Subject-Out cross-validation, with a systematic depth/pooling ablation and Grad-CAM-based explainability on raw physiological windows.

- ResNet-18 (GAP) baseline: **88.63% ± 16.78%** mean LOSO accuracy, **87.48% ± 18.71%** F1
- Full resumable training pipeline: crash-safe checkpointing, disk-cached preprocessing, mixed-precision training, early stopping
- Depth ablation (ResNet-18/34/50/101) and Grad-CAM explainability integration in progress

---

### 🚀 Full-Stack Applications

| Project | What it does | Stack | Live |
|---|---|---|---|
| **[Ledger — AI Expense Tracker](https://github.com/ManmayGhosh/mern-expense-tracker)** | Expense tracker with a real trained classifier (TF-IDF + Logistic Regression, **79% accuracy** on 2,400+ transactions) auto-categorizing spend, plus a forecasting model for next month | React, Node/Express, MongoDB, Python/FastAPI, Docker | [Demo](https://mern-expense-tracker-sable-zeta.vercel.app/) |
| **[Task Manager + RBAC](https://github.com/ManmayGhosh/task-manager-rbac)** | 3-tier role-based task platform (admin/manager/member) with a decoupled FastAPI microservice for AI task breakdown & daily digests | React, Node/Express, MongoDB, Python/FastAPI, Docker | [Demo](https://task-manager-rbac-frontend.onrender.com) |
| **[ParkEase — Mall Parking System](https://github.com/ManmayGhosh/park-rbac)** | 4-role RBAC platform (driver/owner/guard/admin) with atomic slot booking and a dual-QR entry/exit + payment workflow | React, Node/Express, MongoDB, Docker, Nginx | [Demo](https://park-rbac-frontend.onrender.com) |
| **[Secure Chat App](https://github.com/ManmayGhosh/secure-chat-app)** | Real-time chat hardened against XSS/NoSQL-injection/CSRF — JWT access+refresh rotation, bcrypt, strict CSP, account lockout | Node/Express, Socket.IO, MongoDB, Docker | [Demo](https://secure-chat-app-5yn3.onrender.com) |
| **[Rent vs Buy AI Advisor](https://github.com/ManmayGhosh/run-vs-buy-advisor)** | Month-by-month financial simulation (amortization, appreciation, opportunity cost) paired with LLM-generated, transparent reasoning | React, Node/Express, MongoDB, Docker, Groq (LLM) | [Demo](https://run-vs-buy-advisor-frontend.onrender.com) |
| **[Real-Time Multiplayer Chess](https://github.com/ManmayGhosh/mern-chess)** | Server-authoritative chess engine with client-side prediction + reconciliation, tested under simulated latency/jitter/packet loss | React, Node/Express, WebSocket, MongoDB, Docker | [Demo](https://mern-chess-jj10.onrender.com) |
| **[Movie Night Matcher](https://github.com/ManmayGhosh/mern-movie-night-matcher)** | Real-time group movie swiping over Socket.io with live TMDB-backed decks and instant match detection | React, Node/Express, MongoDB, Socket.io, Docker | [Demo](https://movie-matcher-client.onrender.com/) |
| **[Chalkboard Hangman](https://github.com/ManmayGhosh/mern-hangman)** | Word game with server-authoritative state, OS-dictionary word source, and a dual-mode Nginx config for one image across Compose + Render | React, Node/Express, MongoDB, Docker, Nginx | [Demo](https://mern-hangman-frontend.onrender.com/) |
| **[Streamly — Netflix Clone](https://github.com/ManmayGhosh/mern-netflix-clone)** | Full browsing experience — auth, search, "My List" — with a 100-title synthetic catalog and a custom glassmorphism UI | React, Node/Express, MongoDB, Docker | [Demo](https://mern-netflix-clone-frontend-livid.vercel.app) |
| **[Inkwell — Blogging Platform](https://github.com/ManmayGhosh/mern-blog)** | Full-stack blog with a generative Three.js hero (4 offline-rendered scenes) matched to post content via a local keyword engine | React, Node/Express, MongoDB, Three.js, Docker | Deployed (Render) |
| **[NITC Event Board](https://github.com/ManmayGhosh/NITC_event_board_)** | Event management board built as an M.Tech team coursework project (SSL Lab) | React, Node/Express, MongoDB |
| **[Bidding Simulator](https://github.com/ManmayGhosh/bidding-simulator)** | Full-stack bidding/auction simulator | Backend + Frontend |

### 🤖 AI / ML Projects

| Project | What it does | Stack |
|---|---|---|
| **[Spam & Toxic Comment Detector](https://github.com/ManmayGhosh/spam-toxic-detector)** | REST API — spam detection (**98.3% accuracy**) + 6-label toxic comment classifier (**0.96–0.99 ROC-AUC** across labels, 159K-comment Jigsaw dataset) | FastAPI, scikit-learn, Docker — [Live](https://spam-toxic-detector.onrender.com) |
| **[Sector Sentiment Stock Prediction](https://github.com/ManmayGhosh/stock-analysis)** | Dual-engine NLP (VADER + FinBERT) + LSTM/XGBoost ensemble, with a cross-stock sentiment-spillover feature as the key differentiator | Python, PyTorch/XGBoost, FastAPI, React, Docker |
| **[Buy or Wait — Financial Affordability Agent](https://github.com/ManmayGhosh/hackathon-buy-or-wait)** | AI agent deciding whether a user can safely afford an expense, reasoning over recurring costs, pending payments, and messages/images — built for the HackerRank Orchestrate 24-hour hackathon | Python, LLM agents |

---

### 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socket.io&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ManmayGhosh&show_icons=true&theme=default&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ManmayGhosh&layout=compact&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ManmayGhosh&hide_border=true" />
</p>

---

<p align="center"><i>Open to research collaborations, ML internships, and interesting side projects.</i></p>
