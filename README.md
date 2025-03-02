# CodeCraft Summit 2025 - NLW Connect - Nextjs

![Next.js](https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS - V4](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-8B5CF6?style=for-the-badge)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge)

A aplicação é focada em facilitar a inscrição no CodeCraft Summit 2025, com um design moderno e funcionalidades extras como programa de indicação e gamificação. Esse projeto foi desenvolvido atrevés do NLW Pocket oferecido pela [Rocketseat](https://github.com/rocketseat-education).

## Screenshots

<div style="text-align: center;">
  <img src='./public/Desktop.png' width="400" alt="Home Page Preview" />
</div>

<div style="text-align: center;">
  <img src='./public/Event.png' width="400" alt="My Account Page Preview" />
</div>

<div style="text-align: center;">

<img src='./public/Mobile-Home.png' width="200" alt="My Tickets Page Preview" style="margin-bottom: 180;"> />
<img src='./public/Mobile.png' width="200" alt="My Tickets Page Preview" />

</div>

<div style="text-align: center;">
 
</div>

## Tecnologias Utilizadas

- **Next.js** - Framework para React com renderização híbrida e otimização de desempenho.
- **TypeScript** - Superset tipado do JavaScript para um código mais seguro e escalável.
- **React Hook Form** - Gerenciamento eficiente de formulários em React.
- **Zod** - Validação e tipagem de dados de entrada.
- **TailwindCSS** - Biblioteca para estilização baseada em utilitários.
- **Axios** - Cliente HTTP para interação com a API.

## Repositório do Backend

O backend do projeto está disponível em:
[Ticket Hub - Backend](https://github.com/rocketseat-education/nlw-connect-node)

## Como Rodar o Projeto

### Requisitos

- Node.js 20+
- pnpm(de preferência),npm ou yarn

### Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/ismael-henrique-dev/Nlw-Connect-Nextjs.git
   cd nlw-connect
   ```

2. Instale as dependências:

   ```bash
   pnpm install
   # ou
   yarn install
   ```

3. Execute o projeto em ambiente de desenvolvimento:

   ```bash
   pnpm dev
   # ou
   npm run dev
   # ou
   yarn dev
   ```

4. O projeto estará disponível em: [http://localhost:3000](http://localhost:3000)

## Estrutura do Projeto

A estrutura do projeto segue uma organização modularizada:

```
/ticket-hub
├── .next              # Build do Next.js
├── node_modules       # Dependências do projeto
├── public             # Arquivos estáticos
├── src
│   ├── app           # Rotas e páginas do Next.js
│   ├── assets        # Arquivos de mídia
│   ├── components    # Componentes reutilizáveis
│   
├── .gitignore        # Arquivos ignorados pelo Git
├── next-env.d.ts     # Definições do ambiente Next.js
├── next.config.ts    # Configurações do Next.js
├── package.json      # Dependências e scripts do projeto
├── tsconfig.json     # Configuração do TypeScript
├── postcss.config.mjs# Configuração do PostCSS
└── README.md         # Documentação do projeto
```

## Aprendizados

Durante o desenvolvimento do **NLW Connect**, aprendi e apliquei conceitos importantes:

- **Gerenciamento de formulários** com React Hook Form e validação com Zod.
- **Estilização eficiente** com TailwindCSS V4 e novas features do mesmo.
- **Gerenciamento de estado e requisições** usando Axios.
- **Melhores práticas de tipagem** no TypeScript para um código mais robusto.
- **Organização do Next.js**, utilizando `app` directory para um código modular.

## Funcionalidades

- **Criar incrinção no evento** – Simulação do processo de incrição ao evento.
- **Ver ranking** – Possibilidade de ver as quantias de pessoas que compartilharam seu link.

---

Caso tenha dúvidas ou sugestões, sinta-se à vontade para abrir uma issue ou entrar em contato.
