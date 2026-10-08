# Hi, I'm Prince

Final-year Computer Science student at the University of Calgary (graduating December 2026). I build machine learning systems end to end: features and models, honest evaluation, and the APIs and infrastructure that serve them.

**Looking for:** AI/ML Engineer, ML Engineer, and Applied AI new grad roles starting in 2027.

## Featured projects

**[FraudGraph](https://github.com/PatelPrince11/FraudGraph)**: fraud detection and investigation engine
- XGBoost on 1.85M simulated card transactions with leakage-safe, time-split features: 0.973 PR-AUC vs. 0.137 for an amount-only baseline
- FastAPI + PostgreSQL scoring service with SHAP explanations, verified for training-serving feature parity
- NetworkX relationship graph for fraud rings; Docker Compose stack with GitHub Actions CI
- `Python` `XGBoost` `FastAPI` `PostgreSQL` `NetworkX` `React` `Docker`

**OpsPilot**: AI incident-investigation assistant
- RAG over PostgreSQL/pgvector with source attribution, plus a tool-calling LLM agent that queries logs, deployments, and runbooks
- Automated evaluation of retrieval quality, faithfulness, and citation accuracy; deployed on AWS
- `Python` `LLMs` `RAG` `pgvector` `FastAPI` `AWS` `Docker`

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
**GenAI:** LLMs · RAG · embeddings · pgvector · tool-calling agents
**Backend:** FastAPI · Django · PostgreSQL · SQLAlchemy · REST APIs · React
**Infra & testing:** Docker · AWS · GitHub Actions · pytest · JUnit · Linux

## Currently learning

Deep learning (Andrew Ng's specialization) and MLOps: model monitoring, drift detection, and retraining pipelines.

## Contact

[LinkedIn](https://linkedin.com/in/princepatel11) · [Email](mailto:patelprince111104@gmail.com)

Off the keyboard, I play volleyball.
