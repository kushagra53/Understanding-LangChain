# Understanding-LangChain
Week 1 
“This week we finalized the problem statement and architecture.
We studied the RAG pipeline end-to-end and implemented the data ingestion layer.
We tested PDF and CSV loaders, converted documents into a unified Document format with metadata, and verified chunking behavior.

Our next step is building local embeddings, indexing with FAISS, and evaluating retrieval quality before adding quiz generation.”

Our setting is currently limited to digital documents because-
“Handwritten notes require OCR and layout understanding, which is a separate ML problem.
For this phase we’re focusing on retrieval-augmented generation over clean digital text so we can evaluate grounding and retrieval quality properly
