<div align="center">

# Dmitry Koriakin

### Machine Learning Developer

**RAG Systems** · **Search Quality** · **Biomedical AI**

[![Telegram](https://img.shields.io/badge/Telegram-%40WinerGero-2AABEE?style=flat-square&logo=telegram&logoColor=white)](https://t.me/WinerGero)
[![GitHub](https://img.shields.io/badge/GitHub-WeinerGero-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WeinerGero)
[![Focus](https://img.shields.io/badge/Focus-Applied%20ML-6C63FF?style=flat-square)](https://github.com/WeinerGero)

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

## What I build

**End-to-end ML and data systems** that turn unstructured scientific or operational data into working tools.

```text
Raw data -> Search or model -> Evaluation -> UI or API
```

</td>
<td width="50%" valign="top">

## Where I add value

- Retrieval and RAG pipelines
- Data collection and preprocessing
- Search quality and answer evaluation
- Python services and product-facing interfaces

</td>
</tr>
</table>

---

## How I approach ML projects

```mermaid
flowchart LR
    A[Data collection] --> B[Preprocessing]
    B --> C[Retrieval or modeling]
    C --> D[Evaluation]
    D --> E[Interface or API]
```

<table>
<tr>
<td align="center" width="25%">

### 01

**Data**

APIs, XML, databases, raw text

</td>
<td align="center" width="25%">

### 02

**ML layer**

Search, embeddings, ranking, models

</td>
<td align="center" width="25%">

### 03

**Validation**

Metrics, error analysis, test cases

</td>
<td align="center" width="25%">

### 04

**Product**

Streamlit, REST API, local deployment

</td>
</tr>
</table>

---

## Featured projects

<table>
<tr>
<td width="18%" align="center" valign="middle">

# 🧬

**RAG**

</td>
<td width="82%" valign="top">

### [RAG Alzheimer Assistant](https://github.com/WeinerGero/RAG-alzheimer-assistant)

Local RAG assistant for exploring PubMed literature on therapeutic targets in Alzheimer's disease.

**Pipeline**

`PubMed API` -> `Preprocessing` -> `Vector Search + BM25` -> `RRF` -> `PMID grouping` -> `Mistral-Nemo` -> `Streamlit`

**Why it is technically interesting**

- Preserves exact biomedical entities such as SNP identifiers with hybrid retrieval.
- Expands one question into macro, micro and relational search strategies.
- Removes repeated chunks from the same publication before passing evidence to the LLM.
- Produces Russian-language answers while preserving English scientific terminology.

`Python` `ChromaDB` `BM25` `RRF` `Ollama` `Mistral-Nemo` `Streamlit`

[Open repository](https://github.com/WeinerGero/RAG-alzheimer-assistant)

</td>
</tr>
</table>

<br>

<table>
<tr>
<td width="18%" align="center" valign="middle">

# ⚙️

**API**

</td>
<td width="82%" valign="top">

### [Task Tracker API](https://github.com/WeinerGero/task_tracker_API)

Python service for managing one-time and recurring tasks in a medical scheduling context.

**What it demonstrates**

- Recurring schedule modeling through templates and generated task instances.
- PostgreSQL migrations and JSONB recurrence configuration.
- Docker-based local launch, Swagger documentation and automated tests.
- Layered backend structure: API, services, repositories, schemas and domain utilities.

`Python` `PostgreSQL` `Alembic` `Docker` `pytest` `REST API`

[Open repository](https://github.com/WeinerGero/task_tracker_API)

</td>
</tr>
</table>

---

## Technical toolkit

<table>
<tr>
<td width="33%" valign="top">

### Data and ML

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFCC4D?style=flat-square&logo=huggingface&logoColor=black)

</td>
<td width="33%" valign="top">

### RAG and search

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4B5563?style=flat-square)
![BM25](https://img.shields.io/badge/BM25-5A67D8?style=flat-square)
![RRF](https://img.shields.io/badge/RRF-805AD5?style=flat-square)

</td>
<td width="33%" valign="top">

### Engineering

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</td>
</tr>
</table>

---

## Current direction

<table>
<tr>
<td width="33%" align="center">

### Improve retrieval

Hybrid search, reranking and evidence selection.

</td>
<td width="33%" align="center">

### Build applied systems

From raw data to a usable interface or API.

</td>
<td width="33%" align="center">

### Join an ML team

Open to Junior ML Engineer, Data Scientist and AI Engineer roles.

</td>
</tr>
</table>

---

<div align="center">

### Open to collaboration on applied ML, RAG and biomedical AI projects.

</div>
