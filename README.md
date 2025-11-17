# UniGraph-RAG-A-Constraint-Aware-Graph-and-Text-Retrieval-Pipeline-for-Academic-Progression
Repo for the demo paper submitted in WWW demo track 2026


# Abstract 
Large Language Models (LLMs) increasingly depend on retrieval
for reliable reasoning. Yet, most Retrieval Augmentation Gener-
ation (RAG) systems underperform when tasks require integrat-
ing structured graph data, unstructured documents, and explicit
constraints. We introduce UniGraph-RAG, a unified retrieval data
pipeline that combines GraphRAG over a domain Knowledge Graph
with document-level RAG and a text-to-Cypher translation layer.
UniGraph-RAG ingests heterogeneous sources, identifies entities,
aligns documents with graph nodes, and dynamically selects the ap-
propriate retrieval mode based on query intent. A retrieval-quality
harness evaluates graph and constraint coverage, graph–text co-
herence, and evidence traceability, enabling systematic diagnosis
of retrieval gaps. We demonstrate UniGraph-RAG on academic
advising, a scenario that requires accurate integration of graph-
structured curricula with unstructured policy documents. In sys-
tematic evaluations, UniGraph-RAG outperforms LLM-only, RAG-
only, and Graph-only baselines by producing more rule-compliant
study plans, fewer constraint violations, and markedly reduced
hallucination, highlighting the decisive role of retrieval quality in
graph-dependent reasoning tasks.
