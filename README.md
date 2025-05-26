# 📚 Lista de Aulas - Projeto com Fetch API

Este projeto é uma aplicação web simples que permite **visualizar, adicionar, editar e excluir** registros de aulas utilizando a **Fetch API** com os métodos HTTP `GET`, `POST`, `PUT` e `DELETE`.

## 🚀 Funcionalidades

- ✅ Listar todas as aulas registradas
- ➕ Adicionar uma nova aula
- ✏️ Editar o título ou conteúdo de uma aula
- 🗑️ Excluir uma aula do sistema

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- [JSON Server](https://github.com/typicode/json-server) (para simular uma API REST)

## 📦 Estrutura do projeto

FETCH API - PUT E DELETE/
│
├── index.html # Estrutura da página
├── style.css # Estilização dos elementos (cards, botões, formulário)
├── script.js # Lógica principal com integração via Fetch API
└── db.json # (Usado pelo JSON Server como "banco de dados")

## ▶️ Como rodar o projeto

1. **Clonar o repositório ou baixar os arquivos**
2. Instalar o JSON Server globalmente, se ainda não tiver:

```bash
npm install -g json-serverAbrir o index.html em seu navegador.

🔧 Observações
Os métodos PUT e DELETE são acionados por botões de Editar e Excluir, presentes nos cards de cada aula.

A edição pode ser feita inline ou por meio de um formulário, dependendo da versão do código.

O projeto serve como uma introdução prática à manipulação de dados em APIs REST usando JavaScript puro.
