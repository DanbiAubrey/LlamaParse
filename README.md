# PDF to Markdown Converter for RAG Applications

This repository contains a Jupyter Notebook (`.ipynb`) that converts PDF files into Markdown (`.md`) format to prepare documents for use in **Retrieval-Augmented Generation (RAG)** pipelines.

## 📘 Overview

RAG-based applications often benefit from clean, structured, and lightweight textual input. PDF documents, however, are typically rich in layout and formatting, making them suboptimal for such pipelines. This notebook streamlines the conversion process by:

- Extracting text content from PDF files
- Cleaning and formatting the output
- Exporting the content as a Markdown file

## 🧠 Use Cases

- Preparing long-form documents for ingestion into RAG pipelines
- Converting academic papers, manuals, or documentation for use with vector databases
- Creating lightweight, readable text sources for AI-driven question-answering systems

## 📂 Files

- `pdf_to_markdown.ipynb`: Main notebook to load PDF files and output clean Markdown
- `sample_input/`: (Optional) Example PDFs to test
- `output/`: (Optional) Directory where converted Markdown files will be saved

## ✅ Features

- PDF text extraction
- Markdown formatting (headers, lists, paragraphs)
- Optional support for chunking or section tagging

## 🛠 Requirements

Install the necessary dependencies:

```bash
pip install -r requirements.txt
