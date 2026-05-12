# TripleTen Art Gallery — De Pátria para Pátria

Projeto responsivo de página web desenvolvido a partir de um layout no Figma. A página apresenta uma galeria visual sobre lugares de origem, pertencimento e histórias pessoais, combinando texto, imagens, cards de locais, gradientes, sombras e adaptação para diferentes tamanhos de tela.

## Link do projeto

GitHub Pages: https://daniel-winicki.github.io/web_project_homeland/

> Substitua `SEU-USUARIO` pelo seu usuário real do GitHub antes de enviar o projeto.

## Descrição

O projeto “De Pátria para Pátria” é uma página estática construída com HTML e CSS. Ele apresenta uma introdução sobre a Galeria de Arte TripleTen, uma grade de imagens e uma seção com cards de diferentes lugares. Cada card contém título, imagem, informações sobre artistas, texto descritivo e um link para compra simbólica da obra como NFT.

O foco do projeto é praticar estrutura semântica em HTML, organização de arquivos com BEM Flat, CSS Grid, responsividade com media queries e reprodução visual de um design fornecido no Figma.

## Funcionalidades e características

- Layout responsivo para desktop, tablet e mobile.
- Estrutura semântica com `header`, `main`, `section`, `article` e `footer`.
- Seção de galeria de fotos construída com CSS Grid.
- Seção de lugares construída com CSS Grid.
- Cards com título, imagem, artistas, parágrafos descritivos e botão/link.
- Gradientes aplicados aos botões.
- Sombras aplicadas em imagens e botões conforme o design.
- Estados `:hover` em elementos interativos.
- Fonte Inter carregada localmente.
- Organização dos estilos em arquivos separados por blocos BEM.

## Tecnologias utilizadas

- HTML5
- CSS3
- CSS Grid
- Media queries
- Metodologia BEM
- Estrutura de arquivos BEM Flat
- Normalize.css
- Fontes locais com `@font-face`
- Git
- GitHub Pages

## Estrutura do projeto

web_project_homeland/
├── blocks/
│ ├── content.css
│ ├── footer.css
│ ├── header.css
│ ├── intro.css
│ ├── page.css
│ ├── photo.css
│ ├── photo-grid.css
│ ├── place.css
│ └── places.css
├── images/
│ ├── image.jpg
│ ├── logo.svg
│ ├── photo-grid-1.jpg
│ ├── photo-grid-2.jpg
│ ├── photo-grid-3.jpg
│ ├── photo-grid-4.jpg
│ ├── photo-grid-5.jpg
│ ├── photo-grid-6.jpg
│ ├── photo-grid-7.jpg
│ ├── photo-grid-8.jpg
│ └── photo-places-\*.jpg
├── pages/
│ └── index.css
├── vendor/
│ ├── fonts.css
│ ├── normalize.css
│ └── fonts/
├── .editorconfig
├── .gitignore
├── .prettierignore
├── favicon.ico
├── index.html
└── README.md
