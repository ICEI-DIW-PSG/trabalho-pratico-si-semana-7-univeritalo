[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=20753211&assignment_repo_type=AssignmentRepo)
# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome: Ítalo Gabriel Justino Caldeira
- Matricula: 902423
- Proposta de projeto escolhida: Loja de Roupa
- Breve descrição sobre seu projeto: Loja de roupas femininas com um catálogo extenso de roupas de todos os tipos

## Print da Home-Page

<img src="home page.png" alt="print da home page">

## Print da página de detalhes do item

<img src="pagina detalhes.png" alt="print da página de detalhes">

## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript
const produtos = [
  {
    id: 1,
    produto: "Conjunto",
    especificacao: "Conjunto de Top Rosa, Short Jeans Preto e Cinto Preto",
    descricao: "Confortável e elegante, ideal para o dia a dia ou eventos casuais.",
    categoria: "Feminino",
    preco: 146.64,
    imagem: "img/roupa1.jpg"
  },
  {
    id: 2,
    produto: "Conjunto",
    especificacao: "Conjunto de Regata Branca e Short Jeans Preto",
    descricao: "Feita em tecido macio, combina com qualquer look casual.",
    categoria: "Feminino",
    preco: 132.99,
    imagem: "img/roupa2.jpg"
  },
  {
    id: 3,
    produto: "Conjunto",
    especificacao: "Conjunto de Top Branco e Short Jeans",
    descricao: "Ideal para momentos de lazer.",
    categoria: "Feminino",
    preco: 176.75,
    imagem: "img/roupa3.jpg"
  },
  {
    id: 4,
    produto: "Vestido",
    especificacao: "Vestido florido na cor Rosa",
    descricao: "Perfeita para o verão, combina conforto e estilo.",
    categoria: "Feminino",
    preco: 153.23,
    imagem: "img/roupa4.jpg"
  },
  {
    id: 5,
    produto: "Vestido",
    especificacao: "Vestido florido na cor Azul",
    descricao: "Tendência do momento, ideal para dias quentes e frios.",
    categoria: "Feminino",
    preco: 182.39,
    imagem: "img/roupa5.jpg"
  },
  {
    id: 6,
    produto: "Vestido",
    especificacao: "Vestido florido na cor Branco",
    descricao: "Peça coringa que combina com qualquer estilo.",
    categoria: "Feminino",
    preco: 167.49,
    imagem: "img/roupa6.jpeg"
  }
];

```