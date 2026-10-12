<h1 align="center">Olá! 👋 Sou o Samuel Santana</h1>

<h3 align="center">Senior Software Engineer | Frontend-focused (React/Angular) | Full Stack com Node.js & NestJS</h3>

<p align="center">
  Engenheiro de Software Sênior focado na arquitetura de soluções web de alto impacto e performance, com atuação ponta a ponta em plataformas multi-tenant SaaS. Diretamente de Salvador, Bahia ☀️.
</p>

<p align="center">
  <a href="https://linkedin.com/in/samuelcsantana" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:samuel.ssa89@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.samuelsantana.dev/" target="_blank">
    <img src="https://img.shields.io/badge/Blog_&_Website-20232A?style=for-the-badge&logo=dev.to&logoColor=white" alt="Blog">
  </a>
</p>

---

### 🚀 O Que Eu Faço & Impacto Técnico

Acredito que código bom é aquele que resolve problemas reais. Nos últimos anos, tenho focado em liderança técnica e modernização de arquiteturas complexas:

*   **Arquitetura de Software:** Implementação de ecossistemas de **Micro-frontends (Module Federation)**, reduzindo em cerca de **40% o tempo de build** e permitindo deploys independentes.
*   **Performance:** Adoção de padrões reativos modernos (como **Angular Signals**), alcançando melhorias de até **50% no tempo de renderização** e mitigando gargalos.
*   **Sistemas SaaS:** Liderança na transição estrutural de sistemas legados para plataformas multi-tenant, garantindo isolamento de dados e filtros complexos.
*   **Ferramental Moderno:** Utilização de **Spec-Driven Development (SDD)** auxiliado por IA (GitHub Copilot, Claude Code) para escalar a qualidade e velocidade de entrega.

---

### 💼 Projetos em Destaque

**[Pyxis](https://demo.pyxis-analytics.dev)** — Analytics de produto com privacidade por construção: sem cookies, sem IP, sem user agent e sem dados pessoais. Mostra quais features são usadas, onde as requisições falham, onde um funil de cadastro perde gente e o que uma pessoa fez, em ordem. Em produção desde outubro de 2026, medindo o [BolsoVerde](https://bolsoverde.com) e o [meu blog](https://www.samuelsantana.dev/). [Demo ao vivo](https://demo.pyxis-analytics.dev) com dados inventados, sem login. Os três repositórios têm 100% de cobertura como gate de CI.
*   🔧 [`pyxis-api`](https://github.com/samuelcsantana/pyxis-api) — NestJS + Fastify em AWS Lambda atrás do CloudFront, infraestrutura em Terraform, Drizzle/PostgreSQL e Clean Architecture. Ingestão em lote com rate limit, apagamento dos dados de uma pessoa (LGPD), retenção e resumo semanal por e-mail. [Referência da API](https://samuelcsantana.github.io/pyxis-api/).
*   📦 [`pyxis-sdk`](https://github.com/samuelcsantana/pyxis-sdk) — Rastreador para o navegador publicado no npm como [`pyxis-analytics`](https://www.npmjs.com/package/pyxis-analytics), com provenance, zero dependências e orçamento de 5 KB gzip verificado no CI. [Playground](https://samuelcsantana.github.io/pyxis-sdk/).
*   🎨 [`pyxis-web`](https://github.com/samuelcsantana/pyxis-web) — Painel em Next.js 16 com gráficos SVG renderizados no servidor, em inglês e português, testado com Playwright + axe (WCAG 2.2). [Storybook](https://samuelcsantana.github.io/pyxis-web/).

**[BolsoVerde](https://bolsoverde.com)** — Produto próprio em produção: junta as vendas de iFood, 99Food, maquininha, WhatsApp e balcão num lugar só e mostra quanto foi de taxa, o que ainda vai cair na conta e se o mês deu lucro. Código privado.
*   Frontend em Next.js 16 + React 19 na Vercel, em português, inglês e espanhol; API em NestJS + Fastify na AWS Lambda com Drizzle/PostgreSQL. Login por código no e-mail, senha ou Google, assinaturas com Stripe e exportação dos dados do usuário (LGPD).

**[Ninho](https://cygnus.samuelsantana.dev)** — App de saúde infantil: vacinas do calendário do PNI, consultas, crescimento e marcos de desenvolvimento, com acesso compartilhado entre responsáveis.
*   🎨 [`cygnus`](https://github.com/samuelcsantana/cygnus) — React 19 + Vite + TypeScript strict, em português, inglês e espanhol, com [design system público no Storybook](https://samuelcsantana.github.io/cygnus/) e acessibilidade verificada no CI.
*   🔧 [`cygnus-api`](https://github.com/samuelcsantana/cygnus-api) — Fastify 5 + Prisma 7 + PostgreSQL em camadas (domain, application, infrastructure, presentation), lembretes em fila BullMQ/Redis com retry e dead letter queue.

**[Vertex](https://github.com/samuelcsantana/vertex-web)** — Stack completa por trás do meu blog técnico, [samuelsantana.dev](https://www.samuelsantana.dev/), em português, inglês e espanhol e medido pelo Pyxis.
*   🎨 [`vertex-web`](https://github.com/samuelcsantana/vertex-web) — Frontend em Next.js 16, arquitetura server-first, i18n por sub-path, OAuth cross-domain seguro e um host de Module Federation que carrega em runtime um remote de outra origem ([demo de micro-frontends](https://www.samuelsantana.dev/micro-frontends)).
*   🔧 [`vertex-api`](https://github.com/samuelcsantana/vertex-api) — Backend em NestJS + Fastify, Drizzle/PostgreSQL, autenticação via OAuth Token Callback Pattern, API REST com rate limiting.

📦 [`rx-state-bridge`](https://github.com/samuelcsantana/rx-state-bridge) — Lib open-source ([npm](https://www.npmjs.com/package/rx-state-bridge)) de operadores RxJS zero-dependency para conectar streams assíncronos a Angular Signals, React Hooks e Vue Refs, com foco em memory-safety (teardown determinístico via `finalize`) e tipagem forte sem `any`.

**Outros:** [Vela](https://github.com/samuelcsantana/vela-core), SaaS multi-tenant com isolamento de dados por tenant, JWT em cookie httpOnly e RBAC em 3 níveis ([`vela-core`](https://github.com/samuelcsantana/vela-core) em Fastify 5 + Prisma 7, [`vela-ui`](https://github.com/samuelcsantana/vela-ui) em React 19 + Rsbuild + TanStack Router/Query).

---

### 🛠️ Tech Stack & Ferramentas

**Front-end**
<p>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-20232A?style=for-the-badge&logo=react&logoColor=white" />
</p>

**Back-end & Cloud**
<p>
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>

**Qualidade & DevOps**
<p>
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/CI%2FCD-4051B5?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

---

### 📊 Meus Status no GitHub

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=samuelcsantana&theme=radium&hide_border=true" alt="Streak do Samuel" />
</p>

---

### ⚡ Além do Código

*   ✍️ **Criador de Conteúdo:** Escrevo sobre engenharia de software, arquitetura e carreira no meu [Blog Pessoal (samuelsantana.dev)](https://www.samuelsantana.dev/).
*   ☕ Apaixonado por café especial (sempre alternando entre os filtros de metal e a clássica Moka).
