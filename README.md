# Introdução ao Flask para APIs RESTful

Este repositório contém exemplos e anotações para quem está começando com o **Flask**, um microframework em Python, com foco na construção de **APIs RESTful**.

## 📚 Objetivo

Fornecer uma introdução prática e simples ao Flask para quem deseja construir APIs RESTful, com passos organizados para facilitar o aprendizado progressivo.

---

## 🚀 Pré-requisitos

- Python 3.11 ou superior
- pip (gerenciador de pacotes Python) ou Poetry
- Chome (Ou seu navegador Preferido)
- Insomnia (para fazer chamadas Rest)
- Virtualenv (opcional, mas recomendado)

---

## 🔧 Instalação do ambiente

```bash
# Clone o repositório
git clone https://github.com/Caco0/Introdu-o-ao-Flask-para-APIs-RESTful.git
cd nome-do-repositorio

# Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt
```

---

## 📝 Etapas de Aprendizado

### 1. 🔹 Introdução ao Flask
- O que é o Flask?
- Instalação e primeiro "Hello World"
- Estrutura básica de uma aplicação Flask

### 2. 🔹 Rotas e Métodos HTTP
- Criando rotas com `@app.route`
- Lidando com métodos GET, POST, PUT, DELETE

### 3. 🔹 Criando uma API Simples
- Retornando JSON com `Flask jsonify`
- Recebendo dados do cliente (form/json)

### 4. 🔹 Organização do Projeto
- Separando app em arquivos/modularização
- Usando `Blueprints` (básico)

### 5. 🔹 Persistência com Banco de Dados (Opcional)
- Conectando com SQLite usando `Flask-SQLAlchemy`
- CRUD básico com banco de dados

### 6. 🔹 Tratamento de Erros e Respostas
- Status codes personalizados
- Mensagens de erro com `abort` e `make_response`

### 7. 🔹 Testes Básicos com Flask
- Testando rotas com `Flask test_client`

---

## 📂 Estrutura do Projeto (exemplo)

```
.
├── app.py
├── requirements.txt
└── README.md
```

---

## ✅ Referências

- [Documentação oficial do Flask](https://flask.palletsprojects.com/)
- [REST API com Flask – Miguel Grinberg](https://blog.miguelgrinberg.com/)

---

## 📬 Contato

Se tiver dúvidas ou sugestões, fique à vontade para abrir uma _issue_ ou enviar um _pull request_!
