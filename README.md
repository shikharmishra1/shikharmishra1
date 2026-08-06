<div align="center">

# Shikhar Mishra

### I teach machines to search before they hallucinate.

AI engineer building agentic systems, document intelligence, semantic search, and the occasional programming language—because apparently one syntax wasn’t enough.

[LinkedIn](https://www.linkedin.com/in/shikhar-mishra-17b5a1231/) · [GitHub](https://github.com/shikharmishra1) · [Email](mailto:shikharmishra.nu@gmail.com) · [Résumé](./Shikhar_Mishra_CV.pdf)

</div>

## The short version

I build AI systems that have to work outside a notebook: RAG pipelines, ReAct agents, search infrastructure, document parsers, and FastAPI services that survive contact with real users.

Some people collect browser tabs. I collect retrieval metrics.

| Signal | Result |
|:--|--:|
| RAG answer accuracy | **93%** |
| Domain embedding recall | **96%** |
| Active-user growth linked to NLP personalization | **2×** |
| Longer average sessions | **120%** |

## Things I’ve convinced computers to do

### [TurboParse](https://turboparse.shikharmishra-cnt.workers.dev/)

**Parse documents in the browser, at roughly 100 pages per second, without sending them anywhere.**

A privacy-first document intelligence engine built with TypeScript, LightGBM, ONNX Runtime Web, WebAssembly, and OpenCV. It runs fully on-device, understands document layout, and turns PDFs into structured, RAG-ready content—even offline or air-gapped.

`91.34% accuracy` · `86.32% macro F1` · `CPU only` · `No external API`

### [AI Power System Analysis](https://gridmind-fe.shikharmishra-cnt.workers.dev/)

**An AI copilot for electrical networks ranging from 14 to 70,000+ buses.**

The platform combines React, FastAPI, LangChain, PyTorch, MongoDB, a graph neural network, and a ReAct agent armed with 60+ tools for topology, power flow, contingency, OPF, and SCADA queries.

`60+ agent tools` · `100+ MATPOWER cases` · `RAGAS scores: 1.00`

### [Nirguna](https://shikharmishra1.github.io/Nirgunawebapp/)

**A Unicode-native programming language written in Devanagari.**

Custom lexer, recursive-descent parser, type-safe AST, tree-walking interpreter, closures, objects, arrays, localized errors, REPL, and a VS Code extension. It started as a compiler project and escalated responsibly.

`TypeScript` · `Compiler design` · `देवनागरी` · `Yes, it actually runs`

## My usual accomplices

```text
AI & NLP       LLMs · RAG · ReAct · embeddings · reranking · RAGAS
ML             PyTorch · Transformers · SentenceTransformers · LightGBM · YOLO
Search         Apache Solr · BM25 · dense search · hybrid search · RankLib
Backend        Python · FastAPI · MongoDB · MinIO · Keycloak
Frontend       TypeScript · JavaScript · React · ONNX Runtime Web · WebAssembly
Infrastructure Docker · Docker Compose · Azure · Git
```

## How I tend to build

- Give the model tools, context, and a way to admit uncertainty.
- Measure retrieval before blaming generation.
- Keep the clever part explainable and the boring part reliable.
- Ship the demo. Benchmarks are nicer when they have a URL.

## Currently

Building production AI systems at **1Ansah Technologies**, with a particular interest in retrieval, agent orchestration, document AI, and search that understands what the user meant—not just what they typed.

<div align="center">

### Got a difficult search problem, an unruly document collection, or an agent that keeps improvising?

[Let’s talk.](mailto:shikharmishra.nu@gmail.com)

<sub>No chatbots were asked to “delve” during the making of this README.</sub>

</div>
