### Hi, I'm Rakesh Thalaboina 👋
B.Tech CS · **LLM fine-tuning · multi-agent systems · RAG · applied ML**

I build models end to end — curate the data, fine-tune, evaluate, and ship locally/on-prem.

---

## 🔥 Featured Work

### 🤖 [Autonomous AI Warranty Processing](https://github.com/Rakesh-ai-ml/Warranty-Claim-Assistant) — Multimodal Multi-Agent System
6-agent CrewAI workflow (intake → validation → vision inspection → claim processing → resolution → comms) with DB-lookup tools.
- **On-prem multimodal vision:** local Ollama `qwen3-vl:2b` returns structured JSON damage verdicts — zero API cost, no cloud
- **ETL → MySQL:** REST ingestion, Pandas cleaning, bulk `LOAD DATA LOCAL INFILE`; autonomous eligibility checks + DB writes
- **Observability:** W&B Weave tracing of agent steps and tool calls; Streamlit UI

`Python` `CrewAI` `Ollama` `MySQL` `Pandas` `W&B Weave`

### 🧠 [Qwen3-4B QLoRA Fine-Tuning](https://github.com/Rakesh-ai-ml/qwe3_class12_physics_qa_sft) — Physics Education Assistant
QLoRA (4-bit NF4) on a curated 4,715-pair instruction dataset — **6.16% trainable params**. → [adapter on HF Hub](https://huggingface.co/Rakesh7n/Qwen3_4B_NCRT_Physics_12th_Finetuned)
- Unsloth + PyTorch + LoRA adapters for memory-efficient single-GPU training
- W&B loss tracking, hyperparameter logging, artifact versioning; adapter published to HF Hub

`PyTorch` `Hugging Face` `PEFT` `QLoRA` `Unsloth` `W&B`

---

## 📚 More
- **[History-Rag](https://github.com/Rakesh-ai-ml/History-Rag)** — RAG over historical documents
- **[Bankruptcy Prediction](https://bankruptcy-prediction.duckdns.org/)** — CatBoost + Optuna + MLflow, FastAPI + Docker on EC2 (ROC-AUC 0.84) · [live demo](https://bankruptcy-prediction.duckdns.org/)
- **[Churn Classification](https://github.com/Rakesh-ai-ml/Chrun-Classification)** — end-to-end tabular ML

---

**Stack:** Python · PyTorch · HF (Transformers, PEFT) · Unsloth · CrewAI · LangChain · Ollama · RAG · SQL · Docker · FastAPI · MLflow · W&B

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rakesh-thalaboina/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Rakesh7n-FFD21E)](https://huggingface.co/Rakesh7n)
[![Email](https://img.shields.io/badge/Email-rakesh.thalaboina@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:rakesh.thalaboina@gmail.com)
