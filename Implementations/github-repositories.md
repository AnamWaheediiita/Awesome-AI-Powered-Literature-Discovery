# GitHub Implementations

This section contains open-source GitHub repositories related to AI-powered literature discovery, scholarly search, scientific paper recommendation, citation analysis, and research-paper exploration. The selected projects provide implementations, tools, or research code that can be studied and reused for academic research.

## 1. Semantic Scholar Academic Graph API

**Repository:** Allen Institute for AI (AI2)

**What it implements:**
The Semantic Scholar Academic Graph API provides programmatic access to scholarly-paper information, including papers, authors, citations, references, and related academic metadata.

**Why it is relevant:**
The API can be used to build applications for academic search, paper recommendation, citation analysis, literature exploration, and other research-discovery tasks.

**GitHub:**
[Semantic Scholar API](https://github.com/allenai/s2-folks)

**Official Documentation:**
[Semantic Scholar API Documentation](https://www.semanticscholar.org/product/api)

---

## 2. S2ORC

**Repository:** Allen Institute for AI (AI2)

**What it implements:**
S2ORC (Semantic Scholar Open Research Corpus) provides tools and resources for working with a large-scale collection of scientific papers and their metadata, including citation relationships.

**Why it is relevant:**
S2ORC can support research involving scientific information retrieval, citation analysis, document classification, paper recommendation, and scientific NLP.

**GitHub:**
[S2ORC](https://github.com/allenai/s2orc)

**Research Paper:**
[S2ORC — ACL Anthology](https://aclanthology.org/2020.acl-main.447/)

---

## 3. SciDocs

**Repository:** Allen Institute for AI (AI2)

**What it implements:**
SciDocs provides an evaluation framework for scientific document representations. It includes benchmark tasks such as document classification, citation prediction, and recommendation.

**Why it is relevant:**
The repository is directly relevant to evaluating AI systems that represent, compare, recommend, and connect scientific papers.

**GitHub:**
[SciDocs](https://github.com/allenai/scidocs)

**Project Page:**
[SciDocs](https://allenai.github.io/scidocs/)

**Research Paper:**
[SPECTER — ACL Anthology](https://aclanthology.org/2020.acl-main.207/)

---

## 4. SPECTER

**Repository:** Allen Institute for AI (AI2)

**What it implements:**
SPECTER is a scientific-document representation model that uses citation information to produce embeddings of research papers. These embeddings can represent relationships between scientific documents.

**Why it is relevant:**
SPECTER is highly relevant to AI-powered literature discovery because scientific-paper embeddings can be used for document similarity, citation prediction, and paper recommendation.

**GitHub:**
[SPECTER](https://github.com/allenai/specter)

**Research Paper:**
[SPECTER: Document-level Representation Learning Using Citation-informed Transformers](https://aclanthology.org/2020.acl-main.207/)

---

## 5. Pyserini

**Repository:** Castorini Research Group

**What it implements:**
Pyserini is an open-source toolkit for reproducible information retrieval research. It provides implementations and prebuilt indexes for sparse and dense retrieval methods and supports searching large document collections.

**Why it is relevant:**
Pyserini is useful for understanding and experimenting with the technical foundations of literature-discovery systems, including document retrieval, dense retrieval, ranking, and benchmarking.

**GitHub:**
[Pyserini](https://github.com/castorini/pyserini)

**Documentation:**
[Pyserini Documentation](https://castorini.github.io/pyserini/)

---

## Comparison of GitHub Implementations

| Repository               | Main Focus                             | Relevance                                     |
| ------------------------ | -------------------------------------- | --------------------------------------------- |
| **Semantic Scholar API** | Scholarly metadata and citation access | Building research-discovery applications      |
| **S2ORC**                | Scientific corpus and citations        | Scholarly NLP and literature analysis         |
| **SciDocs**              | Scientific document evaluation         | Evaluating recommendation and citation models |
| **SPECTER**              | Scientific document embeddings         | Similarity and paper recommendation           |
| **Pyserini**             | Information retrieval                  | Search, ranking, and retrieval experiments    |

## Summary

These repositories provide different technical perspectives on AI-powered literature discovery. Semantic Scholar provides access to scholarly information, while S2ORC supplies a large corpus for research and experimentation. SciDocs provides standardized evaluation tasks, SPECTER demonstrates citation-informed scientific-document representations, and Pyserini provides practical implementations for information retrieval and ranking.

Together, these projects can help researchers understand how modern literature-discovery systems are built, evaluated, and applied.

