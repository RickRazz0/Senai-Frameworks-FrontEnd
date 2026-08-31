# Resumo da Aula 02: Configuração do Ambiente de Desenvolvimento

## 1. Versionamento e Controle de Versões

* **Versionamento vs Backup:**
  * Versionamento registra histórico completo de alterações, com rastreio de autoria, colaboração simultânea e reversão granular.
  * Backup é apenas uma cópia pontual do estado atual, sem histórico ou rastreabilidade.

* **Problemas sem versionamento:** arquivos duplicados sem contexto, código perdido, conflitos entre desenvolvedores e ausência de histórico.

* **Benefícios do versionamento:** trabalho simultâneo seguro, menos retrabalho, auditoria, rastreabilidade, recuperação de versões e colaboração eficiente.

## 2. Versionamento Semântico (SemVer)

* **Padrão MAJOR.MINOR.PATCH** (ex: 2.1.3):
  * MAJOR: mudanças incompatíveis com versões anteriores.
  * MINOR: novas funcionalidades retrocompatíveis.
  * PATCH: correções de bugs sem alteração na API.

* A versão 1.0.0 marca o lançamento público estável; versões 0.x.x indicam desenvolvimento inicial.

* **Vantagens:** facilita gestão de dependências, clareza para desenvolvedores e usuários, manutenção e previsibilidade.

* **Exemplos de alterações:** Bug Fix, New Feature, Feature Enhancement, Refactoring, Performance, Security Patch, Dependency Update, Adding Tests.

## 3. Git e Controle de Versão

* **Git** é um sistema de controle de versão de arquivos, instalado localmente e utilizado via linha de comando, que sincroniza com repositórios online como GitHub.

* **Instalação:** baixar o instalador para o sistema operacional e executar; configurar usuário e e-mail com `git config --global user.name` e `git config --global user.email`.

* **VS Code e Git:** a aba de Controle de Código-Fonte integra o Git diretamente no editor.

## 4. Tags, Branhes e Boas Práticas no Git

* **Tags:** marcadores para pontos específicos no histórico (ex: releases). Tipos: leve (lightweight) e anotada (annotated).
  * `git tag <nome>` cria uma tag; `git push origin <nome>` envia a tag para o repositório.

* **Boas práticas:**
  * Commits pequenos e frequentes.
  * Mensagens de commit claras.
  * Uso de branches para manter a principal estável.
  * Testes automatizados antes do merge.

## 5. IDE e Visual Studio Code

* **IDE (Ambiente de Desenvolvimento Integrado):** ambiente unificado para desenvolver, testar, executar e depurar software.

* **VS Code** é um editor de código que funciona como IDE por meio de extensões e ferramentas integradas.

## 6. Node.js e NPM

* **Node.js:** ambiente de execução JavaScript no servidor, permitindo usar a mesma linguagem no backend e frontend.

* **NPM (Node Package Manager):** gerenciador de pacotes do Node.js que instala, atualiza e remove bibliotecas e frameworks.

* O arquivo `package.json` registra todas as dependências do projeto, permitindo instalação automática via `npm install`.

## 7. Criação de Projetos React

* **Comando:** `npx create-react-app <nome>` gera projeto com estrutura completa (Webpack, Babel, servidor local, scripts de build e teste).

* **Estrutura básica:**
  * `node_modules`: pacotes instalados.
  * `public`: arquivos HTML, JSON e imagens.
  * `src`: arquivos JS do React.
  * `.gitignore`, `package.json` e `package-lock.json`: configurações e dependências.

* **Arquivos principais:**
  * `index.js`: ponto de entrada do React.
  * `App.js`: componente raiz.
  * `App.css` e `index.css`: estilos.

## 8. Deploy e Hospedagem com Vercel

* **Deploy:** processo de colocar uma aplicação em produção, tornando-a acessível aos usuários finais.

* **Vercel:** plataforma de hospedagem com deploy automático via integração com GitHub/GitLab/Bitbucket.
  * Suporte a frameworks modernos (React, Vue, Next.js, etc.).
  * Deploys instantâneos, CDN global, Serverless Functions e rollback rápido.
  * Alta performance, escalabilidade automática e segurança.

## 9. Atividade Prática

Desenvolver uma aplicação React utilizando VS Code, versionar com Git e publicar no GitHub, seguida pelo deploy automático na Vercel. O projeto final deve estar disponível online por meio de uma URL pública da Vercel.
