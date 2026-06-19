<div align="center">

# Dmitry Koriakin

### Machine Learning Developer

**RAG Systems** · **Search Quality** · **Biomedical AI** · **Python Services**

[![Telegram](https://img.shields.io/badge/Telegram-%40WinerGero-2AABEE?style=flat-square&logo=telegram&logoColor=white)](https://t.me/WinerGero)
[![GitHub](https://img.shields.io/badge/GitHub-WeinerGero-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WeinerGero)
[![Focus](https://img.shields.io/badge/Focus-Applied%20ML-6C63FF?style=flat-square)](https://github.com/WeinerGero)

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

## What I build

End-to-end ML and data systems that turn raw scientific or operational data into usable tools.

```text
Data -> Retrieval or model -> Evaluation -> Interface or API
```

</td>
<td width="50%" valign="top">

## What I focus on

- RAG and information retrieval
- Biomedical literature mining
- Data collection and preprocessing
- Search quality and answer evaluation
- Python APIs and local deployment

</td>
</tr>
</table>

---

## Portfolio map

```mermaid
flowchart LR
    A[Data sources] --> B[Preprocessing]
    B --> C[Search or model]
    C --> D[Evaluation]
    D --> E[User interface or API]
```

<table>
<tr>
<td align="center" width="25%">

### 01

**Data**

APIs, XML, databases and raw text

</td>
<td align="center" width="25%">

### 02

**ML layer**

Embeddings, retrieval, ranking and LLMs

</td>
<td align="center" width="25%">

### 03

**Validation**

Metrics, error analysis and test cases

</td>
<td align="center" width="25%">

### 04

**Product**

Streamlit, REST API and local deployment

</td>
</tr>
</table>

---

## Featured projects

<table>
<tr>
<td width="18%" align="center" valign="middle">

# 🧬

[![RAG](https://img.shields.io/badge/RAG-6C63FF?style=flat-square)](https://github.com/WeinerGero/RAG-alzheimer-assistant)
[![Biomedical AI](https://img.shields.io/badge/Biomedical%20AI-2F855A?style=flat-square)](https://github.com/WeinerGero/RAG-alzheimer-assistant)

</td>
<td width="82%" valign="top">

### [RAG Alzheimer Assistant](https://github.com/WeinerGero/RAG-alzheimer-assistant)

Local RAG assistant for searching PubMed literature on therapeutic targets in Alzheimer's disease.

```text
PubMed API -> XML preprocessing -> Vector Search + BM25 -> RRF
-> PMID grouping -> Mistral-Nemo via Ollama -> Streamlit
```

**What I solved**

- Combined semantic retrieval with BM25 to keep exact biomedical entities, including SNP identifiers, in the search results.
- Expanded each question into macro, micro and relational search strategies.
- Grouped retrieved chunks by PMID before generation to avoid filling the context window with one publication.
- Configured generation in Russian while keeping scientific entities and terminology in English.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![PubMed](https://img.shields.io/badge/PubMed-Entrez%20API-326599?style=flat-square)](https://pubmed.ncbi.nlm.nih.gov/)
[![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20store-4B5563?style=flat-square)](https://www.trychroma.com/)
[![BM25](https://img.shields.io/badge/BM25-Lexical%20search-5A67D8?style=flat-square)](https://github.com/WeinerGero/RAG-alzheimer-assistant)
[![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)](https://ollama.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io/)

[Open repository](https://github.com/WeinerGero/RAG-alzheimer-assistant)

</td>
</tr>
</table>

<br>

<table>
<tr>
<td width="18%" align="center" valign="middle">

# ⚙️

[![Backend](https://img.shields.io/badge/Backend-2563EB?style=flat-square)](https://github.com/WeinerGero/task_tracker_API)
[![Medical scheduling](https://img.shields.io/badge/Medical%20scheduling-0E7490?style=flat-square)](https://github.com/WeinerGero/task_tracker_API)

</td>
<td width="82%" valign="top">

### [Task Tracker API](https://github.com/WeinerGero/task_tracker_API)

Python microservice for managing one-time and recurring tasks in a medical scheduling context.

```text
Recurrence rules -> Templates -> Generated task instances
-> PostgreSQL -> REST API -> Swagger and tests
```

**What I solved**

- Modeled recurring schedules through separate templates and generated task instances.
- Handled dates that do not exist in shorter months by moving a task to the last day of the month.
- Stored variable recurrence rules in JSONB instead of adding sparse database columns.
- Added generation limits, date-range filtering, Docker-based local launch and automated tests.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Alembic](https://img.shields.io/badge/Alembic-Database%20migrations-6B7280?style=flat-square)](https://alembic.sqlalchemy.org/)
[![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)](https://pytest.org/)
[![Swagger](https://img.shields.io/badge/Swagger-API%20docs-85EA2D?style=flat-square&logo=swagger&logoColor=black)](https://github.com/WeinerGero/task_tracker_API)

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

![PubMed](https://img.shields.io/badge/PubMed-Entrez%20API-326599?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4B5563?style=flat-square)
![BM25](https://img.shields.io/badge/BM25-5A67D8?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

</td>
<td width="33%" valign="top">

### Engineering

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6B7280?style=flat-square)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

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
