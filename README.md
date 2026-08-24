<!-- Banner -->
<img src="./banner_for_github.png" alt="Pushkar Kumar Banner" style="width:100%; border-radius: 10px;" />

<h1 align="center">Hi 👋, I'm Pushkar Kumar</h1>
<h3 align="center">⚛️ |Pushkar⟩ = α|Quantum⟩ + β|AI⟩ — Turning quantum theory and AI into real-world systems</h3>

<img align="right" alt="Coding" width="300" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" />

- 🎓 **B.Tech Computer Science** at **MIT ADT University** — AI & Edge Computing, Quantum Technologies minor
- ⚛️ **Qiskit Advocate** at IBM · **Lead Organizer**, Qiskit Fall Fest 2026 · **Technical Team Lead**, QQuEST
- 🔬 **QIntern 2026** with QWorld and the **Moderna challenge** in the **WISER Global Quantum+AI Program** — both completed
- 🧠 Building **Quantum Arcade**, an interactive way to learn quantum computing, and **RepoBridge**, grounded repository context for LLMs
- 📊 Every project below says what can be checked — including the ones where the answer is "not yet"
- 🌐 Full case studies with the limitations included → **[my portfolio](https://portfolio.pushkarkumar0997.workers.dev/)**

---

## 🧭 About Me

I work where **physics, math, and computer science** meet — quantum algorithms on one side, production machine learning on the other.

Most of what I do comes down to the same thing: making a system's real behaviour visible. That means building the control that tells you *which* component failed, catching the data leakage in your own result before someone else does, and reporting the number you got rather than the number you wanted.

I like to:
- Design and reason about **quantum algorithms** at the circuit level — Grover oracles, variational solvers, encoding schemes
- Build **end-to-end ML workflows**: data → distributed training → evaluation → deployment
- Turn ideas from **papers and workshops** into working, measured prototypes
- Write things up so a reader can **check the claims** instead of taking them on trust

---

## 🛠️ Tech Stack & Tools

### Languages & Databases

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=fff)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

### Quantum & Machine Learning

![Qiskit](https://img.shields.io/badge/Qiskit-6129F6?style=for-the-badge&logo=IBM&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### Dev, Cloud & Tools

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=000)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🚀 What I'm Building

### 🎮 Quantum Arcade — [live](https://quantum-arcade.web.app/)

Learn quantum computing the way you'd learn a language: short interactive levels with immediate feedback, real state vector evaluation underneath rather than scripted animations. Start at Level 1 in the browser, no account needed.

### 🌉 RepoBridge — deploying soon

Turns a public GitHub repository into grounded, traceable context for an LLM. Every file is accounted for, every omission carries a reason, and every summary states what it was built from — because a confident summary of a repository nobody read looks exactly like one of a repository that was.

---

## 🔬 Selected Work

### ⚛️ Quantum Document Pipeline — QIntern 2026, QWorld
FRQI/NEQR encoding, a quanvolutional feature layer, and a Grover comparator oracle, benchmarked against Tesseract with 30-split significance testing. An earlier run of mine reported a +1.4 point gain — the angle search had touched rows that later appeared in the test set, and re-running with a sealed partition brought it to +0.1. Both numbers are in the report.

Reproduces from a clean clone in under a minute. Scoped for three people; all 23 commits are mine.

