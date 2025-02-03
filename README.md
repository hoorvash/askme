## 🛠 Overview

This is a **work-in-progress** tool designed to analyze Java projects, generate concise descriptions, and answer questions about the project using **Retrieval-Augmented Generation (RAG)** technology.

### ✨ Features (So Far)
- ✅ Extracts **classes, methods, and API endpoints** from Java projects.
- ✅ Generates **summaries** explaining each file’s purpose.
- ✅ Stores extracted knowledge in a **vector database** for retrieval.
- ✅ Allows **natural language queries** about the project.

### 🔥 Upcoming Features
- [ ] **Support for more languages** (e.g., Python, JavaScript)
- [ ] **Better API documentation parsing**
- [ ] **More accurate project type detection (CLI, Web App, etc.)**

## 🚀 How It Works
1. **Extract Code Structure**: Analyzes Java/Kotlin files to find classes, methods, and API endpoints.
2. **Summarization**: Uses OpenAI’s models to generate a description.
3. **Knowledge Storage**: Saves the structured summaries in a **vector database**.
4. **Query Engine**: Lets you ask questions like _"What does this project do?"_

