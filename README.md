# Hi, I'm Nikhil 👋

## About Me

I'm a final-year undergraduate in **Artificial Intelligence and Data Science**, focused on building ML systems that go from research-grade modeling to production deployment. My work spans reinforcement learning on graph-structured data, MLOps pipelines, and applied deep learning — with an emphasis on rigorous evaluation, not just working code.

- 🔬 Currently exploring reinforcement learning, graph neural networks, and LLM-based systems
- 🛠️ Building end-to-end ML pipelines — from data ingestion to deployment
- 📫 Reach me at: gnikhilsai7@gmail.com
- 🤝 Open to research collaborations, ML internships, and interesting technical discussions

---

## 🚀 Featured Projects

### [Targeted Epidemic Intervention via GNN-Driven Reinforcement Learning](https://github.com/nikhil550000/GNN)
A node-scoring **GCN-PPO framework** for budget-constrained epidemic mitigation on temporal contact networks, modeling quarantine and vaccination as separate learned policy heads within a custom 8-state SEIQVR Gymnasium environment.

- Achieved **47–52% infection reduction** vs. uncontrolled spread across two real-world SocioPatterns datasets (hospital N=75, school N=242)
- Validated results with **Mann-Whitney U tests** (p < 10⁻⁵) and **Cohen's d > 0.8**
- Outperformed DQN baseline by **21%** and single-intervention ablations by **37–41%**
- Two-phase training: **behavioral cloning warm-start + PPO fine-tuning**, validated across four ablation studies

**Stack:** Python, PyTorch, Gymnasium, NetworkX, NumPy, SciPy

---

### [Network Security — Phishing Website Detection](https://github.com/nikhil550000/network)
An end-to-end **MLOps pipeline** for phishing URL classification using XGBoost, achieving **98.78% F1**, **98.56% precision**, and **98.99% recall** on 11K+ samples with 30 network-level features.

- 6-stage modular pipeline (Ingestion → Validation → Transformation → Training → Evaluation → Pusher) with KS-test drift detection and automated model acceptance gating
- Experiment tracking via **MLflow** across 11+ training runs
- Weekly retraining and batch inference orchestrated via **Apache Airflow**, with **AWS S3** artifact sync
- **FastAPI** service for training/inference, containerized with **Docker**, deployed to **AWS EC2** via GitHub Actions CI/CD

**Stack:** Python, XGBoost, FastAPI, MLflow, Airflow, Docker, AWS (S3, ECR, EC2), MongoDB Atlas

---

## 🧠 Areas of Interest

`Reinforcement Learning` · `Graph Neural Networks` · `MLOps` · `Deep Learning` · `LLM Systems & RAG` · `Applied Statistics`

---

## 📊 GitHub Stats

![Nikhil's GitHub stats](https://github-readme-stats.vercel.app/api?username=nikhil550000&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nikhil550000&layout=compact&theme=radical)

---

## 🔗 Connect

- [LinkedIn](https://www.linkedin.com/in/nikhil-sai-g)
- [Email](mailto:gnikhilsai7@gmail.com)
