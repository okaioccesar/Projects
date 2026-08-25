# Projects

# GymManager

O **GymManager** é uma aplicação web desenvolvida para auxiliar academias no gerenciamento de alunos, professores, planos, treinos, pagamentos e frequência.

O projeto tem como objetivo centralizar informações importantes da academia em uma única plataforma, facilitando tarefas administrativas e proporcionando uma experiência mais organizada tanto para os profissionais quanto para os alunos.

> **Status:** Projeto em desenvolvimento.

## Objetivo

Desenvolver uma solução Full Stack que simule um sistema real de gerenciamento de academia, aplicando conceitos de desenvolvimento web, engenharia de software, banco de dados, APIs e boas práticas de programação.

## Funcionalidades planejadas

- Cadastro e autenticação de usuários
- Dashboard administrativo
- Cadastro e gerenciamento de alunos
- Cadastro e gerenciamento de professores
- Criação e gerenciamento de treinos
- Cadastro de exercícios
- Associação de treinos aos alunos
- Gerenciamento de planos e mensalidades
- Controle de pagamentos
- Controle de frequência dos alunos
- Acompanhamento da evolução dos alunos

## Tecnologias

### Frontend

- React
- TypeScript
- HTML
- CSS
- Vite

### Backend

- Node.js
- TypeScript
- Express

### Banco de Dados

- PostgreSQL

### Ferramentas

- Visual Studio Code
- Git
- GitHub
- Postman

## Arquitetura

O projeto será dividido inicialmente em duas aplicações principais:

```text id="vmlpvj"
GymManager/
│
├── frontend/
│   └── Interface da aplicação
│
├── backend/
│   └── API e regras de negócio
│
└── README.md
```

A comunicação seguirá inicialmente a seguinte estrutura:

```text id="ybxgxi"
Frontend
   ↓
REST API
   ↓
Backend
   ↓
PostgreSQL
```

## Principais entidades

O banco de dados será estruturado em torno de entidades como:

```text id="z4s0xn"
Usuário
├── Aluno
└── Professor

Aluno
├── Matrícula
├── Plano
├── Treino
├── Pagamento
└── Frequência

Treino
└── Exercícios
```

## Roadmap

### 1. Estrutura inicial

- [ ] Configurar o projeto
- [ ] Criar frontend
- [ ] Criar backend
- [ ] Configurar banco de dados

### 2. Sistema administrativo

- [ ] Dashboard
- [ ] Gerenciamento de alunos
- [ ] Gerenciamento de professores
- [ ] Gerenciamento de planos

### 3. Sistema de treinos

- [ ] Cadastro de exercícios
- [ ] Criação de treinos
- [ ] Associação de treinos aos alunos

### 4. Gestão da academia

- [ ] Controle de frequência
- [ ] Controle de mensalidades
- [ ] Histórico de pagamentos

### 5. Melhorias futuras

- [ ] QR Code para check-in
- [ ] Gráficos de evolução
- [ ] Notificações de mensalidade
- [ ] Área exclusiva do aluno
- [ ] Responsividade para dispositivos móveis

## Motivação

O GymManager foi criado como um projeto de estudo e portfólio, com foco no desenvolvimento de uma aplicação próxima de um cenário real.

Durante o desenvolvimento serão aplicados conceitos de **Engenharia de Software**, **Análise e Desenvolvimento de Sistemas**, desenvolvimento Full Stack, modelagem de banco de dados, APIs REST, autenticação, versionamento de código e organização de projetos.

## Aprendizados

Durante o desenvolvimento deste projeto serão trabalhados conhecimentos como:

- Desenvolvimento Frontend
- Desenvolvimento Backend
- APIs REST
- Banco de dados relacional
- Modelagem de dados
- Autenticação e autorização
- Git e GitHub
- Arquitetura de software
- Boas práticas de desenvolvimento

## Autor

**Kaio Cesar de Sousa Silva**

Estudante de Análise e Desenvolvimento de Sistemas e Engenharia de Software.

Projeto desenvolvido com foco em aprendizado, evolução profissional e desenvolvimento Full Stack.