# LLM Performance Evaluation Pipeline: Local Models for Historical NLP

This repository documents the scripts and processed files created for the Master's thesis "Large Language Models as the Foundation for Adaptive Workflows in Automated Text Analysis for the Digital Humanities."


## Core Focus & Implemented Data Workflow

This project establishes a comprehensive pipeline to evaluate the performance of small, locally hosted Large Language Models (specifically Gemma and Qwen) on foundational Natural Language Processing tasks using a historical German text corpus.

Developed and executed a data pipeline for raw data extraction (XML Parsing), transformation via text cleaning and linguistic Feature Engineering, and aggregation for quantitative analysis.


## Detailed Modules & Applied Competencies

The repository is structured into four main technical modules, representing the sequential workflow of the project:

**1. Corpus Creation (`corpus_creation.ipynb`)**

XML Parsing, JSON serialization, token-level entity matching, and crucial data filtering to exclude irrelevant text segments.

**2. Text Normalization (`gemma_normalization.ipynb`)**

Orthographic Modernization of historical German text. Includes comparison with Ground Truth (GT) and preparation for external performance metrics (WER/CER).

**3. OCR Analysis (`qwen_ocr.ipynb`)**

Text extraction from image scans of the historical text using vision models (Qwen). Includes testing and comparison of different model sizes (3b, 7b).

**4. Named Entity Recognition (`gemma_information-extraction.ipynb`)**

NER for Person and Location entities. Analysis of Hits, Missing, and False Positives.
