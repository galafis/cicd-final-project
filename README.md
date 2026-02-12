# 🚀 Cicd Final Project

[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED.svg)](https://www.docker.com/)
[![Flask](https://img.shields.io/badge/Flask-3.0-000000.svg)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[English](#english) | [Português](#português)

---

## English

### 🎯 Overview

**Cicd Final Project** — Repositório para o projeto final do curso IBM DevOps and Software Engineering.

Total source lines: **517** across **7** files in **2** languages.

### ✨ Key Features

- **Production-Ready Architecture**: Modular, well-documented, and following best practices
- **Comprehensive Implementation**: Complete solution with all core functionality
- **Clean Code**: Type-safe, well-tested, and maintainable codebase
- **Easy Deployment**: Docker support for quick setup and deployment

### 🚀 Quick Start

#### Prerequisites
- Python 3.12+
- Docker and Docker Compose (optional)

#### Installation

1. **Clone the repository**
```bash
git clone https://github.com/galafis/cicd-final-project.git
cd cicd-final-project
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```




## 🐳 Docker

```bash
# Build the image
docker build -t cicd-final-project .

# Run the container
docker run -p 8000:8000 cicd-final-project
```

### 🧪 Testing

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov --cov-report=html

# Run with verbose output
pytest -v
```

### 📁 Project Structure

```
cicd-final-project/
├── bin/
│   └── setup.sh
├── service/
│   ├── common/
│   │   ├── error_handlers.py
│   │   ├── log_handlers.py
│   │   └── status.py
│   ├── __init__.py
│   └── routes.py
├── tests/
│   └── test_routes.py
├── README.md
├── requirements.txt
└── setup.cfg
```

### 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Python | 6 files |
| Shell | 1 files |

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 👤 Author

**Gabriel Demetrios Lafis**

- GitHub: [@galafis](https://github.com/galafis)
- LinkedIn: [Gabriel Demetrios Lafis](https://linkedin.com/in/gabriel-demetrios-lafis)

---

## Português

### 🎯 Visão Geral

**Cicd Final Project** — Repositório para o projeto final do curso IBM DevOps and Software Engineering.

Total de linhas de código: **517** em **7** arquivos em **2** linguagens.

### ✨ Funcionalidades Principais

- **Arquitetura Pronta para Produção**: Modular, bem documentada e seguindo boas práticas
- **Implementação Completa**: Solução completa com todas as funcionalidades principais
- **Código Limpo**: Type-safe, bem testado e manutenível
- **Fácil Implantação**: Suporte Docker para configuração e implantação rápidas

### 🚀 Início Rápido

#### Pré-requisitos
- Python 3.12+
- Docker e Docker Compose (opcional)

#### Instalação

1. **Clone the repository**
```bash
git clone https://github.com/galafis/cicd-final-project.git
cd cicd-final-project
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```




### 🧪 Testes

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov --cov-report=html

# Run with verbose output
pytest -v
```

### 📁 Estrutura do Projeto

```
cicd-final-project/
├── bin/
│   └── setup.sh
├── service/
│   ├── common/
│   │   ├── error_handlers.py
│   │   ├── log_handlers.py
│   │   └── status.py
│   ├── __init__.py
│   └── routes.py
├── tests/
│   └── test_routes.py
├── README.md
├── requirements.txt
└── setup.cfg
```

### 🛠️ Stack Tecnológica

| Tecnologia | Uso |
|------------|-----|
| Python | 6 files |
| Shell | 1 files |

### 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

### 👤 Autor

**Gabriel Demetrios Lafis**

- GitHub: [@galafis](https://github.com/galafis)
- LinkedIn: [Gabriel Demetrios Lafis](https://linkedin.com/in/gabriel-demetrios-lafis)
