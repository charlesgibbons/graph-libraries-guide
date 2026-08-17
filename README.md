# Graph Libraries Guide 📊

A comprehensive, curated reference of graph libraries for knowledge graph construction, graph databases, visualization, and LLM integration. 

**Updated:** August 2026  
**Scope:** 100+ libraries across 11 categories

---

## 📚 Table of Contents

- [Knowledge Graph Extraction](#1-knowledge-graph-extraction--construction)
- [Graph Databases](#2-graph-databases)
- [Graph Processing & Analysis](#3-graph-processing--analysis)
- [Graph Visualization](#4-graph-visualization)
- [LLM + Graph Integration](#5-llm--graph-integration)
- [Semantic Web & RDF](#6-semantic-web--rdf)
- [Graph Neural Networks](#7-graph-neural-networks--machine-learning)
- [Vector Databases](#8-vector-databases-with-graph-features)
- [NLP & Extraction](#9-natural-language-processing--extraction)
- [Data Integration](#10-data-integration--etl)
- [Query Languages](#11-query-languages--standards)
- [By Use Case](#by-use-case)
- [Quick Start](#quick-start)

---

## 1. Knowledge Graph Extraction & Construction

Extract unstructured data (documents, text) and transform into structured knowledge graphs.

### Document to Graph

| Library | Language | Best For |
|---------|----------|----------|
| [docling-graph](https://github.com/docling-project/docling-graph) | Python | PDF/document → KG with LLM backend |
| [Docs2KG](https://github.com/AI4WA/Docs2KG) | Python | Human-LLM collaborative graph from diverse docs |
| [llm-graph-builder](https://github.com/neo4j-labs/llm-graph-builder) | Python/JS | Neo4j official tool for unstructured → graph |
| [knowledge-graph-extractor](https://github.com/hanxiao/knowledge-graph-extractor) | Python | Doc ZIP → interactive KG with local LLMs |
| [knowledge_graph](https://github.com/rahulnyk/knowledge_graph) | Python | Text → graph for RAG & QnA |
| [knowledge-graph-construction](https://github.com/aimaster-dev/knowledge-graph-construction) | Python | SPO triplet extraction + entity standardization |
| [ai-knowledge-graph](https://github.com/robert-mcdermott/ai-knowledge-graph) | Python | AI-powered KG generator |

### LLM-Integrated

| Library | Language | Best For |
|---------|----------|----------|
| [LangChain](https://github.com/langchain-ai/langchain) | Python/JS | Graph construction chains, RAG, entity extraction |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Python | KG + vector retrieval for RAG |

---

## 2. Graph Databases

Production-grade storage and query systems for graph data.

### Open Source

| Database | Language | Best For |
|----------|----------|----------|
| [Neo4j](https://github.com/neo4j/neo4j) | Java | Industry standard, property graphs |
| [ArangoDB](https://github.com/arangodb/arangodb) | C++/JS | Multi-model (graph + doc + search) |
| [JanusGraph](https://github.com/JanusGraph/janusgraph) | Java | Scalable, pluggable storage backends |
| [Memgraph](https://github.com/memgraph/memgraph) | C++ | Neo4j alternative, in-memory fast |
| [Dgraph](https://github.com/dgraph-io/dgraph) | Go | Distributed, GraphQL API |
| [RedisGraph](https://github.com/RedisGraph/RedisGraph) | C | In-memory graph on Redis |
| [HugeGraph](https://github.com/apache/incubator-hugegraph) | Java | Apache project, large-scale |

### Commercial / Managed

| Service | Best For |
|---------|----------|
| [TigerGraph](https://www.tigergraph.com/) | High-performance analytics at scale |
| [Amazon Neptune](https://aws.amazon.com/neptune/) | AWS-managed, property graphs & RDF |

---

## 3. Graph Processing & Analysis

Algorithms, analytics, and computation on graphs.

### Python Libraries

| Library | Best For |
|---------|----------|
| [NetworkX](https://github.com/networkx/networkx) | Graph algorithms, analysis |
| [igraph](https://igraph.org/) | High-performance algorithms |
| [SNAP](http://snap.stanford.edu/) | Large network analysis |
| [Graph-Tool](https://graph-tool.skewed.de/) | C++ backend, Python binding |

### Distributed Processing

| Library | Best For |
|---------|----------|
| [Apache Spark GraphX](https://spark.apache.org/graphx/) | Distributed graph computation |
| [Apache Flink Gelly](https://nightlies.apache.org/flink/flink-docs-master/docs/libs/gelly/overview/) | Streaming + batch graph processing |

### Standalone Tools

| Tool | Purpose |
|------|---------|
| [Gephi](https://gephi.org/) | Desktop graph analysis + visualization |
| [Graphviz](https://graphviz.org/) | Layout algorithms, static rendering |

---

## 4. Graph Visualization

Display and interact with graphs in web and desktop environments.

### JavaScript (Web)

| Library | GitHub | Best For |
|---------|--------|----------|
| [Cytoscape.js](https://js.cytoscape.org/) | [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | Interactive, feature-rich web viz |
| [Vis.js](https://visjs.org/) | [visjs/vis-network](https://github.com/visjs/vis-network) | Easy, performant network graphs |
| [D3.js](https://d3js.org/) | [d3/d3](https://github.com/d3/d3) | Highly customizable, powerful |
| [Force-Graph](https://github.com/vasturiano/force-graph) | — | 2D/3D force-directed layout |
| [Sigma.js](https://www.sigmajs.org/) | [jacomyal/sigma.js](https://github.com/jacomyal/sigma.js) | Large network visualization |

### Python

| Library | Best For |
|---------|----------|
| [PyVis](https://pyvis.readthedocs.io/) | Python wrapper for Vis.js, quick viz |
| [Plotly](https://plotly.com/python/network-graphs/) | Interactive, publication-quality |

### Desktop

| Tool | Purpose |
|------|---------|
| [Gephi](https://gephi.org/) | Full analysis + visualization suite |

---

## 5. LLM + Graph Integration

Connect large language models to knowledge graphs for reasoning and RAG.

### Frameworks

| Library | GitHub | Best For |
|---------|--------|----------|
| [LangChain](https://github.com/langchain-ai/langchain) | — | Graph memory, chains, extraction |
| [LlamaIndex](https://github.com/run-llama/llama_index) | — | KG + vector backend for RAG |
| [Mem0](https://github.com/mem0ai/mem0) | — | Persistent memory with graph storage |

### LLM APIs (Structured Output)

| Provider | Documentation |
|----------|---|
| [OpenAI](https://platform.openai.com/docs/guides/structured-outputs) | JSON schema for extraction |
| [Anthropic Claude](https://www.anthropic.com/) | Structured output API |

### LLM Abstraction

| Library | Purpose |
|---------|---------|
| [LiteLLM](https://github.com/BerriAI/litellm) | Unified LLM interface + graph connectors |

---

## 6. Semantic Web & RDF

Ontologies, linked data, and semantic web standards.

### RDF & Ontology

| Library | GitHub | Language | Best For |
|---------|--------|----------|----------|
| [RDFLib](https://github.com/RDFLib/rdflib) | — | Python | RDF graphs & SPARQL queries |
| [Apache Jena](https://jena.apache.org/) | — | Java | RDF framework + semantic web |
| [OWLAPI](https://github.com/owlcs/owlapi) | — | Java | OWL ontologies |

### Tools & Query

| Tool | Purpose |
|------|---------|
| [Protégé](https://protege.stanford.edu/) | Ontology editor (desktop + web) |
| [SPARQL](https://www.w3.org/TR/sparql11-overview/) | W3C standard for RDF queries |

### Public Knowledge Bases

| KB | Description |
|----|-------------|
| [Wikidata](https://www.wikidata.org/) | Open, queryable knowledge graph |
| [DBpedia](https://www.dbpedia.org/) | Structured Wikipedia data |

---

## 7. Graph Neural Networks & Machine Learning

Apply deep learning to graph-structured data.

### Libraries

| Library | Framework | Best For |
|---------|-----------|----------|
| [PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric) | PyTorch | Most popular GNN library |
| [DGL](https://github.com/dmlc/dgl) | PyTorch/TF/MXNet | Framework-agnostic GNN |
| [Spektral](https://graphneural.network/) | Keras/TF | Graph NN on TensorFlow |
| [Jraph](https://github.com/deepmind/jraph) | JAX | DeepMind's JAX library |
| [StellarGraph](https://github.com/stellargraph/stellargraph) | TF/Keras | ML on graphs |
| [Graph-Tool](https://graph-tool.skewed.de/) | C++/Python | Network analysis + ML |

---

## 8. Vector Databases with Graph Features

Combine vector search with graph capabilities for RAG and similarity search.

| Database | GitHub | Best For | Type |
|----------|--------|----------|------|
| [Weaviate](https://github.com/weaviate/weaviate) | — | Vector + graph, RAG systems | Cloud/Open |
| [Milvus](https://github.com/milvus-io/milvus) | — | Scalable vector search | Open Source |
| [Pinecone](https://www.pinecone.io/) | — | Vector search as service | Cloud |
| [Chroma](https://github.com/chroma-core/chroma) | — | Lightweight embedding DB | Open Source |
| [FAISS](https://github.com/facebookresearch/faiss) | — | Facebook's similarity search | Open Source |

---

## 9. Natural Language Processing & Extraction

Extract entities, relationships, and structured data from text.

| Library | GitHub | Language | Best For |
|---------|--------|----------|----------|
| [spaCy](https://github.com/explosion/spaCy) | — | Python | Industrial NLP + entity recognition |
| [YAKE](https://github.com/LIAAD/yake) | — | Python | Unsupervised keyword extraction |
| [OpenIE](https://github.com/knowitall/openie) | — | Java | Extract subject-predicate-object triples |
| [REBEL](https://github.com/Babelscape/rebel) | — | Python | Relation extraction model |
| [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/) | — | Java | Comprehensive NLP toolkit |
| [Hugging Face Transformers](https://github.com/huggingface/transformers) | — | Python | Pre-trained models for extraction |
| [Docling](https://github.com/DS4SD/docling) | — | Python | Document parsing + layout analysis |

---

## 10. Data Integration & ETL

Pipeline orchestration and data transformation.

| Tool | GitHub | Best For |
|------|--------|----------|
| [Apache Airflow](https://github.com/apache/airflow) | — | Workflow orchestration |
| [dbt](https://github.com/dbt-labs/dbt-core) | — | Data transformation (ELT) |
| [Apache NiFi](https://github.com/apache/nifi) | — | Data routing + transformation |
| [Talend](https://www.talend.com/) | — | Enterprise ETL |
| [AWS Glue](https://aws.amazon.com/glue/) | — | Serverless data integration |

---

## 11. Query Languages & Standards

Query and traverse graph data.

| Language | Purpose | Best For |
|----------|---------|----------|
| [Cypher](https://neo4j.com/developer/cypher/) | Neo4j query language | Property graphs, becoming standard |
| [Gremlin](https://tinkerpop.apache.org/gremlin.html) | Apache TinkerPop traversal | Multi-language graph queries |
| [SPARQL](https://www.w3.org/TR/sparql11-overview/) | RDF query standard | Semantic web, linked data |
| [GraphQL](https://graphql.org/) | API query language | Works alongside graphs for APIs |

---

## By Use Case

### For LLM & RAG Applications
- **Extract:** LangChain, LlamaIndex, docling-graph
- **Store:** Neo4j, Weaviate, ArangoDB
- **Query:** Cypher, GraphQL

### For Enterprise Knowledge Graphs  
- **Build:** llm-graph-builder, Docs2KG, docling-graph
- **Store:** Neo4j, TigerGraph, JanusGraph
- **Query:** Cypher, SPARQL

### For Data Science & Graph Analytics
- **Compute:** NetworkX, PyTorch Geometric, DGL
- **Visualize:** Gephi, Cytoscape.js, Plotly
- **Store:** Neo4j, ArangoDB

### For Document → Graph Pipelines
- **Extract:** docling-graph, Docs2KG, spaCy, OpenIE
- **Transform:** Apache Airflow, dbt
- **Load:** Neo4j, ArangoDB

### For Real-Time Applications
- **Store:** RedisGraph, Memgraph, Dgraph
- **Process:** Apache Flink Gelly
- **Visualize:** Cytoscape.js, Vis.js

### For Semantic Web & Knowledge Bases
- **Query:** RDFLib, Apache Jena, SPARQL
- **Browse:** Wikidata, DBpedia
- **Build:** OWLAPI, Protégé

### For Graph Visualization Only
- Web: Cytoscape.js, Vis.js, D3.js, Force-Graph
- Desktop: Gephi
- Python: PyVis, Plotly

---

## Quick Start

### Beginner (just exploring)
1. Install **[NetworkX](https://networkx.org/)** — learn graph fundamentals
2. Visualize with **[Cytoscape.js](https://js.cytoscape.org/)** or **[PyVis](https://pyvis.readthedocs.io/)**
3. Read about **[Neo4j Cypher](https://neo4j.com/developer/cypher/)**

### Building Knowledge Graph Systems
```
Data → [docling-graph or Docs2KG] 
      → [Neo4j or ArangoDB] 
      → [LangChain or LlamaIndex] 
      → [Your LLM App]
```

1. Extract: docling-graph for PDFs, Docs2KG for mixed documents
2. Store: Neo4j (industry standard) or ArangoDB (multi-model)
3. Integrate: LangChain for LLM chains, LlamaIndex for RAG
4. Query: Cypher for Neo4j or AQL for ArangoDB

### Machine Learning on Graphs
1. Learn: **[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/)** or **[DGL](https://www.dgl.ai/)**
2. Visualize: **[Gephi](https://gephi.org/)** or **[Cytoscape.js](https://js.cytoscape.org/)**
3. Scale: **[Apache Spark GraphX](https://spark.apache.org/graphx/)** if needed

### Semantic Web / Linked Data
1. Learn SPARQL: [W3C Tutorial](https://www.w3.org/TR/sparql11-overview/)
2. Explore: [Wikidata](https://www.wikidata.org/), [DBpedia](https://www.dbpedia.org/)
3. Build: [RDFLib](https://rdflib.readthedocs.io/) (Python)

---

## Contributing

This is a curated reference guide. It is **not open to community contributions** at this time.

For corrections or suggestions, please open an issue.

---

## License

This guide is provided as-is for educational and reference purposes.

---

## 📖 About

This guide was created to help developers, data scientists, and engineers navigate the expanding landscape of graph technologies. Whether you're building knowledge graphs, analyzing networks, or integrating LLMs with structured data, this reference should help you find the right tool.

**Last Updated:** August 2026  
**Maintained by:** [apicrazy.com](https://apicrazy.com)

---

## Related Resources

- [apicrazy.com Blog](https://apicrazy.com) — Articles on knowledge graphs and APIs
- [Neo4j Resources](https://neo4j.com/developer/)
- [Knowledge Graphs and LLMs](https://github.com/heathersherry/Knowledge-Graph-Tutorials-and-Papers) — Research papers and tutorials
