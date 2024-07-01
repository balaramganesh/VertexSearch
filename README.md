# VertexSearch
Implementing vertex search using FAISS Indices

The FAISS.ipynb notebook intends to solve for the following use case:
Give the user a list of top movie suggestions based on a given list of movies. 

Implementation:
Instead of using lexical search, performing the more effective semantic search for movies based on a vector index created on the BERT embeddings of the movies' descriptions. The vector index is created using the FAISS (Facebook AI Similarity Search) library. 