`Repo:` [qi26_25](https://github.com/Pushkar0997/qi26_25) · [Live demo](https://pushkar0997.github.io/qi26_25/) · [Report](https://github.com/Pushkar0997/qi26_25/blob/main/docs/final_report.md)

### 🧬 RNA Folding with Quantum Optimization — WISER × Moderna challenge
CVaR-VQE reproduces ViennaRNA's exact minimum-free-energy structure at a 0.000 kcal/mol gap, holding across 35 runs under shot and depolarizing noise. Where it missed, exhaustive brute force over the same QUBO missed identically — proving the limitation was in the formulation, not the optimizer.

`Repo:` [Moderna-Quantum-RNA](https://github.com/Harold-Ohandja/Moderna-Quantum-RNA-) · [Interactive explainer](https://harold-ohandja.github.io/Moderna-Quantum-RNA-/)

### ⚡ Distributed Training on GCP Vertex AI
Multi-GPU Longformer fine-tuning with a self-relaunching `accelerate` topology, rank-gated tokenization behind a barrier file, explicit NCCL configuration, and a four-destination checkpoint strategy. Plus a cheap smoke test that validates IAM and GCS access before any GPU spins up — written after a silent deadlock ran unattended for twenty hours and produced nothing.

`Repo:` [vertex-pytorch-trainers](https://github.com/Pushkar0997/vertex-pytorch-trainers)

### 🌿 Plant Disease Detection (DenseNet-169)
Two-stage pipeline: contour/HSV localisation, then DenseNet-169 across 15 PlantVillage classes. 97.8% accuracy, 97.7% macro F1 on 4,134 images — though validation drove checkpoint selection, so that number is optimistically biased and I say so. The confidence floor was chosen by measurement: my first instinct of 0.40 would have suppressed zero errors, so it ships at 0.80.

`Repo:` [plant-disease-densenet169](https://github.com/Pushkar0997/plant-disease-densenet169) · [Demo](https://huggingface.co/spaces/PushkarKumar/plant-disease-densenet169) · [Model](https://huggingface.co/PushkarKumar/plant-disease-densenet169)

### 📰 Veritas AI — long-context misinformation classification
Longformer across three iterations. v1 had a malformed global attention mask that differed between training and inference, so Longformer's defining mechanism was misconfigured for the whole run. v2 fixes it and trains on ISOT, LIAR and FEVER merged on Vertex AI.

`Repo:` [veritas_ai_v2](https://github.com/Pushkar0997/veritas_ai_v2) · [Model](https://huggingface.co/PushkarKumar/veritas_ai_v2)

### 🧪 Quantum Toybox
Ten quantum algorithms as runnable notebooks — Bell states, teleportation, Deutsch–Jozsa, Bernstein–Vazirani, Grover, QFT, phase estimation, VQE, and basic error correction. A learning and reference collection, not a packaged library.

`Repo:` [quantum-toybox](https://github.com/Pushkar0997/quantum-toybox) · [Grover's Algorithm](https://github.com/Pushkar0997/Grover-s_Algorithm_Implementation)

More at [github.com/Pushkar0997](https://github.com/Pushkar0997) · Full case studies at [my portfolio](https://portfolio.pushkarkumar0997.workers.dev/)

---

## 📈 Contribution Activity

<p align="center">
  <img 
    src="https://github-readme-activity-graph.vercel.app/graph?username=Pushkar0997&theme=tokyo-night&hide_border=true" 
    alt="GitHub Activity Graph" 
  />
</p>

---

## 🌆 GitHub 3D Skyline

![3D Skyline GIF](./pushkar-skyline.gif)

> View the full interactive skyline here: [skyline.github.com/Pushkar0997](https://skyline.github.com/Pushkar0997)

---

## 🌐 Connect & Collaborate

Currently available for **contract ML engineering**, **quantum algorithm work**, and **research collaboration**.

I'm always open to:
- Collaborating on **quantum computing**, **QML**, or **ML research** projects
- Contributing to **open source** and learning through real-world PRs
- Talking about ideas at the intersection of **physics, AI, and real-world systems**

<p align="center">
  <a href="https://portfolio.pushkarkumar0997.workers.dev/">
    <img src="https://img.shields.io/badge/Portfolio-16211d?style=for-the-badge&logo=astro&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/pushkar-kumar-aaa96a301">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://huggingface.co/PushkarKumar">
    <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000" />
  </a>
  <a href="mailto:pushkarkumar0997@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-red?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
