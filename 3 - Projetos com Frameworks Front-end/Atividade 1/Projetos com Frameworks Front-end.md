# 🌐 Atividade 03 - Projetos com Frameworks Front-end (React, Vue, Angular e Next.js)

> **Disciplina:** Frameworks Front-end
> **Professor:** Prof. Me. Deivison S. Takatu — deivison.takatu@edu.senai.br
> **Tecnologias:** React, Vue, Angular e Next.js

![Atividade](https://img.shields.io/badge/atividade-03%20Frameworks%20Front--end-yellow)
![Tema](https://img.shields.io/badge/tema-4%20Projetos%20em%20Frameworks%20diferentes-green)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)

## 📑 Índice

1. [Resumo da Atividade](#-resumo-da-atividade)
2. [Sobre a Atividade](#-sobre-a-atividade)
3. [Projetos Desenvolvidos](#-projetos-desenvolvidos)
4. [Tecnologias Utilizadas](#-tecnologias-utilizadas)
5. [Como Executar](#-como-executar)
6. [Estrutura dos Projetos](#-estrutura-dos-projetos)
7. [Comparação entre as Tecnologias](#-comparação-entre-as-tecnologias)
8. [Checklist da Atividade](#-checklist-da-atividade)

---

## 📝 Resumo da Atividade

A Atividade 03 consiste em, em grupo, desenvolver **quatro projetos Web sobre o mesmo tema**, utilizando **React, Vue, Angular e Next.js**. Cada projeto deve apresentar uma página funcional, responsiva e organizada, empregando componentes e os recursos básicos da tecnologia escolhida. Durante o desenvolvimento, os projetos são versionados com Git e publicados no GitHub, e ao final elabora-se uma breve comparação entre as quatro tecnologias, destacando as principais diferenças encontradas.

Esta atividade exercita os conceitos de **componentização, estado, roteamento e build** abordados na Aula 3 - Projetos com Frameworks Front-end.

## 🎯 Sobre a Atividade

Conforme o enunciado da Aula 3, a entrega é composta por:

- **Projeto 01:** React
- **Projeto 02:** Vue
- **Projeto 03:** Angular
- **Projeto 04:** Next.js
- **Projeto 05:** uma cópia de um projeto a partir de um repositório (clone/modelo)

Todos os projetos devem seguir o **mesmo tema**, garantindo uma comparação justa entre as tecnologias. Cada um deve ser versionado no GitHub e publicado (deploy) na Vercel.

## 🗂️ Projetos Desenvolvidos

Os projetos foram criados a partir dos repositórios online (clonados localmente em `C:\Users\Felipe Lopes\Desktop\frontend-atividades`):

| # | Framework | Repositório (GitHub) | Deploy (Vercel) | Linguagem | Servidor de dev |
| --- | --- | --- | --- | --- | --- |
| 01 | ⚛️ React | [`projeto-react-01`](https://github.com/biancaciriloads/projeto-react-01) | ✅ [`projeto-react-01-three.vercel.app`](https://projeto-react-01-three.vercel.app) | JavaScript (JSX) | `npm start` → :3000 |
| 02 | 💚 Vue | [`projeto-vue`](https://github.com/RickRazz0/projeto-vue) | ✅ [`projeto-vue-vert.vercel.app`](https://projeto-vue-vert.vercel.app) | TypeScript (SFC) | `npm run dev` (Vite) |
| 03 | 🅰️ Angular | [`meu-app-angular`](https://github.com/Nickddb/meu-app-angular) | ✅ [`meu-app-angular-omega.vercel.app`](https://meu-app-angular-omega.vercel.app) | TypeScript | `ng serve` → :4200 |
| 04 | ▲ Next.js | [`projeto-next`](https://github.com/Felipe-Pinheiro-Lopes/projeto-next) | ✅ [`projeto-next-nu.vercel.app`](https://projeto-next-nu.vercel.app) | TypeScript (App Router) | `npm run dev` → :3000 |

> [!NOTE]
> O **Projeto 05** (cópia a partir de um repositório) será elaborado a partir de um modelo open source clonado via `git clone`, conforme orientado na Aula 3.

## 🛠️ Tecnologias Utilizadas

- **React** — biblioteca para interfaces com componentes reutilizáveis (Virtual DOM, JSX, `useState`/`useEffect`).
- **Vue** — framework progressivo com Single-File Components (`.vue`), reatividade automática e Vite.
- **Angular** — framework completo com TypeScript, MVC, CLI, injeção de dependência e Change Detection.
- **Next.js** — framework baseado em React para aplicações full-stack (SSR, roteamento por arquivos, Server Components).
- **Git e GitHub** — versionamento de código e colaboração em equipe.
- **Vercel** — deploy/hospedagem das aplicações.

## ▶️ Como Executar

Em cada pasta de projeto (dentro de `C:\Users\Felipe Lopes\Desktop\frontend-atividades`):

### React (`projeto-react-01`)
```bash
npm install
npm start
```

### Vue (`projeto-vue`)
```bash
npm install
npm run dev
```

### Angular (`meu-app-angular`)
```bash
npm install
ng serve
```

### Next.js (`projeto-next`)
```bash
npm install
npm run dev
```

## 🧩 Estrutura dos Projetos

- **React:** `public/` (estáticos), `src/` (`App.js`, componentes em `src/game/`), `package.json`.
- **Vue:** `public/`, `src/` (`App.vue`, `components/`, `main.ts`), `vite.config.ts`, `package.json`.
- **Angular:** `src/` (`app/`, `main.ts`, `index.html`, `styles.css`), `angular.json`, `tsconfig*.json`, `package.json`.
- **Next.js:** `app/` (`page.tsx`, `layout.tsx`, estilos globais), `public/`, `next.config.ts`, `package.json`.

## ⚖️ Comparação entre as Tecnologias

| Critério | React | Vue | Angular | Next.js |
| --- | --- | --- | --- | --- |
| Tipo | Biblioteca | Framework | Framework | Framework (sobre React) |
| Linguagem | JS/TS | JS/TS | TypeScript | TS/JS |
| Componentes | JSX (`.js`/`.tsx`) | SFC (`.vue`) | `@Component` (TS) | JSX (App Router) |
| Estado | `useState`/Redux | Reatividade nativa | Services + DI | `useState`/Server |
| Roteamento | Biblioteca externa | Vue Router | `RouterModule` | Por arquivos |
| Build/Dev | CRA/`npm start` | Vite | Angular CLI | `npm run dev` |
| Renderização | Cliente (SPA) | Cliente (SPA) | Cliente/SPA | SSR + Cliente |

> Resumo: React e Vue são mais leves e flexíveis; Angular é opinativo e completo (TypeScript nativo); Next.js adiciona SSR, rotas por arquivos e recursos de backend sobre o React.

