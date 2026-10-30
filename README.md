Estrutura do Projeto
Agenda de Investimentos

Aplicação web para registar, organizar e acompanhar investimentos pessoais, permitindo controlar o capital investido, os rendimentos esperados e as datas de recebimento.

Objetivos

- Centralizar informações sobre diferentes tipos de investimentos.
- Acompanhar o capital aplicado e os rendimentos.
- Organizar datas de vencimento e recebimento.
- Consultar o histórico de transações financeiras.
- Visualizar um resumo da carteira de investimentos.

Funcionalidades previstas

- Gestão de investimentos: registo, consulta, edição e remoção de investimentos.
- Diversidade de ativos: ações, títulos, fundos de investimento, imóveis, depósitos a prazo, renda fixa, criptomoedas e outras categorias.
- Previsão de rendimentos: estimativa de retornos com base nos dados fornecidos pelo utilizador.
- Calendário financeiro: organização das datas previstas para pagamentos e recebimentos.
- Controlo de transações: registo de aplicações, reforços, levantamentos e rendimentos recebidos.
- Painel de controlo: resumo dos investimentos, capital aplicado e próximos recebimentos.
- Histórico financeiro: consulta das operações realizadas.

Tecnologias

Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Recharts

Backend

- Node.js
- TypeScript
- Express
- Prisma ORM
- Zod

Base de dados

- PostgreSQL

Testes

- Vitest
- Supertest

Estrutura do Projeto

- "frontend/" — interface e componentes visuais da aplicação.
- "backend/" — API, regras de negócio, autenticação e acesso à base de dados.
- "backend/prisma/" — modelo e migrações da base de dados.
- "backend/tests/" — testes unitários e de integração.
- "docs/" — documentação, requisitos, diagramas e documentação dos testes.

Regras financeiras

- O capital investido deve ser distinguido dos rendimentos.
- As previsões devem basear-se nos dados fornecidos pelo utilizador.
- Taxas, impostos e comissões não devem ser presumidos quando não forem conhecidos.
- Investimentos em moedas diferentes devem ser apresentados separadamente, salvo quando existir uma taxa de conversão definida.
- Os rendimentos estimados devem ser distinguidos dos valores efetivamente recebidos.
- Investimentos sem data de vencimento devem poder ser registados.

Instalação e execução

As instruções de instalação e execução serão adicionadas após a configuração dos ambientes do frontend, backend e PostgreSQL.

Estado do Projeto

Em desenvolvimento.

As funcionalidades descritas representam os objetivos previstos e não significam que todas já estejam implementadas.

Contribuição

1. Cria um fork do repositório.
2. Cria uma branch para as tuas alterações.
3. Implementa e testa as alterações.
4. Envia um Pull Request com uma descrição clara do que foi alterado.

Licença

A licença do projeto será definida posteriormente.


- frontend/
  
  - src/
    - "assets/"
    - components/
      - "layout/"
      - "forms/"
      - "charts/"
      - "ui/"
    - "pages/"
    - "hooks/"
    - "contexts/"
    - "routes/"
    - "services/"
    - "types/"
    - "utils/"

- backend/
  
  - prisma/
    - "migrations/"
  - src/
    - "config/"
    - modules/
      - "auth/"
      - "users/"
      - "investments/"
      - "transactions/"
      - "payments/"
      - "valuations/"
      - "notifications/"
      - "dashboard/"
    - domain/
      - financial/
        - "calculations/"
        - "rules/"
    - "middlewares/"
    - "utils/"
  - tests/
    - "unit/"
    - "integration/"

- docs/
  
  - "requisitos/"
 

  - "diagramas/"
  - "arquitetura/"
  - "testes/"
