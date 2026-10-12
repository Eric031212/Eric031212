<h1 align="center">Hi there, I'm Hongtao 👋</h1>

<p align="center">
  <b>Sc.M. student in ECE @ Brown University</b> 🐻 · Computer Vision · 3D Generation · LLMs
</p>

<p align="center">
  <a href="mailto:hongtao_xie@brown.edu"><img src="https://img.shields.io/badge/Email-hongtao__xie%40brown.edu-4E2A1E?style=flat-square&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Based%20in-Providence%2C%20RI-blue?style=flat-square" />
</p>

---

### 🙋 About me

- 🎓 Currently doing my **Sc.M. in Electrical & Computer Engineering at Brown** (2026 – 2028)
- 🏫 Before that: **B.S. (Honors) in Computer Science** in China 🇨🇳 — where I fell down the 3D vision rabbit hole 🕳️
- 🧠 I like building things that *see*, *reconstruct*, and *move* — from Gaussian splats to 3D humans picking up objects
- 🛠️ Also happy writing the boring-but-important stuff: Flask backends, SQL schemas, access control 😄
- 🎸 Off the keyboard: I've played **guitar for 15 years** — ask me for song recs
- 💬 Always up for chatting about research, collabs, or just cool demos!

---

### 🔬 Research Interests

- **3D Computer Vision** — novel-view synthesis and scene reconstruction with 3D Gaussian Splatting
- **Generative Modeling** — text-conditioned diffusion for 3D human–object interaction (HOI) synthesis
- **Efficient Sequence Models** — RetNet and Mamba as alternatives to Transformers for long-range dependencies
- **Representation Learning** — contrastive objectives for geometric consistency and cross-modal (text–motion) alignment
- **Large Language Models** and **AI for Healthcare** (safe medication recommendation)

---

### 📄 Publications

- **H. Xie**, H. Zhang. *SCGC: Sparse Control-Guided Gaussian Splatting with Contrastive Learning.*
  ACM VRCAI 2025. [DOI: 10.1145/3779232.3779453](https://doi.org/10.1145/3779232.3779453)
- **H. Xie**, S. Zhu. *MambaGuard-MOO: Multi-Objective Safe Drug Recommendation with Contrastive Learning.*
  IEEE BigData 2025 Workshop on AI in Big Data Analytic for Healthcare.

---

### 🧪 Research Projects

**SCGC — Sparse Control-Guided Gaussian Splatting** · *ACM VRCAI 2025*
- Extends Scaffold-GS with 512 sparse control points (farthest-point-sampling initialization, KNN assignment to scene anchors) and a Transformer-based geometry refinement module.
- Dual-level contrastive learning over control points and Gaussian primitives to improve multi-view consistency.
- NeRF Synthetic (8 scenes, 30k iterations): mean **33.61 dB PSNR / 0.951 SSIM**, +0.07 dB and +0.019 over Scaffold-GS.

**RetHOI — Text-to-3D Human–Object Interaction** · *Final Year Project*
- Text-conditioned diffusion framework with parallel RetNet branches for human and object motion, coordinated via bidirectional cross-retention.
- Multi-scale Gabor filtering for contact-trajectory refinement; CLIP-based contrastive alignment at both the affordance-prediction and motion-generation stages.
- BEHAVE (1,451 sequences), vs. HOI-Diff: foot-skating ratio **−94%**, contact distance **−21.3%**, FID **1.501 → 1.443**, inference time **27.3 → 18.8 min** (−31.1%; 196-frame sequences, RTX 4090).

**MambaGuard-MOO — Safe Drug Recommendation** · *IEEE BigData 2025 Workshop*
- Extends MambaDrug to model diagnosis and procedure histories, with drug–drug interaction (DDI) constraints and medication–diagnosis associations in patient-state transitions.
- Adaptive multi-objective optimization balancing efficacy, safety, ranking and personalization; drug-embedding contrastive learning with staged training.
- MIMIC-III, benchmarked against 9 methods: **F1 0.7052** (vs. SafeDrug 0.6418) and DDI rate **0.0682 → 0.0341** (−50%).

---

### 🚀 Other Fun Stuff I've Built

- 🏫 **E-DBA (Education Data Bay Area)** — 6-person team, full-stack Flask + SQLAlchemy + MySQL platform with multi-tenant access control, audit logs, and JSON-configurable API integration. Got shown off at BNBU's CS Poster Exhibition 🎉
- 🤟 **Sign Language Recognition App** — 3D-CNN turns sign-language videos into word fragments, then BERT stitches them into real sentences. Video in, text out!
- 🌱 Won a **Special Mentions Prize** at HKBU Greenhack *"Hack for Climate Action"* (2023)

---

### 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Models I play with:** Gaussian Splatting · Diffusion · Transformers · RetNet · Mamba · CLIP · BERT

---

<p align="center"><i>Thanks for stopping by! ⭐ Feel free to poke around my repos.</i> 🎸✨</p>
