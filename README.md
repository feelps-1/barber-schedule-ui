# Crab Barber - Sistema de Agendamento de Barbearia 🦀✂️

Este projeto consiste em uma interface de usuário desenvolvida em **Angular** com **TypeScript** para gerenciar agendamentos e clientes de uma barbearia fictícia chamada **Crab Barber**.

## 🚀 Funcionalidades Principais

- **Agendamento de Clientes**: Interface para criar novos agendamentos, escolhendo data, horário e cliente.
- **Listagem de Clientes**: Tela para visualizar todos os clientes cadastrados, com informações básicas.
- **Cadastro/Edição de Clientes**: Formulário para adicionar novos clientes ou editar dados existentes.

---

## 📱 Telas Implementadas

### 1. 🗓️ Tela de Agendamento
- Formulário para selecionar cliente, data e horário.
- Validação de campos obrigatórios.
- Integração com API para salvar agendamentos.
  
### 2. 👥 Tela de Listagem de Clientes
- Exibição de clientes cadastrados em tabela.
- Opções para editar ou remover clientes.
- Paginação e filtro por nome.

### 3. ✍️ Tela de Cadastro/Edição de Cliente
- Formulário para adicionar ou editar informações como nome, telefone e e-mail.
- Validação de dados.
- Reaproveitamento do mesmo componente para cadastro e edição.

---

## 🛠️ Tecnologias Utilizadas

- **Angular** – Framework principal.
- **TypeScript** – Tipagem estática para maior segurança e legibilidade.
- **Angular Material** – Estilização básica e responsiva.

---

## 📚 Habilidades Desenvolvidas no Projeto

### 🔗 Consumo de APIs
- Utilização do `HttpClient` do Angular para fazer requisições **GET**, **POST**, **PUT** e **DELETE**.
- Integração com endpoints para persistência dos dados de clientes e agendamentos.

### 🧩 Componentização
- Divisão da aplicação em componentes reutilizáveis para melhor organização e manutenção do código.
- Criação de componentes específicos para formulário de cliente, tabela de listagem e formulário de agendamento.

### 🌐 Uso de Rotas
- Configuração de rotas com `Angular Router` para navegação entre as páginas:
  - `/clients`
  - `/clientes/:id`
  - `/schedules`
  - `/schedules/:id`
  - ´/schedules/:year/:month´

### 🏗️ Boas Práticas de Arquitetura
- Separação clara entre serviços (responsáveis por comunicação com API), componentes e modelos.
- Aplicação de princípios de **Single Responsibility** e **DRY (Don't Repeat Yourself)**.

### ✅ Validação de Formulários
- Uso do **Reactive Forms** para validações síncronas e assíncronas.
- Feedback visual ao usuário em casos de erros.

---

## 📈 Possíveis Melhorias Futuras

- Implementação de autenticação para acesso restrito.
- Dashboard com estatísticas dos agendamentos.
- Integração com APIs externas para envio de notificações (SMS/WhatsApp).
- Adição de testes unitários e testes e2e com **Jasmine/Karma** e **Protractor/Cypress**.

---



