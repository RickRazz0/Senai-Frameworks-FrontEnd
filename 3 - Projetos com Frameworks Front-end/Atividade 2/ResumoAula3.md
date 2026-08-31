# Resumo da Aula 03: Projetos com Frameworks Front-end

## 1. Introdução aos Frameworks Front-end

* **Framework Front-end:** conjunto de ferramentas, bibliotecas e convenções que padronizam o desenvolvimento de interfaces web, fornecendo estrutura pré-definida e acelerando a criação de aplicações complexas.

* **Desenvolvimento sem framework:** código manual, difícil manutenção e repetição.

* **Desenvolvimento com framework:** componentes reutilizáveis, estado gerenciado e atualizações eficientes.

## 2. Framework vs Biblioteca

* **Framework:** controla o fluxo do aplicativo (inversão de controle), exige estrutura definida (ex: Angular, Vue).

* **Biblioteca:** você controla quando chamar, flexível, sem imposições (ex: React, jQuery).

* **Exemplo prático:** React (biblioteca) chama `ReactDOM.render()` quando você quiser; Angular (framework) decide quando renderizar componentes.

## 3. Por que Utilizar um Framework?

* **Produtividade aumentada:** soluções prontas para roteamento, estado e renderização.

* **Melhores práticas:** código organizado em componentes seguindo padrões reconhecidos.

* **Manutenção facilitada:** Virtual DOM (React), Change Detection (Angular) e otimizações internas.

* **Comunidade e suporte:** documentação extensa, plugins e soluções prontas para problemas comuns.

## 4. Principais Frameworks

* **React:** biblioteca criada pelo Facebook (2013) para construção de interfaces de usuário reutilizáveis. Arquitetura baseada em componentes e Virtual DOM.

* **Angular:** framework completo desenvolvido pelo Google, com soluções robustas para SPAs, TypeScript nativo, arquitetura MVC e CLI poderosa.

* **Vue.js:** framework progressivo de curva de aprendizado suave, reatividade eficiente, Single-File Components (SFC) e performance otimizada.

* **Next.js:** framework baseado em React com roteamento por arquivos, renderização no servidor, Server Components, otimização de imagens/fontes e recursos de backend.

## 5. Características dos Frameworks Front-end

* **Estrutura de código organizada:** separação de HTML, CSS e JavaScript, com componentes reutilizáveis.

* **Componentização:** componentes independentes e reutilizáveis, encapsulando lógica e apresentação.

* **Programação reativa:** atualização automática da UI com mudanças no estado da aplicação.

* **Ferramentas de build e bundling:** minificação, transpilação e combinação de arquivos.

* **Sistema de rotas:** SPAs com navegação suave e carregamento rápido.

* **Integração com APIs:** chamadas assíncronas e gerenciamento de estado.

* **Documentação e comunidade ativa:** tutoriais, plugins e suporte.

* **Padrões de design e acessibilidade:** componentes pré-construídos com diretrizes inclusivas.

* **Suporte a testes:** ferramentas para testes unitários e de integração.

## 6. Comparação entre Frameworks

A escolha do framework impacta diretamente desempenho, escalabilidade, manutenção e experiência do usuário. A decisão deve considerar complexidade do projeto, curva de aprendizado, desempenho e suporte da comunidade.

## 7. Conceitos Fundamentais e Criação de Projetos

* **React:** Hooks (`useState`, `useEffect`), JSX, gerenciamento de estado (Context API, Redux), Virtual DOM.
* **Angular:** componentes com `@Component`, módulos `@NgModule`, serviços `@Injectable`, data binding, injeção de dependência, roteamento.
* **Vue:** Single-File Components (`.vue`), reatividade automática, curva de aprendizado suave.
* **Next.js:** roteamento baseado em arquivos, renderização no servidor, Server Components.

## 8. Atividade Prática

Desenvolver, em grupo, quatro projetos Web sobre o mesmo tema, utilizando React, Vue, Angular e Next.js. Cada projeto deve apresentar uma página funcional, responsiva e organizada, utilizando componentes e os recursos básicos de cada tecnologia.

* **Requisitos:**
  * Projetos versionados com Git.
  * Publicação no GitHub com histórico de commits.
  * Elaboração de uma comparação entre as quatro tecnologias, destacando as principais diferenças encontradas durante o desenvolvimento.
