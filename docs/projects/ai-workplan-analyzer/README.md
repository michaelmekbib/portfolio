# AI Workplan and Data Quality Analyzer

I built an application that connects workplan findings to page-level evidence and supports consistent review of public health data-quality activities.

**Status:** Functional prototype in pilot  
**Tools:** Python, Streamlit, Azure OpenAI, Entra ID, PyMuPDF, pandas

## The challenge

Workplan review requires finding relevant evidence across lengthy documents, applying consistent criteria, and explaining how each conclusion was reached.

## My contribution

I designed and built the end-to-end workflow:

- Parse PDFs and retrieve relevant passages.
- Apply structured Azure OpenAI analysis.
- Calibrate confidence and review potential false positives.
- Capture reviewer corrections and decisions.
- Export findings to Excel, Word, PDF, and CSV.

## What it delivers

The application brings together page-linked evidence, status, strength, confidence, gaps, and summary views. Reviewers retain control of final determinations and can inspect the source material behind each finding.

[Explore the portfolio project](https://michaelmekbib.github.io/portfolio/#cdc-workplan)

[Project hub](../../../README.md) · [Portfolio](https://michaelmekbib.github.io/portfolio/) · [Contact](mailto:mikiethio@gmail.com)
