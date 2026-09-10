# 🏰 Atividade 02 — Consumindo APIs REST no Front-end

**SENAI** — Curso de Frameworks Front-end  
**Professor:** Prof. Me. Deivison S. Takatu  
**Atividade 02** — Consumindo APIs REST no Front-end (API em Express + Front-end React)

---

## 📖 Descrição Geral do Projeto

O projeto **Relógio do Reino** é uma aplicação web com tema medieval que consome dinamicamente a data e hora em tempo real diretamente de uma API REST construída com **Node.js/Express**. 

A arquitetura do sistema segue uma separação clara de responsabilidades entre cliente e servidor, com dois serviços independentes que se comunicam via HTTP e JSON, demonstrando uma integração cliente-servidor moderna.

---

## 🌐 Links do Projeto e Deploys

| Serviço | Repositório | Deploy |
|---------|-------------|--------|
| **Front-end** | [Repositório GitHub](https://github.com/RickRazz0/RelogioDoReino.git) | [Vercel](https://relogio-do-reino.vercel.app) |
| **Back-end / API** | [Repositório GitHub](https://github.com/RickRazz0/Api-DataHora.git) | [Render](https://api-datahora-km6m.onrender.com) |

---

## 🛠️ Tecnologias Utilizadas

### Back-end
- Node.js
- Express.js
- CORS
- JSON
- Render

### Front-end
- React.js
- Vite
- JavaScript (ES6+)
- CSS3 (Tema Medieval / Pergaminho)
- Vercel

---

## 🎯 Funcionalidades e Rotas da API

### Endpoint Principal

**`GET /api/data-hora`**

Retorna um objeto JSON contendo a data e hora atual do servidor, com os seguintes campos:

```json
{
  "data": "DD/MM/AAAA",
  "hora": "HH:MM:SS",
  "dataHora": "DD/MM/AAAA HH:MM:SS",
  "timestamp": 1234567890
}
```

### Funcionamento no Front-end

O consumo da API é realizado automaticamente através do hook `useEffect` com um `setInterval` configurado para executar a cada **1 segundo**, garantindo a atualização contínua da data e hora exibida na interface.

---

## 🚀 Como Executar os Projetos Localmente

### 1. Clone os repositórios

```bash
# Back-end
git clone https://github.com/RickRazz0/Api-DataHora.git

# Front-end
git clone https://github.com/RickRazz0/RelogioDoReino.git
```

### 2. Instale as dependências

```bash
# No diretório do Back-end
cd Api-DataHora
npm install

# No diretório do Front-end
cd RelogioDoReino
npm install
```

### 3. Configure o arquivo `.env`

No projeto Front-end, crie um arquivo `.env` na raiz do projeto com a seguinte variável:

```
VITE_API_URL=http://localhost:3000
```

> **Nota:** Certifique-se de que a porta corresponda à porta configurada no servidor Express.

### 4. Execute as aplicações

```bash
# Back-end (na pasta Api-DataHora)
npm start

# Front-end (na pasta RelogioDoReino)
npm run dev
```

Acesse a aplicação Front-end no navegador, geralmente em `http://localhost:5173`.

---

## ✅ Considerações Finais

A atividade cumpre todos os requisitos propostos pelo professor Deivison S. Takatu:

- Código organizado em **repositórios separados** para Back-end e Front-end;
- Integração entre os serviços configurada com **CORS**;
- API hospedada na **Render** e Front-end na **Vercel**;
- **Consumo funcional de dados dinâmicos** em tempo real, com atualização automática a cada segundo;
- Interface estilizada com **tema medieval**, proporcionando uma experiência visual imersiva.

Esta implementação consolida os conceitos de APIs REST, comunicação cliente-servidor e deploy em nuvem, fundamentais para o desenvolvimento web moderno.
