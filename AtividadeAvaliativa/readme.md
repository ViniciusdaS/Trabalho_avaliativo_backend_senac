# 📦 Atividade avaliativa de backend

Este projeto é uma aplicação Node.js com TypeScript que permite o gerenciamento de usuários e eventos, incluindo funcionalidades completas de CRUD. A estrutura segue o padrão MVC (Model-View-Controller), utilizando Express, TypeORM e outras bibliotecas essenciais.

## 🛠️ Tecnologias Utilizadas

- [Node.js]
- [TypeScript]
- [Express]
- [TypeORM]
- [bcrypt]
- [@types/*]


## 📁 Estrutura do Projeto

├── src/
│ ├── controller/ # Lógica das rotas e funções CRUD
│ ├── model/ # Modelos TypeORM para as tabelas (usuarios e eventos)
│ ├── view/ # Arquivos relacionados à visualização (integração com HTML)
│ ├── public/ # Telas HTML e arquivos estáticos (CSS, JS, imagens)
│ ├── routes.ts # Definição das rotas
│ └── server.ts # Inicialização do servidor
├── tsconfig.json # Configuração do TypeScript
├── package.json # Dependências e scripts
└── README.md # Documentação do projeto


🧪 Funcionalidades

✅ Cadastro, visualização, edição e atualização de usuários

✅ Criação e gerenciamento de eventos e de usuários

✅ Visualização de dados

✅ Criptografia e hash de senhas com bcrypt

✅ Requisitos: Node.js 

✅ Banco de dados (ex: PostgreSQL ou SQLite)


📌 Observações

Os modelos (model/) estão alinhados com as tabelas do banco de dados.

As rotas HTTP utilizam Express.Request e Express.Response com tipagem correta.

As telas são renderizadas utilizando HTML localizado em public/.

✍️ Autor
**Vinicius**

