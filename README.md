Academic Search Engine for Research Papers  

This repository implements a custom academic search engine aimed at enhancing the retrieval of research articles across multiple disciplines using the arXiv dataset.  

Features  
- **BM25 Ranking**: Efficient ranking of documents based on query relevance.  
- **Semantic Re-ranking**: Improved results using embeddings and similarity search.  
- **Filtering Options**: Filter by citation count, publication date, journal impact factor, and more.  
- **Interactive Interfaces**: Includes a Streamlit web app and CLI for query input and result display.  

 Dataset  
Utilizes the arXiv dataset from Cornell University, featuring metadata like titles, authors, abstracts, and categories to support cross-disciplinary search needs.  

Tools and Libraries  
- **BM25** for retrieval and ranking.  
- **FAISS** and **Pinecone** for vector indexing and search.  
- **Streamlit** for the web-based interface.  
- **IR Evaluation Library** for performance assessment using metrics like MAP, nDCG, and Precision@K.  

Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/shreyshrivastava/Academic-Search-Engine-for-Research-Papers.git  
   cd Academic-Search-Engine-for-Research-Papers  
