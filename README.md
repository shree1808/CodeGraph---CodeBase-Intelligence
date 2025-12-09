# CodeGraph---CodeBase-Intelligence
An codebase intelligence assistant to analyze .NET and Python codebases through static code parsing for impact analysis and dependency discovery, & knowledge retrieval

## Demo
![Image](https://github.com/user-attachments/assets/cb5bada0-179a-4e28-852c-8d75f38405bd)

## HIGH LEVEL ARCHITECTURE
### OVERVIEW
The application allows users to add their code repo (.py, .NET only supported). This application is a 4-stage pipeline designed to understand large codebases (.py, .NET, etc.) by combining:
** AST-based code parsing, ** Neo4j graph ingestion, **Vector database–based semantic retrieval, **Hybrid RAG orchestration.
This enables the system to answer code-related queries such as dependencies, impact analysis, function-level questions, and architecture-level insights—all in a structured and explainable manner.

<img width="1374" height="777" alt="image" src="https://github.com/user-attachments/assets/af9152f2-2890-4926-9654-504ec986623e" />


## Tech Stack
* AST Parsers: Python AST, Roslyn (.NET), Language-specific parsers,
* Vector DB: FAISS,,
* Graph DB: Neo4j,
* RAG Framework: LangGraph,
* LLM Layer: OpenAI / Azure / Anthropic (configurable)


© 2025 Shree Sudame. All rights reserved. This repository showcases the conceptual workflow, architecture, and demonstration of the project for portfolio purposes. The underlying source code, internal scripts, datasets, and configurations are not included due to confidentiality agreements and organizational policies. Unauthorized use, reproduction, or distribution of the materials in this repository is strictly prohibited.
