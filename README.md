<div align="center">

# Nikhil Sai Goori

### Software Engineer · Backend Systems · Applied AI

I build reliable backend services and AI systems—from API contracts and data pipelines to retrieval, evaluation, and deployment.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikhil-sai-g)
[![Email](https://img.shields.io/badge/Email-Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gnikhilsai7@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nikhil550000?tab=followers)

</div>

## About

I'm a final-year Artificial Intelligence and Data Science undergraduate who approaches AI projects as software engineering problems. My strongest work sits where backend systems meet applied AI: designing APIs, structuring data flows, validating inputs, separating components, testing critical paths, and shipping services that can be operated beyond a notebook.

Most of my backend work is in Python and FastAPI, supported by SQL or MongoDB, containerized delivery, CI, and cloud infrastructure. On the AI side, I work with hybrid retrieval, reranking, citation validation, model training, and evaluation. I care about clean interfaces, reproducible results, and making system tradeoffs visible.

<table>
<tr>
<td width="33%" valign="top">
<h3>Backend systems</h3>
<p>API design, validation, data access, service boundaries, and scheduled workflows.</p>
</td>
<td width="33%" valign="top">
<h3>AI systems</h3>
<p>Retrieval, reranking, grounded generation, model evaluation, and observability.</p>
</td>
<td width="33%" valign="top">
<h3>Engineering practice</h3>
<p>Modular design, automated tests, CI gates, containerization, and deployment.</p>
</td>
</tr>
</table>

## Selected systems

<table>
<tr>
<td width="50%" valign="top">

### [RAG Scholar](https://github.com/nikhil550000/Hybrid-Rag)

A FastAPI-backed research assistant for querying ten machine-learning papers with hybrid retrieval and verified citations.

- Combines vector search and BM25, then applies cross-encoder reranking
- Keeps citation validation separate from answer generation
- Includes offline unit tests, observability, and an evaluation gate in CI
- Reached **0.974 faithfulness** and **0.928 citation accuracy** on a 100-question offline evaluation

<sub>Python · FastAPI · ChromaDB · BM25 · Sentence Transformers · DeepEval · Langfuse</sub>

</td>
<td width="50%" valign="top">

### [Network Security Pipeline](https://github.com/nikhil550000/Network_Security)

An API-driven ML system for phishing classification, repeatable training, evaluation, batch inference, and deployment.

- Uses a group-aware split to keep duplicate feature vectors out of both train and test sets
- Keeps preprocessing and inference behavior consistent through a packaged model pipeline
- Adds schema validation, model acceptance checks, scheduled jobs, and offline tests
- Reached **95.97% phishing-class F1** on a held-out group-aware test set

<sub>Python · FastAPI · XGBoost · Airflow · MLflow · Docker · GitHub Actions · AWS</sub>

</td>
</tr>
</table>

## Core stack

| Area | Primary tools |
| --- | --- |
| **Backend** | Python · FastAPI · Pydantic · REST APIs · SQL |
| **Data and retrieval** | MongoDB · MySQL · ChromaDB · BM25 · vector search |
| **AI and machine learning** | PyTorch · scikit-learn · XGBoost · RAG · LLM evaluation |
| **Systems and delivery** | Docker · GitHub Actions · AWS · Airflow · MLflow |
| **Quality and collaboration** | pytest · Ruff · Git · schema validation · evaluation gates |

## How I approach engineering

- Define clear contracts between the API, pipeline, storage, and model layers.
- Keep core behavior testable without requiring live models or cloud credentials.
- Treat evaluation as part of development, with metrics tied to a dataset and test context.
- Document limitations and operational tradeoffs instead of presenting a demo as a finished product.

## GitHub activity

<div align="center">

<img width="98%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nikhil550000&theme=github_dark" alt="Nikhil's GitHub contribution history" />

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=nikhil550000&theme=github_dark" alt="Nikhil's GitHub statistics" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=nikhil550000&theme=github_dark" alt="Nikhil's repositories by language" />

</div>

<sub>Activity cards are generated from public GitHub data. Repository-language statistics show code distribution, not proficiency.</sub>

## Currently

I'm open to internships and upcoming entry-level roles in **backend engineering, software engineering, and AI/ML infrastructure**. I'm especially interested in teams building API platforms, data-intensive services, ML tooling, or AI products that need strong engineering underneath.

Reach me on [LinkedIn](https://www.linkedin.com/in/nikhil-sai-g) or by [email](mailto:gnikhilsai7@gmail.com).
