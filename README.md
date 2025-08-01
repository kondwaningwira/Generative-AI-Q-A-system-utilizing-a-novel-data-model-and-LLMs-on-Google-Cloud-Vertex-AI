# Generative-AI-Q-A-system-utilizing-a-novel-data-model-and-LLMs-on-Google-Cloud-Vertex-AI
Project Overview
This project demonstrates a robust, enterprise-grade Q&A system built on Google Cloud's Vertex AI. By employing a Retrieval Augmented Generation (RAG) architecture, this system can accurately answer questions based on a specific corpus of documents. The architecture is designed to be scalable and flexible, utilizing a novel data model to efficiently retrieve and process relevant information.

Key Features
Retrieval Augmented Generation (RAG): The system uses a RAG approach to connect Large Language Models (LLMs) to external knowledge sources like documents and databases, enabling it to generate more accurate and informed responses.

Google Cloud Vertex AI: The project is built on Vertex AI, a platform that provides a suite of tools for building and deploying machine learning models.

Novel Data Model: The system leverages an innovative data model to manage and index document chunks for efficient retrieval, which is crucial for handling large volumes of unstructured data.

Extensive Document Processing: The system can process various document types and extract relevant text for indexing and retrieval.

Technologies Used
Google Cloud Vertex AI: For model serving, pipelines, and a managed orchestration service for RAG.

LangChain: A framework for developing applications powered by LLMs.

Google Cloud Storage (GCS): For storing the documents that the Q&A system will query.

Python Libraries: The project relies on several Python libraries, including langchain, google-cloud-aiplatform, unstructured, pdf2image, pytesseract, and pdfminer.

Getting Started
Prerequisites
A Google Cloud account.

A project with the Vertex AI and Cloud Storage APIs enabled.

Installation
Clone the repository and install the required dependencies:

Bash

git clone https://github.com/your-username/Generative-AI-Q-A-system-utilizing-a-novel-data-model-and-LLMs-on-Google-Cloud-Vertex-AI.git
cd Generative-AI-Q-A-system-utilizing-a-novel-data-model-and-LLMs-on-Google-Cloud-Vertex-AI
pip install -r requirements.txt
Setup
Configure your Google Cloud credentials.

Set up a Google Cloud Storage bucket to store your documents.

Modify the project ID and bucket name in the notebook.

Usage
Run the Jupyter notebook Group 6_3_PHASE_1,_2,_3,_and_PHASE_10_full with 20 ans (1).ipynb to see the Q&A system in action. Follow the steps to install dependencies, process your documents, and query the system.

License
(Choose your desired license, e.g., MIT, Apache 2.0)

Contact
(Provide your contact information here)
