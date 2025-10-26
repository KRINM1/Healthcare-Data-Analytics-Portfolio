# AI Vector Search in Healthcare

**Goal**  
Demonstrate how Oracle Cloud Vector Search + Generative AI (RAG) can enhance access to clinical knowledge.

**Tools Used**  
Oracle Cloud Generative AI, Vector Search, Python, LangChain

**Workflow**  
1. Ingest public health education pages (MedlinePlus, CDC).  
2. Chunk & embed text → store embeddings in OCI Vector Search.  
3. Retrieve top-k results for a clinician/patient question.  
4. LLM summarizes with citations & safety disclaimer.

**Example Prompt**  
> “Summarize self-care instructions for heart failure using retrieved context only.”

**Preview**
![Preview](../assets/vector_search_diagram.png)
