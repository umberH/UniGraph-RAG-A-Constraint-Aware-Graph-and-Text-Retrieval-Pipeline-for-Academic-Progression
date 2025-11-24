# UniGraph-RAG: A Constraint-Aware Graph and Text Retrieval Pipeline for Academic Progression  
*Demo paper submitted to the WWW 2026 Demo Track*

---

## 🎯 Abstract  
Large Language Models (LLMs) increasingly depend on retrieval for reliable reasoning. Yet, most Retrieval Augmentation Generation (RAG) systems underperform when tasks require integrating structured graph data, unstructured documents, and explicit constraints. We introduce UniGraph-RAG, a unified retrieval data pipeline that combines GraphRAG over a domain Knowledge Graph with document-level RAG and a text-to-Cypher translation layer. UniGraph-RAG ingests heterogeneous sources, identifies entities, aligns documents with graph nodes, and dynamically selects the appropriate retrieval mode based on query intent. A retrieval-quality harness evaluates graph and constraint coverage, graph–text coherence, and evidence traceability, enabling systematic diagnosis of retrieval gaps. We demonstrate UniGraph-RAG on academic advising, a scenario that requires accurate integration of graph-structured curricula with unstructured policy documents. In systematic evaluations, UniGraph-RAG outperforms LLM-only, RAG-only, and Graph-only baselines by producing more rule-compliant study plans, fewer constraint violations, and markedly reduced hallucination, highlighting the decisive role of retrieval quality in graph-dependent reasoning tasks.

---

## 🏗️ System Architecture  

![Architecture Diagram of UniGraph-RAG](
<img width="1334" height="941" alt="architecture_diagram (1)" src="https://github.com/user-attachments/assets/51cca46f-89b9-4536-8660-a76569f91554" />)
<img width="1334" height="941" alt="architecture_diagram (1)" src="https://github.com/user-attachments/assets/51cca46f-89b9-4536-8660-a76569f91554" />


---


## System Screen w

<img width="3536" height="1083" alt="interface drawio" src="https://github.com/user-attachments/assets/0413ca8d-9da7-44c4-8ffa-798429db90e9" />


## 🎥 Demo Video  
Walkthrough of the retrieval pipeline, constraint-checking workflow, and advising interactions:

🔗 https://www.loom.com/share/904f27aaea064949ba7a1bce74cf32c0


---

## 🤝 Acknowledgements  
This demo was developed as part of the WWW 2026 submission and builds upon ongoing research in graph-based retrieval and academic progression analytics.

