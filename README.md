# Steps AI NLP Engineer Application - Take-Home Assessment

# Project Description
This project involves developing a system capable of web crawling, creating a vector database using MILVUS, and developing a question-answering system using a Language Model (LLM). The main objectives are to assess skills in data retrieval, data processing, vector database creation, and natural language processing.

# 1. Web Crawling
Objective: 
Develop a web crawler to scrape data from the provided website and its sub-links up to a depth of 5 levels.
Website: NVIDIA CUDA Documentation
Requirements:
Scrape data from the main link and sub-links up to 5 levels deep.
Identify and scrape data from both parent links and corresponding sub-links.

# 2. Data Chunking and Vector Database Creation
Objective: Chunk the scraped data based on sentence/topic similarity and create a vector database.
Requirements:
Implement advanced chunking techniques considering similarity and topic relevance.
Convert the chunks into embedding vectors.
Create a vector database using MILVUS and store embedding vectors with HNSW indexing.
Store relevant metadata, such as web-links, with the chunks in the vector database.

# 3. Retrieval and Re-ranking
Objective: Enhance the data retrieval process and re-rank retrieved data.
Requirements:
Implement query expansion techniques.
Employ hybrid retrieval methods (BM25 and BERT/bi-encoder-based methods like DPR and spider).
Re-rank the retrieved data based on relevance and similarity to the query.

# 4. Question Answering
Objective: Use an LLM to generate accurate and relevant answers based on retrieved and re-ranked data.
Requirements:
Choose an LLM to generate answers.
Ensure the LLM generates accurate and relevant answers from the retrieved data.

# 5. User Interface (Optional)
Objective: Create a user interface to demonstrate the system's functionality.
Frameworks: Streamlit or Gradio.
Requirements:
Allow users to input queries.
Display retrieved answers in a user-friendly manner.
