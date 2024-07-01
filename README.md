# VertexSearch
Implementing vertex search using FAISS Indices

The FAISS.ipynb notebook intends to solve for the following use case:
Give the user a list of top movie suggestions based on a given list of movies. 

Here is an example: 

Custom movie description: Suggest historical movies  
Search Result:  
Honigmond  -  German Comedy   
Richard III  -  Shakespeare's Play transplanted into a 1930s setting.  
It's My Party  -  A gathering of friends. A gift of love. A celebration of life.  
Paris, France  -  A writer has torrid fantasy affairs with young men.  
Living in Oblivion  -  Film about filmmaking. It takes place during one day on set of non-budget movie. Ultimate tribute to all independent filmmakers.  

Implementation:   
Instead of using lexical search, performing the more effective semantic search for movies based on a vector index created on the BERT embeddings of the movies' descriptions.  The vector index is created using the FAISS (Facebook AI Similarity Search) library.  
