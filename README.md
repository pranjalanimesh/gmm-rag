# Advanced RAG System with GMM Clustering and RAPTOR-based Approach

This Jupyter notebook (`rag_system.ipynb`) implements an advanced Retrieval-Augmented Generation (RAG) system using innovative techniques for document processing, indexing, retrieval, and generation.

## Key Features

1. **Document Chunking and Indexing**
   - Utilizes Gaussian Mixture Model (GMM) clustering for intelligent document segmentation
   - Implements RAPTOR (Recursive Abstraction of Passages for Textual Organization and Retrieval) for hierarchical document structuring

2. **Retrieval Mechanism**
   - Employs cosine similarity for efficient and accurate document retrieval

3. **Generation Approaches**
   - Query Variant Method: Generates multiple variations of the original query to expand the search space
   - Query Splitting Method: Breaks down complex queries into subqueries for comprehensive information retrieval
   - Context Compression Method: Condenses retrieved contexts for more focused and relevant generation

## Prerequisites

- Python 3.8+
- Jupyter Notebook
- Required libraries (list provided in `requirements.txt`)

## Setup and Usage

1. Clone this repository
2. Install required dependencies:
3. Open `rag_system.ipynb` in Jupyter Notebook
4. Follow the step-by-step instructions within the notebook

## System Components

### 1. Document Processing
- Custom PDF processor made using - text(PYMuPDF), tables(tabula), images(GLM-4vq)
- GMM Clustering: Segments documents into semantically coherent chunks
- RAPTOR: Creates a hierarchical structure of document segments for efficient retrieval

### 2. Indexing
- Builds an inverted index using the processed document chunks
- Stores document vectors for quick similarity comparisons

### 3. Retrieval
- Implements cosine similarity to find the most relevant document chunks for a given query

### 4. Generation
- Query Splitting: Divides complex queries into manageable subqueries
- Query Variant Generation: Creates alternative formulations of the original query
- Context Compression: Summarizes and compresses retrieved contexts for focused generation

## Performance and Evaluation

The notebook can be extended to include ragas evaluation metrics for assessing the system's performance and effectiveness.

## Customization

Users can modify various parameters within the notebook to optimize the system for specific use cases or datasets.

## Contributing

Feel free to fork this repository and submit pull requests for any enhancements or bug fixes.
