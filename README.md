# Hi, I'm Too Lik Heng 👋

Computer Science graduate from Asia Pacific University of Technology & Innovation (APU), based in Kuala Lumpur. I build things end to end: provision them, ship them through CI/CD, monitor them, and measure that they work. I'm looking for roles in **DevOps, cloud and data**.

- 🎓 BSc (Hons) Computer Science, APU (2023–2026)
- ☁️ AWS Certified Cloud Practitioner
- 💼 Data Analytics Intern at YTL Construction (2025): Power BI dashboards, Power Automate workflows and PowerShell automation for HR
- 🗣️ English, Malay, Mandarin, Cantonese

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Too%20Lik%20Heng-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/too-lik-heng-7a27902a2)

## 🛠️ Tech I work with

- **DevOps & cloud:** Docker, Kubernetes (k3s / k3d), Ansible, GitHub Actions, GHCR, Trivy, Prometheus, Grafana, AWS (Bedrock, S3, DynamoDB)
- **Backend:** Python, FastAPI, PostgreSQL + pgvector, TypeScript, Next.js
- **AI / ML:** RAG, Ollama, scikit-learn, XGBoost, LightGBM, SHAP, Pandas, NumPy
- **Data & BI:** SQL, R, Power BI (DAX, Power Query), Power Apps, Power Automate, Excel

## 🚀 Featured projects

### [Self-hosted DevOps platform](https://github.com/toolikheng/devops-platform)
A small platform run end to end on one machine. Ansible provisions three nodes, a FastAPI service is built, scanned and deployed to a k3d cluster, Prometheus and Grafana monitor it, restic backs it up, and GitHub Actions gates every push. Every claim in the README was checked by running it, including zero failed requests during a rolling restart and a restore test that catches a broken restore.

`Ansible` `Docker` `Kubernetes` `GitHub Actions` `Trivy` `Prometheus` `Grafana`

### [PolicyPal: AI HR policy assistant](https://github.com/toolikheng/policypal-hr-rag)
A RAG assistant that answers HR policy questions with section-level citations, and refuses instead of guessing when the policies don't cover a question. On a 52-question golden set it finds the right section in the top 5 every time (100% hit@5, 87.5% hit@1). Runs locally as 4 Docker Compose services, with CI/CD publishing images to GHCR.

`Python` `FastAPI` `PostgreSQL/pgvector` `Ollama` `Streamlit` `Docker`

### [Predicting at-risk students](https://github.com/toolikheng/Predicting-at-risk-student-app)
An early-warning model with 96.7% accuracy and 95.4% recall on at-risk students, plus a Streamlit dashboard that uses SHAP to show educators why each student was flagged.

`XGBoost` `LightGBM` `scikit-learn` `SHAP` `Streamlit`

### [MedPal: AI medical document assistant](https://github.com/TeeHaoBin/MedPal-Great-Malaysia-AI-Hackathon)
Great Malaysia AI Hackathon team project: a chat assistant for plain-language questions across medical PDFs. I built the Next.js chat interface and the backend APIs, using AWS Bedrock, S3 and DynamoDB.

`Next.js` `AWS Bedrock` `S3` `DynamoDB`

### More
- [Data analyst portfolio](https://github.com/toolikheng/PortfolioProject): SQL, Excel and R analysis projects
