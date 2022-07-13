## Conveções

## Sass
- CSS with superpowers
- São pré-processadores ou compiladores de CSS, que a partir de uma sintaxe são capazes de gerar outra sintaxe
- (scss, sass), a primeira é mais próxima do CSS

## BEM
- Convenção para nomes
- Fácil de usar ajuda na legibilidade do código e na sua organização
- Bem, vem de bloco(footer, header, checkbox), elemento(element-filho esta vinculado ao seu bloco) e modificador(variante de um bloco ou elemento, ex: disabled, checked)

## Parcel
- Ferramenta para criação de configuração do zero de Sass, Js, CSS, HTML etc..
- Inclui um servidor de desenvolvimento, com auto reloading
- Caso cometa um erro, ele identifica no terminal

## PostCSS
- O PostCSS é melhor definido como um ecossistema e não como um pré/pós-processador ou wrapper de CSS

## Namespace
- c-, para componentes exs: c-modal, c-modal__content, c-modal__button
- u-, para utilitários, ou seja para aqueles que fazem apenas uma única coisa e nada mais, u-bold, permitido usar o !important
- s-, para escopos, para modificar conteúdo CMS, s-main-menu .menu-item, ele envolve o conteúdo por completo.
- is-/has, está ou é, estado ou dado uma condição. is-open
- js-, desenvolvimento em camadas, (HTML, CSS, JavaScript), js-main-menu, para manipularmos este via JS
- qa-, para auxiliar os QA
