## About

A bibliometric analysis of **Vision Language Models (VLMs)** using the `bibliometrix` R package (v4.x), covering **998 documents (2017–2026)** sourced from the **OpenAlex** repository and visualized via **Biblioshiny**.

---

## 📋 Description

This repository contains the R code and analysis pipeline for a comprehensive bibliometric study of Vision Language Models — AI systems capable of processing both visual and textual data.

The analysis covers:
- 📈 **Performance analysis** — annual publication trends (1 paper in 2017 → 443 in 2024)
- 🔗 **Citation analysis** — citation peak in 2021 driven by transformer-based architectures
- 👥 **Co-authorship network mapping** — country and institutional collaborations
- 🔑 **Keyword co-occurrence analysis** — spanning computer science, cognitive psychology, and linguistics
- 🗺️ **Thematic mapping** — intellectual structure and temporal evolution of VLM research

**Key findings:**
- 🇨🇳 🇺🇸 China and the U.S. dominate global output
- 🏛️ Stanford University and Google lead institutionally
- 📄 Most-cited work: *Swin Transformer* by Ze Liu (2021) with **28,540 citations**
- 🚀 Post-2024 surge in applied VLMs for remote sensing and machine vision

---

## 🛠️ Tools & Packages

| Tool | Purpose |
|------|---------|
| `bibliometrix` (v4.x) | Core bibliometric analysis |
| `Biblioshiny` | Interactive visualization |
| `OpenAlex` | Data source (998 documents) |
| `R / RStudio` | Analysis environment |

---


## 📥 Data Collection

Data was collected directly within **Biblioshiny** using the integrated OpenAlex API. Follow the steps below to reproduce the data collection process:

1. Launch Biblioshiny and navigate to **Data → API → OpenAlex** from the left sidebar
2. In the **OpenAlex Data Collection** page, enter the following:

   - **Title:** `Vision Language Model`
   - **Date Range:** 2017 – 2026

3. Under **Advanced Features**, configure:

   - **Language:** English
   - **Max Records:** 1000

4. Click the **Search** button (bottom right of the title field) to retrieve the dataset

> This query returned **998 documents** spanning from 2017 to 2026, which form the basis of all analyses in this study.




---
