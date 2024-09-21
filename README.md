# **Navigating Academic Standards with AGGA: A Dataset of Academic Guidelines for Generative AI and Large Language Models**

## **Project Overview**
This repository contains the data, code, and results associated with the **AGGA (Academic Guidelines for Generative AIs)** project, which analyzes 80 academic guidelines related to Generative AI (GAI) and Large Language Models (LLMs) from institutions across six continents. This study aims to provide insight into how universities around the globe are adapting to and regulating the use of GAI tools like ChatGPT in academic settings.

The repository includes:
- **Text Analysis**: Frequency analysis of keywords from academic guidelines, broken down by continent.
- **Network Graphs**: Visualizations of relationships between major keywords for academic guidelines, categorized by five types.

This project supports Natural Language Processing (NLP) tasks like model synthesis, ambiguity detection, and requirements engineering.

## **Repository Structure**

```plaintext
Navigating Academic Standards with AGGA/
│
├── data/
│   ├── raw/
│   │   ├── AGGA_Africa.docx
│   │   ├── AGGA_Asia.docx
│   │   ├── ... (other continents' raw DOCX files)
│   ├── processed/
│       ├── AGGA_Africa.txt
│       ├── AGGA_Asia.txt
│       ├── ... (processed text files for each continent)
│
├── figures/
│   ├── frequency_africa.png
│   ├── frequency_asia.png
│   ├── network_graph_keywords.png
│
├── notebooks/
│   ├── text_analysis.ipynb
│   ├── network_graph.ipynb
│
├── README.md
├── AGGA.xlsx
├── AGGA Dataset of Academic Guidelines for G...
├── AGGA_Analysis.ipynb
├── requirements.txt
