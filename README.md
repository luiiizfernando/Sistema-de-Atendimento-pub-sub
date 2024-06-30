# Sistema de Atendimento Distribuído utilizando pub-sub

Este projeto foi desenvolvido como parte das disciplinas ECOS02 (Sistemas Distribuídos) e ECOS012 (Laboratório de Sistemas Distribuídos). O sistema consiste em uma aplicação de atendimento que utiliza tecnologias como Node.js, Express, Google Cloud Pub/Sub e Nodemailer.

## Estrutura do Projeto

O projeto está organizado da seguinte maneira:

sistema-de-atendimento/
│
├── backend/
│ ├── auth.js
│ ├── package-lock.json
│ ├── package.json
│ ├── server.js
│ └── service-account-key.json
│
└── frontend/
├── node_modules/
├── public/
│ ├── cliente.html
│ ├── dashboard.html
│ ├── details.html
│ ├── login.html
│ ├── style.css
│ ├── cliente.js
│ ├── dashboard.js
│ ├── details.js
│ └── login.js
└── package.json


## Funcionalidades Principais

- **Login:** Autenticação de usuários com autenticação simples.
- **Abertura de Chamados:** Formulário para criação de novos chamados com diferentes tipos de problema.
- **Dashboard:** Visualização e gestão dos chamados abertos.
- **Respostas por Email:** Sistema integrado para enviar respostas aos usuários por email.
- **Desconexão Segura:** Possibilidade de deslogar do sistema de forma segura.

## Configuração

### Pré-requisitos

- Node.js instalado
- Conta no Google Cloud Platform com acesso ao Pub/Sub

### Instalação e Execução

1. **Backend:**

   ```bash
   cd backend/
   npm install
   node server.js

2. **Frontend:**

   cd frontend/
   npm install
   npm start



