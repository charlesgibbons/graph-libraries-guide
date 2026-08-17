# Complete Graph Libraries Guide: Build Knowledge Graphs & Graph Applications

A comprehensive reference of graph libraries for knowledge graph construction, databases, visualization, and LLM integration.

---

## 1. Knowledge Graph Construction & Extraction

### From Documents to Graphs

- **[docling-graph](https://github.com/docling-project/docling-graph)** — Transform unstructured documents into validated knowledge graphs. Supports PDF, images, and various formats with LLM-powered extraction.

- **[Docs2KG](https://github.com/AI4WA/Docs2KG)** — Human-LLM collaborative approach to unified knowledge graph construction from heterogeneous documents.

- **[llm-graph-builder](https://github.com/neo4j-labs/llm-graph-builder)** — Official Neo4j tool for knowledge graph construction from unstructured data using LLMs.

- **[knowledge-graph-extractor](https://github.com/hanxiao/knowledge-graph-extractor)** — Turn any document or ZIP into an interactive knowledge graph using self-hosted LLMs (Qwen, etc.).

- **[knowledge_graph](https://github.com/rahulnyk/knowledge_graph)** — Convert any text to a graph of knowledge for Graph Augmented Generation (RAG) and knowledge-based QnA.

- **[knowledge-graph-construction](https://github.com/aimaster-dev/knowledge-graph-construction)** — SPO triplet extraction with entity standardization and community detection visualization.

- **[ai-knowledge-graph](https://github.com/robert-mcdermott/ai-knowledge-graph)** — AI-powered knowledge graph generator from unstructured text.

### LLM-Integrated Graph Building

- **[LangChain](https://github.com/langchain-ai/langchain)** — Graph construction chains, entity extraction, relationship mapping for RAG applications.

- **[LlamaIndex](https://github.com/run-llama/llama_index)** — Knowledge graph building from documents with LLM integration and vector retrieval.

---

## 2. Graph Databases (Storage & Query)

### Production-Grade Databases

- **[Neo4j](https://github.com/neo4j/neo4j)** — Industry-standard property graph database with Cypher query language. Most widely adopted.

- **[ArangoDB](https://github.com/arangodb/arangodb)** — Multi-model database supporting graphs, documents, and search in one system.

- **[TigerGraph](https://www.tigergraph.com/)** — High-performance distributed graph database designed for large-scale analytics.

- **[JanusGraph](https://github.com/JanusGraph/janusgraph)** — Scalable, open-source graph database backed by Apache. Can use various storage backends.

- **[Memgraph](https://github.com/memgraph/memgraph)** — Open-source Neo4j alternative with in-memory performance.

### Cloud & Managed Services

- **[Amazon Neptune](https://aws.amazon.com/neptune/)** — AWS-managed graph database supporting both property graphs and RDF.

- **[Dgraph](https://github.com/dgraph-io/dgraph)** — Distributed graph database with GraphQL API.

- **[RedisGraph](https://github.com/RedisGraph/RedisGraph)** — In-memory graph database built on Redis.

- **[HugeGraph](https://github.com/apache/incubator-hugegraph)** — Apache project for large-scale graph databases.

---

## 3. Graph Processing & Analysis

### Algorithms & Computing

- **[NetworkX](https://github.com/networkx/networkx)** — Most popular Python library for graph algorithms, analysis, and visualization. Industry standard.

- **[igraph](https://igraph.org/)** — High-performance C library with bindings for Python, R, Ruby. Fast algorithms.

- **[Apache Spark GraphX](https://spark.apache.org/graphx/)** — Distributed graph processing and computation on Spark clusters.

- **[Apache Flink Gelly](https://nightlies.apache.org/flink/flink-docs-master/docs/libs/gelly/overview/)** — Distributed graph processing on Apache Flink.

- **[SNAP](http://snap.stanford.edu/)** — Stanford Network Analysis Platform. High-performance for large networks.

### Desktop & Standalone Tools

- **[Gephi](https://gephi.org/)** — Open-source graph analysis and visualization platform. Desktop application.

- **[Graphviz](https://graphviz.org/)** — Graph visualization software. Layout algorithms and rendering.

---

## 4. Graph Visualization

### JavaScript Libraries

- **[Cytoscape.js](https://js.cytoscape.org/)** — Web-based, highly interactive graph visualization. Most feature-rich for web applications.

- **[Vis.js](https://visjs.org/)** — JavaScript library for network visualization. Easy to use, good performance.

- **[D3.js](https://d3js.org/)** — Highly customizable visualization library. Steep learning curve but maximum control.

- **[Force-Graph](https://github.com/vasturiano/force-graph)** — 2D and 3D force-directed graph visualization.

- **[Sigma.js](https://www.sigmajs.org/)** — Dedicated graph visualization library optimized for large networks.

### Python Libraries

- **[PyVis](https://pyvis.readthedocs.io/)** — Python wrapper for Vis.js. Easy interactive graph visualization.

- **[Plotly](https://plotly.com/python/network-graphs/)** — Interactive network graphs with Python API.

### Standalone & Desktop

- **[Gephi](https://gephi.org/)** — Full-featured visualization and analysis platform (also listed above).

---

## 5. LLM + Graph Integration

### Frameworks & Platforms

- **[LangChain](https://github.com/langchain-ai/langchain)** — Graph memory, reasoning chains, and entity extraction for LLM apps.

- **[LlamaIndex](https://github.com/run-llama/llama_index)** — Knowledge graphs combined with vector retrieval for RAG systems.

- **[Mem0](https://github.com/mem0ai/mem0)** — Persistent memory layer with graph-based storage for AI agents.

### LLM APIs (Structured Output)

- **[OpenAI API](https://platform.openai.com/docs/guides/structured-outputs)** — Structured output mode for entity/relationship extraction.

- **[Anthropic Claude API](https://www.anthropic.com/)** — Structured output via JSON schema for extraction tasks.

- **[LiteLLM](https://github.com/BerriAI/litellm)** — Unified LLM interface with graph connectors.

---

## 6. Semantic Web & RDF

### RDF & Ontology

- **[RDFLib](https://github.com/RDFLib/rdflib)** — Python library for RDF and SPARQL query support.

- **[Apache Jena](https://jena.apache.org/)** — Java-based framework for RDF and semantic web applications.

- **[OWLAPI](https://github.com/owlcs/owlapi)** — OWL ontology API for Java. Handle complex ontologies.

### Tools & Editors

- **[Protégé](https://protege.stanford.edu/)** — Ontology editor. Desktop and web versions.

### Query Languages

- **[SPARQL](https://www.w3.org/TR/sparql11-overview/)** — W3C standard for querying RDF graphs.

### Public Knowledge Graphs

- **[Wikidata](https://www.wikidata.org/)** — Large, open knowledge graph. Queryable via SPARQL.

- **[DBpedia](https://www.dbpedia.org/)** — Structured data extracted from Wikipedia.

---

## 7. Graph Neural Networks & Machine Learning

### Deep Learning on Graphs

- **[PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric)** — Most popular library for graph neural networks on PyTorch.

- **[DGL (Deep Graph Library)](https://github.com/dmlc/dgl)** — Framework-agnostic GNN library. Works with PyTorch, TensorFlow, MXNet.

- **[Spektral](https://graphneural.network/)** — Graph neural networks for Keras and TensorFlow.

- **[Graph-Tool](https://graph-tool.skewed.de/)** — C++ library with Python bindings for network analysis and machine learning.

- **[Jraph](https://github.com/deepmind/jraph)** — JAX library for graph neural networks from DeepMind.

- **[StellarGraph](https://github.com/stellargraph/stellargraph)** — Machine learning on graphs with TensorFlow and Keras.

---

## 8. Vector Databases with Graph Features

### Hybrid Vector + Graph

- **[Weaviate](https://github.com/weaviate/weaviate)** — Vector database with graph capabilities and RAG support.

- **[Milvus](https://github.com/milvus-io/milvus)** — Open-source vector database. Scalable similarity search.

- **[Pinecone](https://www.pinecone.io/)** — Vector search as a service. Cloud-hosted.

- **[Chroma](https://github.com/chroma-core/chroma)** — Lightweight open-source vector database for embeddings.

- **[FAISS](https://github.com/facebookresearch/faiss)** — Facebook's library for similarity search at scale.

---

## 9. Natural Language Processing & Extraction

### Entity & Relationship Extraction

- **[spaCy](https://github.com/explosion/spaCy)** — Industrial-strength NLP pipeline with entity recognition.

- **[YAKE](https://github.com/LIAAD/yake)** — Unsupervised keyword extraction. No training required.

- **[OpenIE](https://github.com/knowitall/openie)** — Open Information Extraction. Extract subject-predicate-object triples.

- **[REBEL](https://github.com/Babelscape/rebel)** — Relation extraction model. Pre-trained on large corpora.

- **[Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/)** — Comprehensive NLP toolkit for Java.

- **[Hugging Face Transformers](https://github.com/huggingface/transformers)** — Pre-trained language models for extraction tasks.

### Document Processing

- **[Docling](https://github.com/DS4SD/docling)** — Document parsing and layout analysis. Base library for docling-graph.

---

## 10. Data Integration & ETL

### Workflow Orchestration

- **[Apache Airflow](https://github.com/apache/airflow)** — Workflow orchestration platform. Define, schedule, monitor pipelines.

- **[dbt](https://github.com/dbt-labs/dbt-core)** — Data transformation. "T" in ELT. Transform raw data into analytics-ready tables.

- **[Apache NiFi](https://github.com/apache/nifi)** — Data routing, transformation, and system mediation logic.

### ETL Platforms

- **[Talend](https://www.talend.com/)** — Enterprise ETL platform.

- **[AWS Glue](https://aws.amazon.com/glue/)** — Serverless data integration service.

---

## 11. Query Languages & Standards

### Graph Query Languages

- **[Cypher](https://neo4j.com/developer/cypher/)** — Neo4j's query language. Becoming de facto standard for property graphs.

- **[Gremlin](https://tinkerpop.apache.org/gremlin.html)** — Apache TinkerPop's graph traversal language. Language-agnostic.

- **[SPARQL](https://www.w3.org/TR/sparql11-overview/)** — W3C standard for querying RDF graphs.

### Complementary

- **[GraphQL](https://graphql.org/)** — API query language. Works alongside graph databases for API design.

---

## By Use Case

### For LLM & RAG Applications
- LangChain, LlamaIndex, docling-graph, Neo4j, Weaviate, llm-graph-builder

### For Enterprise Knowledge Graphs
- Neo4j, TigerGraph, JanusGraph, ArangoDB, llm-graph-builder

### For Data Science & Analysis
- NetworkX, PyTorch Geometric, DGL, Gephi, SNAP, igraph

### For Document → Graph Pipelines
- docling-graph, Docs2KG, LangChain, spaCy, YAKE, OpenIE

### For Real-Time Applications
- RedisGraph, Memgraph, ArangoDB, Dgraph

### For Semantic Web & Knowledge Bases
- RDFLib, Apache Jena, OWLAPI, SPARQL, Wikidata

### For Visualization Only
- Cytoscape.js, Vis.js, D3.js, Gephi, Force-Graph

---

## Getting Started

**For beginners:**
1. Start with **NetworkX** for graph algorithms
2. Use **Cytoscape.js** or **Vis.js** for visualization
3. Try **LangChain** for LLM integration

**For building knowledge graph systems:**
1. Extract with **docling-graph** or **Docs2KG**
2. Store in **Neo4j** or **ArangoDB**
3. Query with **Cypher** or integrate with **LangChain**

**For ML on graphs:**
1. Learn **PyTorch Geometric** or **DGL**
2. Visualize with **Gephi** or **Cytoscape.js**
3. Deploy with **Spark GraphX** if needed at scale

---

## Comparison Matrix

| Library | Type | Language | Best For | Maturity |
|---------|------|----------|----------|----------|
| Neo4j | Database | Java | Enterprise graphs | ⭐⭐⭐⭐⭐ |
| docling-graph | Extraction | Python | Doc → Graph | ⭐⭐⭐⭐ |
| NetworkX | Analysis | Python | Algorithms | ⭐⭐⭐⭐⭐ |
| PyTorch Geometric | ML | Python | Graph Neural Nets | ⭐⭐⭐⭐⭐ |
| LangChain | Framework | Python | LLM + Graphs | ⭐⭐⭐⭐ |
| Cytoscape.js | Visualization | JavaScript | Web visualization | ⭐⭐⭐⭐⭐ |
| ArangoDB | Database | Multi | Multi-model data | ⭐⭐⭐⭐ |
| TigerGraph | Database | C++ | Analytics at scale | ⭐⭐⭐⭐ |
| Weaviate | Vector DB | Go | RAG systems | ⭐⭐⭐⭐ |
| JanusGraph | Database | Java | Scalable graphs | ⭐⭐⭐⭐ |

---

*Last updated: August 2026*
