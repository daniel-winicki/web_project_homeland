# TripleTen Art Gallery — De Pátria para Pátria

Este projeto é uma página estática desenvolvida como parte do curso de desenvolvimento web da TripleTen. A página apresenta uma galeria/landing page responsiva construída com HTML e CSS.

## Descrição

O projeto consiste em uma landing page estática chamada  “De Pátria para Pátria”. A página contém:

- cabeçalho com logo, título principal e subtítulo;
- imagem principal da galeria;
- seção introdutória com título, citação e texto descritivo;
- rodapé com copyright.

A proposta é praticar a construção de uma página responsiva a partir de um layout visual, mantendo organização de arquivos, semântica HTML e separação dos estilos em blocos CSS.

## Tecnologias utilizadas

- HTML5
- CSS3
- Metodologia BEM para organização das classes
- Media queries para responsividade
- Normalize.css
- Fonte Inter carregada localmente via `@font-face`

## Estrutura do projeto

```text
web_project_homeland/
├── blocks/
│   ├── content.css
│   ├── footer.css
│   ├── header.css
│   ├── intro.css
│   ├── page.css
│   └── photo.css
├── fonts/
│   ├── Inter-Black.woff2
│   └── Inter-Regular.woff2
├── images/
│   ├── image.jpg
│   └── logo.svg
├── pages/
│   └── index.css
├── vendor/
│   ├── fonts.css
│   └── normalize.css
├── index.html
└── README.md
```

## Funcionalidades e características

- Layout centralizado com largura máxima definida.
- Página responsiva para diferentes larguras de tela.
- Ajustes específicos para telas menores usando `@media`.
- Organização dos estilos em arquivos separados por bloco.
- Uso de classes seguindo a lógica BEM.
- Imagens e fontes armazenadas localmente no projeto.

## Como executar o projeto

1. Clone ou baixe este repositório.
2. Abra a pasta do projeto no seu editor de código.
3. Abra o arquivo `index.html` no navegador.

Também é possível usar uma extensão como Live Server no VS Code para visualizar a página localmente com recarregamento automático.

## Status do projeto

Projeto criado para praticar estruturação de páginas estáticas, responsividade e organização de CSS.

## Autor

Daniel Winicki
