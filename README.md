# UniGraph-RAG: A Constraint-Aware Graph and Text Retrieval Pipeline for Academic Progression  
*Demo paper submitted to the WWW 2026 Demo Track*

---

## 🎯 Abstract  
Large Language Models (LLMs) increasingly rely on retrieval for reliable reasoning. Yet most Retrieval-Augmented Generation (RAG) systems underperform when tasks require integrating **structured graph data**, **unstructured policy documents**, and **explicit academic constraints**.

**UniGraph-RAG** introduces a unified, constraint-aware retrieval pipeline that blends:

- 🧭 **GraphRAG** over a domain Knowledge Graph  
- 📄 **Document-level RAG** over policy and handbook sources  
- 🔍 **Text-to-Cypher translation** for structure-aware query patterns  

The system ingests heterogeneous sources, identifies key entities, aligns documents with graph nodes, and dynamically selects the appropriate retrieval mode based on query intent.

To diagnose retrieval gaps, UniGraph-RAG includes a **retrieval-quality harness** that evaluates:

- 🌐 Graph coverage  
- ✔️ Constraint satisfaction  
- 🔗 Graph–text coherence  
- 📑 Evidence traceability  

We demonstrate UniGraph-RAG in the academic advising domain, where reasoning requires reconciling **versioned curriculum graphs**, **dynamic student histories**, and **unstructured policy documents**. In systematic evaluations, UniGraph-RAG outperforms LLM-only, RAG-only, and KG-only baselines by producing:

- 📘 More rule-compliant study plans  
- ⚠️ Fewer prerequisite and progression violations  
- ✨ Substantially reduced hallucination  

These results highlight the decisive role of **high-quality, constraint-aware retrieval** in graph-dependent reasoning tasks.

---

## 🏗️ System Architecture  
*(Insert your diagram once uploaded)*  
![Architecture Diagram of UniGraph-RAG](architecture_unigraph.png)

---

## 🎥 Demo Video  
Walkthrough of the retrieval pipeline, constraint-checking workflow, and advising interactions:

🔗 https://www.loom.com/share/904f27aaea064949ba7a1bce74cf32c0


---

## 🤝 Acknowledgements  
This demo was developed as part of the WWW 2026 submission and builds upon ongoing research in graph-based retrieval and academic progression analytics.

