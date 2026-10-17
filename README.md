# Hi, I'm Prince

Final-year Computer Science student at the University of Calgary (graduating December 2026). I build machine learning systems end to end: features and models, honest evaluation, and the APIs and infrastructure that serve them.

**Portfolio:** [princepatel-portfolio.vercel.app](https://princepatel-portfolio.vercel.app) · **GitHub:** [PatelPrince11](https://github.com/PatelPrince11) · **LinkedIn:** [princepatel11](https://linkedin.com/in/princepatel11) · **Email:** [patelprince111104@gmail.com](mailto:patelprince111104@gmail.com)

**Looking for:** AI/ML Engineer, ML Engineer, and Applied AI new grad roles starting in 2027.

## Featured projects

**[FraudGraph](https://github.com/PatelPrince11/FraudGraph)**: fraud detection and investigation engine
- XGBoost on 1.85M simulated card transactions with leakage-safe, time-split features: 0.973 PR-AUC vs. 0.137 for an amount-only baseline
- FastAPI + PostgreSQL scoring service with SHAP explanations, verified for training-serving feature parity
- NetworkX relationship graph for fraud rings; Docker Compose stack with GitHub Actions CI
- `Python` `XGBoost` `FastAPI` `PostgreSQL` `NetworkX` `React` `Docker`

**[OpsPilot](https://github.com/PatelPrince11/opspilot)**: AI incident-investigation agent ([demo video](https://youtu.be/k9yHhlwRVRQ))
- Hybrid RAG over PostgreSQL/pgvector with source attribution; hybrid retrieval raised MRR from 0.757 to 0.839 on 100 held-out questions (synthetic corpus)
- LangGraph agent with 5 read-only tools (incident history, runbooks, logs, service health); a citation check failed 25.6% of first-draft claims, fixed by redraft or drop
- Evaluation on a frozen test split; layered prompt-injection defenses cut attack success from 11/45 to 2/45; Docker Compose + Nginx on AWS EC2, run on demand
- `Python` `LLMs` `RAG` `LangGraph` `pgvector` `FastAPI` `AWS` `Docker`

**[BrickByByte](https://brickbybyte.vercel.app)**: real estate ML app (live)
- XGBoost and scikit-learn models served through a FastAPI API, React/TypeScript frontend
- Diagnosed and fixed a production train/serve skew caused by a scikit-learn version mismatch
- `Python` `XGBoost` `scikit-learn` `FastAPI` `React` `Render` `Vercel`

**[notMNIST Vision](https://github.com/PatelPrince11/notmnist-vision)**: image classification with leak-free evaluation
- Found 513 of 10,000 test images duplicated in training and rebuilt evaluation on a de-duplicated split; a 289K-parameter PyTorch CNN reached 96.72% vs. 92.82% for the Keras MLP baseline
- Fine-tuned ResNet-18 against a from-scratch control: no significant gain from ImageNet pretraining (p = 0.50)
- Fixed a preprocessing mismatch that cut inference accuracy to 82.6%; FastAPI service in Docker with 51 pytest tests
- `Python` `PyTorch` `scikit-learn` `FastAPI` `Docker` `pytest`

## Tech stack

**Languages:** Python · SQL · TypeScript · Java · C/C++
**ML & data:** XGBoost · scikit-learn · PyTorch · TensorFlow · pandas · NumPy · SHAP · NetworkX
**GenAI:** LLMs · RAG · embeddings · pgvector · LangGraph · tool-calling agents
**Backend:** FastAPI · Django · PostgreSQL · SQLAlchemy · REST APIs · React
**Infra & testing:** Docker · AWS · GitHub Actions · pytest · JUnit · Linux

## Currently learning

Deep learning (Andrew Ng's specialization) and MLOps: model monitoring, drift detection, and retraining pipelines.

## Contact

Off the keyboard, I play volleyball.
