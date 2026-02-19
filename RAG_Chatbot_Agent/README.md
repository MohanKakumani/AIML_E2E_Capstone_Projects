RAG - Implemented ingestion of structured and unstructured documents in PDF format with text, images and tables.
  For text, perform chunking, embedding generation and meta data insertion and store in FAISS.
  For Image, generate image embeddings using CLIP model and store in FAISS.
  Retrieve the results using similarity search between query embeddings and stored embeddings in the FAISS.
  
Chat with vector-indexed data by integrating with LLM and use LLM-as-Judge framework to evaluate the LLM response.

Enhance the RAG framework to Agentic RAG by introducing Query rewriting, extend the capabilities with tools and generate the final response 
in iterative manner.
