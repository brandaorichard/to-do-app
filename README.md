# Task Manager - Fullstack MERN App

Este é um projeto fullstack desenvolvido com a stack MERN (MongoDB, Express, React, Node.js) que permite criar, listar e gerenciar tarefas de forma simples e eficiente.

## 🧠 Funcionalidades

- ✅ Criar tarefas
- 📝 Listar tarefas
- ✏️ Editar tarefas
- ❌ Deletar tarefas
- ❌/✅ Alternar tarefa concluída/não concluída

## 🛠️ Tecnologias Utilizadas

### Frontend
MERN STACK
- [React/Vite]
- [JavaScript]
- [Tailwind CSS]
- [React Icons]

### Backend
- [Node.js]
- [Express]
- [MongoDB]
- [Mongoose]

## 🗂️ Estrutura de Pastas

```
root/
│
├── frontend/                # Frontend React
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── App.tsx
│       └── main.tsx
│
├── backend/                # Backend Node.js
│   ├── config/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── app.js
│
├── package.json           # Dependências monorepo
└── README.md              # Este arquivo
```

## 🚀 Como rodar o projeto

### Pré-requisitos

- Node.js v18+
- MongoDB instalado ou MongoDB Atlas

### Clonando o repositório

```bash
git clone https://github.com/seu-usuario/task-manager.git
cd task-manager
```

### Instalando as dependências

```bash
npm install
```

### Rodando o servidor

```bash
cd server
npm run dev
```

### Rodando o cliente

```bash
cd client
npm run dev
```

## 🔐 Variáveis de Ambiente

Crie um arquivo `.env` na pasta `server` com o seguinte conteúdo:

```
PORT=5000
MONGO_URI=coloque_aqui_sua_string_de_conexao
```

## 📦 Scripts

Na raiz do projeto:

```bash
npm run dev     # Inicia client e server simultaneamente (se configurado com concurrent)
npm run lint    # Executa lint com ESLint
```

## ✍️ Autor

Ricardo Brandão  
Desenvolvedor Fullstack
[LinkedIn](https://www.linkedin.com/in/ricardo-brandao-dev)
[Portfolio](https://ricardobrandaodev.com/)

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
