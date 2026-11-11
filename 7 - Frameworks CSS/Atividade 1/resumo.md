# Resumo - Atividade 1 (Aula 7: Frameworks CSS)

## Projeto desenvolvido

Foi criado um projeto de **landing page de biblioteca digital** chamado **BiblioTech**, utilizando apenas HTML e CSS, conforme proposto na Atividade 1 da aula.

Repositório: https://github.com/RickRazz0/senai-front-bibliotech.git

### Arquivos criados

| Arquivo | Descrição |
|---------|-----------|
| `index.html` | Estrutura semântica da página |
| `style.css` | Estilos aplicados externamente via `<link>` |

---

## Como os requisitos da Atividade 1 foram atendidos

### 1. Projeto com index.html e style.css, CSS externo via `<link>`

O arquivo `index.html` referencia o CSS externo na tag `<head>`:

```html
<link rel="stylesheet" href="style.css">
```

Todos os estilos estão centralizados em `style.css`, sem uso de CSS inline ou `<style>` no HTML.

### 2. 20 elementos com valores em Content, Padding, Border e Margin

Foram criados mais de 20 elementos na página, cada um com preenchimento nas quatro propriedades do modelo de caixa (box model):

- **content**: texto, ícones, imagens coloridas (divs representando capas de livros), botões, links, formulário
- **padding**: espaçamento interno em todos os elementos (cabeçalho, seções, cards, itens de categoria, formulário, rodapé, etc.)
- **border**: bordas sólidas, arredondadas, com cores variadas em praticamente todos os componentes
- **margin**: espaçamento externo entre seções, elementos e componentes

Exemplos de elementos com as quatro propriedades preenchidas:

- `.cabecalho`, `.logo`, `.menu`, `.btn-acesso`
- `.hero`, `.hero-conteudo`, `.hero-imagem`, `.livro-destaque`
- `.categorias`, `.grid-categorias`, `.categoria-item`, `.icone-categoria`
- `.destaques`, `.carousel-livros`, `.card-livro`, `.capa-livro`
- `.sobre`, `.sobre-conteudo`, `.sobre-imagem`
- `.contato`, `.contato-conteudo`, `.contato-info`, `.contato-form`, `.btn-enviar`
- `.rodape`, `.logo-rodape`, `.redes-sociais`

### 3. 20+ propriedades Flexbox para organização responsiva

Foram aplicadas propriedades Flexbox em diversos containers para manipular e organizar os elementos:

| Propriedade Flexbox | Onde foi aplicada |
|---------------------|-------------------|
| `display: flex` | cabeçalho, hero, grid de categorias, carousel de livros, sobre, contato, rodapé, redes sociais |
| `flex-direction` | hero (linha/coluna), sobre (linha/coluna), contato (linha/coluna), categorias |
| `justify-content` | cabeçalho, hero, categorias, carousel, sobre, contato, rodapé |
| `align-items` | cabeçalho, hero, categorias, cards, sobre, contato, rodapé |
| `flex-wrap` | hero-imagem, grid-categorias, carousel-livros |
| `flex` | hero-conteudo, hero-imagem, sobre-conteudo, sobre-imagem, contato-info, contato-form |
| `gap` | menu, botoes-hero, grid-categorias, carousel-livros, redes-sociais |
| `flex-shrink` | card-livro (evita encolhimento indesejado) |
| `align-self` | btn-enviar (alinhamento individual dentro do formulário) |

### Responsividade

A página é responsiva por meio de **media queries** para:

- **Tablets (até 900px)**: empilhamento de colunas (hero, sobre, contato passam de linha para coluna), ajustes de padding e margens, menu e botão de acesso reorganizados verticalmente.
- **Celulares (até 600px)**: redução de tamanhos de fonte, botões do hero em largura total, itens de categoria e cards de livro ocupam largura máxima disponível, textos centralizados, redes sociais centralizadas.

---

## Estrutura da página

1. **Cabeçalho** — logo, menu de navegação (Início, Categorias, Destaques, Sobre, Contato) e botão Entrar
2. **Hero** — chamada principal com título, subtítulo, botões de ação e representação visual de livros em destaque
3. **Categorias** — grade com 6 categorias (Ficção, Mistério, Ficção Científica, História, Autoajuda, Artes), cada uma com ícone, título e descrição
4. **Destaques da Semana** — carrossel horizontal de 5 livros com capa, título, autor, preço e botão "Ler amostra"
5. **Sobre** — texto institucional da BiblioTech com imagem ao lado
6. **Contato** — informações de endereço, telefone, e-mail e formulário de mensagem
7. **Rodapé** — logo, copyright e links para redes sociais

---

## Tecnologias utilizadas

- HTML5 semântico
- CSS3 externo (arquivo separado vinculado via `<link>`)
- Flexbox para layout
- Media queries para responsividade (mobile-first / breakpoints)

---

## Como visualizar

Abra o arquivo `index.html` diretamente em qualquer navegador web. Não é necessário servidor local, pois não há dependências externas.