# AI-Powered Fundamental Stock Analysis using RAG

## 1. Project Overview

This project develops an AI-powered financial analysis system using Retrieval-Augmented Generation (RAG) to analyze the fundamental financial performance of **Reliance Industries Limited (RELIANCE.NS)**.

The system retrieves relevant financial information using semantic search with FAISS and generates natural-language answers using Google's Gemini LLM.

The objective is to provide relevant, context-based financial insights while reducing unsupported or fabricated responses.

## 2. Business Problem

Investors and financial analysts often need to examine multiple financial indicators to understand a company's financial health.

Manually reviewing financial statements, financial ratios, and historical performance can be time-consuming.

This project addresses this challenge by developing a question-answering system that allows users to ask financial questions in natural language and receive answers based on retrieved financial information.

## 3. Tools and Technologies

- **Programming Language:** Python
- **Platform:** Google Colab
- **Financial Data Source:** Yahoo Finance (yfinance)
- **Vector Database:** FAISS
- **Large Language Model:** Google Gemini
- **Technique:** Retrieval-Augmented Generation (RAG)
- **Concepts:** Data Extraction, Text Embeddings, Semantic Search, Financial Analysis

## 4. Project Workflow

1. **Financial Data Extraction:** Retrieved fundamental financial information for Reliance Industries Limited using Yahoo Finance.
2. **Data Preparation:** Extracted and organized financial statements, financial ratios, and valuation metrics.
3. **Document Creation:** Converted financial information into structured documents suitable for retrieval.
4. **Text Embeddings:** Generated embeddings to represent financial documents numerically.
5. **Vector Database:** Created a FAISS index to store and retrieve relevant financial information.
6. **Semantic Search:** Retrieved relevant financial documents based on users' natural-language questions.
7. **Answer Generation:** Integrated retrieved information with Google's Gemini model to generate context-based financial answers.
8. **Evaluation:** Tested the system using multiple financial questions to evaluate generation success and retrieval relevance.

## 5. Financial Analysis Features

The system supports questions related to:

- Revenue and revenue growth
- Profitability and net income
- Earnings Per Share (EPS)
- Assets and liabilities
- Debt and cash position
- Operating cash flow and free cash flow
- Financial ratios
- Historical financial performance
- Valuation metrics, including trailing P/E and forward P/E
- Financial strengths and potential risks

## 6. Evaluation and Results

The system was tested using multiple natural-language financial questions.

Evaluation focused on:
- Retrieval of relevant financial documents.
- Relevance of retrieved information to the questions.
- Successful generation of responses using Gemini.
- Grounding generated responses in the retrieved financial knowledge base.

**Evaluation Results:**

- Total evaluation questions: 5
- Successful answer generations: 5
- Generation success rate: 100%

The evaluation demonstrated that the system successfully generated responses for all five test questions.

## 7. Key Learnings

Through this project, I gained practical experience in:

- Extracting financial data using Python and Yahoo Finance.
- Preparing structured financial knowledge documents.
- Implementing semantic search using FAISS.
- Understanding text embeddings and vector databases.
- Integrating Google's Gemini API with a RAG pipeline.
- Evaluating AI-generated responses using retrieved financial information.
- Building an end-to-end AI-powered financial question-answering application.

## 8. Limitations

- The analysis is dependent on the availability and accuracy of financial data from Yahoo Finance.
- The project focuses on Reliance Industries Limited as the primary case study.
- Generated responses depend on the relevance and completeness of retrieved documents.
- The evaluation covers a limited set of five test questions and does not establish complete factual accuracy.
- This project is intended for educational and analytical purposes and should not be considered investment advice.

## 9. Conclusion

This project demonstrates how Retrieval-Augmented Generation can be applied to financial fundamental analysis.

By combining Python, FAISS, semantic search, and Google's Gemini model, the system provides a natural-language interface for exploring company financial information.

The project highlights the practical application of Generative AI, vector databases, and financial data analytics in building an intelligent financial question-answering system.

---

**Author:** Arati Joshi

**GitHub:** [Arati-Joshi-Data](https://github.com/Arati-Joshi-Data)
