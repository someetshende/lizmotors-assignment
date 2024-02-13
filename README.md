# lizmotors-assignment
# Web Scraping and Data Analysis Project

This project involves web scraping data and analyzing it to generate insights from website's data scrapped using LangChain, Faiss, and OpenAI's GPT-3.5.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data Loading](#data-loading)
- [Text Processing](#text-processing)
- [Vectorization and Embeddings](#vectorization-and-embeddings)
- [Question-Answering](#question-answering)
- [Persistence](#persistence)
- [Tech Stacks Used](#tech-stacks-used)
- [License](#license)

## Introduction

This project aims to scrape data from various sources, process the text, and utilize LangChain, Faiss, and OpenAI's GPT-3.5 to perform question-answering and generate valuable insights.

## Installation

## Usage
To use the project, follow these steps:

Install the required libraries as mentioned in the installation section.
Execute the provided code snippets to load, process, and analyze data.
Customize the data sources and analysis parameters based on your requirements. IPYNB file is provided with the outcome and code.

```bash
!pip install langchain
!pip install faiss-cpu
!pip install openai
!pip install unstructured
!pip install chromadb
```
## Data Loading
The project supports loading data from various URLs. Update the urls list in the provided code with the desired sources.

## Text Processing
Text processing involves cleaning and tokenization. Customize the text_splitter according to your specific requirements.

## Vectorization and Embeddings
Vectorization and embeddings are handled using LangChain's Chroma and OpenAI's GPT-3.5 embeddings. The vectorDB component manages the persistence and retrieval of vectorized data.

## Question-Answering
The project utilizes OpenAI's GPT-3.5 for question-answering. The RetrievalQAWithSourcesChain combines LangChain's retriever with the language model for effective QA.

## Persistence
Data and models can be persisted using Chroma and other storage mechanisms. Update the persist_directory as needed.

## Tech Stacks Used
1.LangChain
2.Faiss
3.OpenAI GPT-3.5
4.Unstructured
5.ChromaDB

