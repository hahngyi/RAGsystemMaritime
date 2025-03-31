# Maritime Regulations RAG

This RAG system takes a large pdf of regulations and implements Gemini API key to answer related inputs. 

## Includes:

 * **rag_prep**
  1. breaks pdf into chunks
  1. stores vector embeddings
 * **rag_query**
1. finds relevant chunks to query
1. extracts and combines chunks

