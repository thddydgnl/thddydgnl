<!-- Auto-generated from thddydgnl/cv (cv.yaml + templates/readme.md.j2). Do not edit here — changes are overwritten. -->
# YongHwi Song · 송용휘

**B.S. Candidate · Chungbuk National University**<br>
World Models · World-Action Models · Model-Based Planning · Tool-Using Language Agents

[Academic Homepage](https://thddydgnl.github.io/) · [CV (PDF)](https://thddydgnl.github.io/YongHwi_Song_CV.pdf) · [Email](mailto:thddydgnl1937@gmail.com)

I am an undergraduate researcher in Information and Communication Engineering at Chungbuk National University. My research focuses on world models and world-action models: learning compact models of the environment, planning inside them, and reading actions out of them efficiently. I also explore world models as decision modules for tool-using language agents. Previously, I worked on multimodal reinforcement learning for autonomous driving.

## Education & Research Experience

| Period | Role & Affiliation |
| :--- | :--- |
| Mar. 2023 – Feb. 2027 (Expected) | **B.S. Candidate**, School of Information and Communication Engineering, Chungbuk National University · GPA **3.83 / 4.5** |
| Jun. 2026 – Present | **Research Intern**, Artificial Intelligence Laboratory (AI Lab), Chungbuk National University (Advisor: Prof. Keon Myung Lee) · Researching efficient and reliable world models and their use in LLM agents.<br>– Showed that MPPI planners exploit deterministic rounding error in low-bit TD-MPC2 world models; training-free dithering removed a median **95% of the success drop** on Meta-World.<br>– Found that latent world-model imagination blurs near misses: success-vs-near-miss AUROC fell from **0.953 to 0.853** on DINO-WM PushT, while far misses stayed separable.<br>– Showed that a frozen decision model, JEV, works as an LLM agent's world model without task training, reaching **93.4% success** in TextWorld vs. 79.5% for a failure-memory baseline. |
| Mar. 2025 – Jun. 2026 | **Research Intern**, Multimedia Information Processing (MIP) Laboratory, Chungbuk National University (Advisor: Prof. Hyun Soo Kang) · Conducted research on multimodal reinforcement learning for autonomous driving.<br>– Designed and implemented RCS-AC, a CARLA driving actor-critic that gates RGB, LiDAR, route, and ego-state features by sensor reliability, risk, and Shapley contribution. |

## Activities & Leadership

| Period | Role & Organization |
| :--- | :--- |
| Oct. 2026 – Present | **Runner (13th Cohort)**, [Hello, World! Season 2 — World Models Paper Review](https://github.com/Pseudo-Lab/hello-world-models), Pseudo Lab (가짜연구소) · Reviewing world-model research papers, participating in technical discussions, and contributing structured review documents to the project website. |
| Jan. 2026 – Sep. 2026 | **Team Leader**, Applied Machine Learning Division, HyperCore AI & Data Analytics Club · Formed and led a club team for hackathons and paper reviews. |

## Research Interests

- **World Models and World-Action Models**
- **Model-Based Planning and Reinforcement Learning**
- **Efficient and Reliable World Models**
- **World Models for Embodied and Language Agents**

## Publications & Manuscripts

### Under Review

- **Planners Exploit Deterministic Error: Dithered Low-Bit World Models**<br>
  Song, YongHwi* and Lee, Keon Myung · Submitted to the **Korean Artificial Intelligence Association (KAIA) Conference** (poster), 2026. Extended version to be submitted to Robotics: Science and Systems (RSS) 2027.
- **Near-Miss Blindness: Latent World-Model Imagination Loses Resolution at the Outcome Boundary**<br>
  Song, YongHwi* and Lee, Keon Myung · Submitted to the **Korean Artificial Intelligence Association (KAIA) Conference** (poster), 2026. Extended version to be submitted to Transactions on Machine Learning Research (TMLR).
- **Imagine Once, Act Fast: Lightweight Action Readout from a Frozen Driving World-Action Model**<br>
  Song, YongHwi* and Kang, Hyun Soo · Submitted to the **Korean Artificial Intelligence Association (KAIA) Conference** (poster), 2026.

### In Preparation

- **K-PragShift: Diagnosing Korean Pragmatic Revisions in Tool-Using Language Models**<br>
  Song, YongHwi* · To be submitted to the **EACL 2027 Student Research Workshop**.
- **Imagine Once, Act Fast: Lightweight Action Readout from a Frozen Driving World-Action Model**<br>
  Song, YongHwi* and Lee, Keon Myung · To be submitted to **Transactions on Machine Learning Research (TMLR)**.

### Conference Presentations

- **A World Model for LLM Agents: Comparing a Decision Model with General-Purpose LLMs**<br>
  Song, YongHwi* and Lee, Keon Myung · Oral presentation, **2026 Fall Conference of the Korean Institute of Intelligent Systems (KIIS)**.

\* First author. Submitted work is listed with its current submission status.

### Additional Publication

- Hyeban Namgung, Kuk Seorin, Park Geonwoo, Bae Seohyun, **Song Yonghwi**, Lee Hyesong, Han Jian, Hyojoong Kim. “A Comparative Study on the Prevalence of Forensic Flies Using Chicken Corpse.” *Journal of Science Education for the Gifted*, 2020.

## Selected Projects

### [Moonkeeper — CLPS Lunar Mission Explorer](https://github.com/HANORAAI-png/Moonkeeper)

**2026 NASA Space Apps Challenge Team Project · Sep. 2026 – Present**<br>
Building a React web app that visualizes CLPS lunar landing sites, Sun/Earth visibility windows, and mission timelines from NASA data.

### [Folding — Local-First Document Agent](https://github.com/dotenv-uploaded/_FOLDING_)

**Team Project · Jul. 2026**<br>
Built the initial LLM-wiki platform that turns HWP, Office, and PDF files into a linked knowledge base.

### [Solar TutorBoard: AI-Powered Personalized Learning Platform](https://github.com/thddydgnl/solar-tutorboard)

**3rd MixUp AI Hackathon (Upstage × BDAI) · May 2026**<br>
Built AI-agent workflows and backend infrastructure for an educational AI platform.

### [Vehicle and Pedestrian Trajectory Forecasting on Argoverse 2](https://github.com/thddydgnl/vehicle-trajectory-prediction-av2)

**Personal Project · Mar. 2026 – Jun. 2026**<br>
Compared linear, LSTM, Transformer, and diffusion trajectory forecasters; PCA latent diffusion reached a **minFDE of 0.86** at K=16.

### Comparative Survey of RL Research for Autonomous Driving

**Independent Research Project · Sep. 2025 – Present**<br>
Analyzing **93 RL-based autonomous driving studies** and summarizing key research trends.

### [Shapley-guided Multimodal RL for Autonomous Driving](https://github.com/thddydgnl/rcs-ac-04-final)

**Faculty-Supervised Research Project · Jun. 2025 – Jun. 2026**<br>
Implemented Shapley-guided multimodal fusion using RGB, LiDAR, route, and ego-state inputs.

[Main implementation](https://github.com/thddydgnl/rcs-ac-04-final) · [Experiments](https://github.com/thddydgnl/rcs-ac-03-experiments) · [Prototype](https://github.com/thddydgnl/rcs-ac-01-prototype)

## Competitions & Hackathons

| Event | Result & Work |
| :--- | :--- |
| **2026 NASA Space Apps Challenge (Seoul)** · Nov. 2026, upcoming | Accepted as a participant in the Seoul Local Event with Team Moonkeeper. |
| **SK hynix AI Hackathon 2026** · Oct. 2026, in progress | Passed the document screening round. |
| **KRAFTON AI R&D Hackathon — Dream It Yourself, Video-Based Lightweight World-Action Model** · Oct. 2026 | Advanced to the final round. Built a world-action model that predicts cart–double-pendulum dynamics and selects the next action from the same representation. |
| **2026 Startup for All Project (모두의 창업)** · Oct. 2026 | Passed the first round. Folding Next / A desktop agent that helps public servants fill forms and draft documents from in-house files, with user-checked sources. |
| **LG Aimers 9th Cohort** · Aug. – Sep. 2026 | Advanced to the Phase 2 online hackathon (**top 20%**). Worked on predicting pitch-control success probabilities from game context, player history, and tracking data. |
| **2026 NIKL AI-Malpyung — Argumentative Writing Scoring** · Jul. – Sep. 2026 | Ranked **23rd in the preliminary round** and advanced to the **final round of 50 teams**. Developed an AI system for automated evaluation of Korean argumentative writing. |
| **2026 CODEGATE AI Startup Hackathon** · Jul. 2026 | **Finalist** · Selected as one of approximately 20 finalist teams for the offline hackathon and demo day. Participated in intensive development and validation of an AI-based startup MVP. |
| **3rd MixUp AI Hackathon (Upstage × BDAI)** · May 2026 | **Finalist** · Solar TutorBoard / Built the agent workflows and backend of a Solar Pro3-based tutoring assistant for lesson reports, payment reminders, and scheduling. |

## Awards & Scholarships

- **Academic Excellence Scholarship**, Chungbuk National University · Mar. 2026, Mar. 2024, Sep. 2023
- **Undergraduate Research Assistant Scholarship**, Chungbuk National University · Sep. 2025 – Mar. 2026

## Skills & Tools

| Area | Technologies & Methods |
| :--- | :--- |
| Programming | Python, C/C++, Java |
| ML Frameworks | PyTorch, JAX, Triton, Hugging Face Transformers, scikit-learn, Stable-Baselines3 |
| World Models & Simulation | TD-MPC2, DreamerV3, DINO-WM, MuJoCo, Meta-World, LIBERO, CARLA |
| Tools | Linux, Git, Hydra, vLLM, FastAPI |

---

[Homepage](https://thddydgnl.github.io/) · [CV](https://thddydgnl.github.io/YongHwi_Song_CV.pdf) · [thddydgnl1937@gmail.com](mailto:thddydgnl1937@gmail.com)<br>
Updated October 31, 2026.
