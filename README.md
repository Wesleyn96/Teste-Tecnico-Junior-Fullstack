
Cadastro de Clientes e Endereços
Este projeto consiste em uma aplicação Fullstack desenvolvida para o gerenciamento de clientes e seus respectivos endereços. A solução foi projetada priorizando a organização do código, a separação de responsabilidades e a experiência do usuário.

Tecnologias Utilizadas
Backend
Runtime: Node.js com TypeScript

Framework: Express (ou o framework utilizado)

ORM: Prisma

Banco de Dados: PostgreSQL (ou MongoDB)

Frontend
Framework: React com Vite e TypeScript

Interface: Tailwind CSS e shadcn/ui

Formulários: React Hook Form e Zod (validação)

Requisições: Axios

Funcionalidades Implementadas
Relacionamento 1:N: Estrutura que permite vincular múltiplos endereços a um único cliente.

Integração ViaCEP: Preenchimento automático de rua, bairro e cidade ao informar o CEP, otimizando o cadastro de endereços.

Diferenciação PF/PJ: O formulário alterna dinamicamente entre os campos de CPF e CNPJ, incluindo validações específicas para cada tipo.

Gestão de Clientes: CRUD completo com campos de nome, e-mail, WhatsApp e tipo de pessoa.

Sistema de Busca e Filtros: Listagem com pesquisa por nome ou e-mail e filtragem por período de data.

Instruções de Execução
Configuração de Ambiente
Antes de iniciar, certifique-se de configurar as variáveis de ambiente no arquivo .env dentro da pasta do backend (ex: DATABASE_URL).

Backend
Navegue até a pasta do servidor:

Bash
cd backend
Instale as dependências:

Bash
npm install
Execute as migrações do banco de dados:

Bash
npx prisma migrate dev
Inicie o serviço:

Bash
npm run dev
Frontend
Navegue até a pasta da interface:

Bash
cd frontend
Instale as dependências:

Bash
npm install
Inicie a aplicação:

Bash
npm run dev
Arquitetura e Boas Práticas
O projeto foi estruturado seguindo o Service Pattern e princípios do SOLID. A lógica de negócio está concentrada em camadas de serviço, o que desativa a dependência direta das rotas em relação à persistência de dados.

Destaques da implementação:

Clean Code: Nomenclatura clara de variáveis e funções.

Tipagem Estrita: Uso de interfaces e tipos do TypeScript em todo o fluxo de dados.

Componentização: Interface construída com componentes reutilizáveis para garantir consistência visual.