# Standalone examples

This directory contains standalone examples which has their own seperate end to end workflow like UI, deployment methodologies and tools showcasing different usecases.


## RAG in NVDIA  (5 minutes example)

Nvidia AI playground -> (https://catalog.ngc.nvidia.com/ai-foundation-models)
Connects to Langchain & uses Streamlit


- NVIDIA_API_KEY. details [here](../docs/rag/aiplayground.md#prepare-the-environment) to get this. Update it in the code.


- Finally to test the deployed example, goto the URL `http://<host_ip>:8501` in a web browser. Click on `browse files` and select your knowledge source. After selecting click on `Upload!` button to complete the ingestion process.


**This codebase is from the NVIDIA git repo to deploy RAG directly using NVIDA models**