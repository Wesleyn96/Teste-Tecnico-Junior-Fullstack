# 🧪 Teste Prático - Desenvolvedor Fullstack Júnior

## 📝 Descrição do Desafio
Desenvolver uma aplicação web para cadastro de Cliente e Endereços. 

---

## 📋 Requisitos Funcionais 
- O usuário deve ser capaz de criar clientes e vincular um ou mais endereços a ele
- O usuário deve ser capaz de cadastrar e editar endereços usando a API [ViaCEP](https://viacep.com.br/) e obter os dados de endereço automaticamente
- O usuário deve ser capaz de escolher entre cadastrar um cliente que é pessoa física (CPF) ou jurídica (CNPJ)
- O usuário deve ser capaz de editar e excluir dados do cliente e endereços
- O usuário deve ser capaz de buscar clientes
- O usuário deve ser capaz de realizar busca por nome ou email, e filtrar dados por data

---

## ⚙️ Requisitos Técnicos

### Observações Importantes
- Os requisitos listados abaixo são **obrigatórios**, mas funcionalidades extras que agreguem **usabilidade, performance ou segurança** serão bem-vindas e avaliadas positivamente.
- O candidato deve estar preparado para **explicar suas escolhas técnicas** (bibliotecas, padrões de arquitetura, banco de dados, etc.) e **como essas escolhas foram aplicadas** no projeto. 

---

### Backend
- **Stack**: Node.js + Typescript (uso de framework é permitido)
- **Banco de dados**: PostgreSQL ou MongoDB

#### Banco de Dados (Campos mínimos)
**Cliente**
- nome (obrigatório)  
- email (obrigatório)  
- whatsapp  
- tipo: [CPF/CNPJ] (obrigatório)  
- cpf  
- cnpj  

**Endereço**
- cep  
- rua  
- bairro  
- cidade  

---

### Frontend
- **Stack**: React + Vite + [shadcn/ui](https://ui.shadcn.com/)

---

## 🤖 Uso de Inteligência Artificial (IA)
O uso de ferramentas de **IA** (como ChatGPT, Copilot, etc.) é **permitido**, mas com as seguintes regras:
- **Não é permitido** utilizar IA para **gerar código completo** ou **copiar soluções prontas**.
- O uso é permitido para:
  - Consultar dúvidas conceituais
  - Pesquisar boas práticas
  - Obter explicações ou comparações de abordagens
- O candidato deve ter **total domínio** sobre as escolhas técnicas realizadas, demonstrando capacidade de explicar:
  - **Por que** optou por determinada solução
  - **Como** ela foi implementada dentro do projeto

---

## 🌟 Diferenciais

### Backend
- Organização do código seguindo boas práticas e clean-code
- Virtualização do ambiente (Docker)
- Uso de **ORM** (Prisma, Sequelize, Mongoose, etc.)

### Frontend
- Uso de **React Hook Form** para gerenciamento de formulários
- Uso de **React Query** para requisições e cache de dados
- UI responsiva e amigável

---

## 📦 Entrega

1. O candidato deve **clonar o repositório base** fornecido pela empresa.  
2. Após finalizar o desafio, deverá **subir o código em um repositório público** no GitHub.  
3. Enviar o **link do repositório finalizado** para avaliação.  

O repositório deve conter um **README.md** com:
- Passos para rodar o backend
- Passos para rodar o frontend

---

## ✅ Critérios de Avaliação
- Cobertura de requisitos funcionais
- Busca e filtros funcionando corretamente
- Organização do código e boas práticas
- Estruturação do projeto
- Clareza na documentação (`README.md`)
- Capacidade de explicar e justificar as escolhas técnicas

---

## ⏱️ Prazo
- **5 dias corridos** após receber o desafio.  

Qualquer dúvida, fique à vontade para nos perguntar pelo canal de comunicação da vaga.  
Boa sorte 🚀
