# LangChain Application for Text Processing

This repository contains a set of Jupyter notebooks designed for building applications using the LangChain framework. The focus is on text processing tasks such as text ingestion, splitting, embedding, and retrieval, leveraging state-of-the-art models and tools.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Dependencies](#dependencies)
6. [Contributing](#contributing)
7. [License](#license)

---

## Introduction
This project demonstrates the use of LangChain and its integrations for processing large text datasets. It includes steps for:
- Data ingestion and preprocessing.
- Text splitting using advanced algorithms.
- Embedding generation for semantic search.
- Retrieval and similarity matching.

---

## Project Structure
```
├── Apps_lanchain.ipynb                # Application workflow using LangChain
├── data_ingestion_and_text_splitter.ipynb # Data ingestion and text splitting
├── embeddings.ipynb                   # Embedding generation and similarity search
├── requirement.txt                    # Dependencies
├── README.md                          # Project documentation
```

---

## Installation
1. Clone the repository:
```
git clone <repository-url>
cd <repository-name>
```

2. Create a virtual environment:
```
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```
pip install -r requirement.txt
```

---

## Usage
1. Open Jupyter Notebook:
```
jupyter notebook
```
2. Execute the notebooks in the following order:
   - `data_ingestion_and_text_splitter.ipynb`: Load and preprocess data.
   - `embeddings.ipynb`: Generate embeddings and create FAISS index.
   - `Apps_lanchain.ipynb`: Implement the LangChain application workflow.

---

## Dependencies
The following dependencies are required (also listed in `requirement.txt`):
- `langchain`
- `langchain-openai`
- `ipykernel`
- `python-dotenv`
- `langchain_community`
- `pypdf`
- `langchain_text_splitters`
- `wikipedia`
- `langchain-huggingface`
- `tensorflow`
- `tf_keras`
- `faiss-cpu`

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request with a clear description of your changes.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

