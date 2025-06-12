# 🚀 Unstract by Zipstack

**No‑code LLM Platform to launch APIs & ETL Pipelines to structure unstructured documents**

[![License: AGPL-3.0](https://img.shields.io/github/license/Zipstack/unstract)]()
[![Docker Pulls](https://img.shields.io/docker/pulls/unstract/backend)]()

A powerful open-source, **no-code** platform that automates extraction of unstructured data from long, complex documents—powered by LLMs and human-in-the-loop workflows.

---

## 🧩 Why Unstract?

- **No-code Prompt Studio**: Design and iteratively refine prompts, schemas, sample docs, and view multi-LLM outputs & cost comparisons—all from a single UI.
- **Flexible deployment**: Support unstructured-data API endpoints and ETL pipelines that integrate with S3, GCS, databases, and warehousing systems.
- **Feed documents to LLMs with ease**: [LLMWhisperer](https://docs.unstract.com/llmwhisperer/) adapts raw OCR or native text (including handwritten forms, checkboxes, tables) into LLM-friendly formats.
- **Performance & reliability**: Leverage advanced techniques like **LLMChallenge**, **SinglePass Extraction**, and **Summarized Extraction** to improve accuracy and reduce latency & costs (available in [Unstract Enterprise](https://docs.unstract.com/unstract/cloud_edition/)).

---

## 🛠️ Get Started

### Requirements

- 8 GB RAM
- Docker & Docker Compose
- Git (for cloning)
- Linux or macOS (Intel or Apple Silicon)

### Quick Start (Open Source edition)

```bash
git clone https://github.com/Zipstack/unstract.git
cd unstract
./run-platform.sh
