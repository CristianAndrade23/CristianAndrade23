# Olá, eu sou o Cristian 👋

**Desenvolvedor Front-end Angular** em Porto Alegre/RS · **buscando nova oportunidade**

Construo aplicações em **Angular moderno**: componentes standalone, **signals**, **Signal Forms** e change detection **zoneless**, com testes unitários e E2E e deploy contínuo. Também escrevo as APIs que os meus fronts consomem, em **Node/Express** e **Java/Spring Boot**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cristian-andrade-b26684119/)
[![E-mail](https://img.shields.io/badge/E--mail-cristian.a.s.andrade%40hotmail.com-0078D4?logo=microsoftoutlook&logoColor=white)](mailto:cristian.a.s.andrade@hotmail.com)

## Projetos

Todos têm **demo online**: abrem direto no navegador, sem instalar nada.

| Projeto | O que é | Stack | |
|---|---|---|---|
| **[Meat](https://github.com/CristianAndrade23/MeatApp)** | App de delivery no estilo iFood: cardápio com opções e adicionais, sacola, checkout em etapas, conta e avaliações | Angular 22 · Express · JWT · Cypress | [▶ Demo](https://cristianandrade23.github.io/MeatApp/) |
| **[Estaciona](https://github.com/CristianAndrade23/frontend-estacionamento)** | Gestão de estacionamento: pátio com cobrança por faixa, caixa por turno, perfis de acesso e relatórios | Angular 22 · Java 25 · Spring Boot 4 · JUnit | [▶ Demo](https://cristianandrade23.github.io/frontend-estacionamento/) |
| **[AgroPainel](https://github.com/CristianAndrade23/agro-painel)** | Painel administrativo agrícola: assinaturas, custos de lavouras e comparação de safras | Angular 22 · Express · JWT · Cypress | [▶ Demo](https://cristianandrade23.github.io/agro-painel/) |
| **[AgroPainel · Site](https://github.com/CristianAndrade23/novo-site-cerealiza)** | Landing page do produto, com abas acessíveis e cadastro com Signal Forms | Angular 22 · Vitest · Cypress | [▶ Demo](https://cristianandrade23.github.io/novo-site-cerealiza/) |
| **[Forttiori IT](https://github.com/CristianAndrade23/site-forttiori)** | Site institucional migrado de Angular 7 para Angular 22 | Angular 22 · Bootstrap 5 · Vitest | [▶ Demo](https://cristianandrade23.github.io/site-forttiori/) |

Os logins de demonstração estão no README de cada projeto.

<details>
<summary><b>Como os projetos são feitos</b></summary>

- **Angular atual de ponta a ponta:** sem `NgModule`, estado em signals (`signal`, `computed`, `linkedSignal`), `httpResource` para leitura, rotas lazy, guards e interceptors funcionais.
- **Testes em camadas:** Vitest nos componentes e regras, testes de API (`node:test` e JUnit/MockMvc) e Cypress nos fluxos principais, todos rodando no GitHub Actions a cada push.
- **Demos sem servidor:** nos projetos com backend, a versão publicada roda a API dentro do navegador com as mesmas regras de negócio. No Estaciona, a paridade com a API Java foi conferida rota a rota.
- **Acessibilidade e UI próprias:** `<dialog>` nativo, navegação por teclado, ARIA, tema escuro e CSS com design tokens, sem bibliotecas de componentes.

</details>

## Stack

**Front-end:** Angular · TypeScript · RxJS · HTML · CSS
**Back-end:** Node.js · Express · Java · Spring Boot · PostgreSQL
**Testes e entrega:** Vitest · Cypress · JUnit · GitHub Actions · Docker
