# CapyGames

Protótipo visual de um catálogo de jogos, com layout responsivo, banners, categorias e cards de produtos. O foco é a apresentação de uma interface web usando HTML, CSS/SCSS, Bootstrap e JavaScript.

> **Status:** estudo de frontend estático. Botões de compra, busca e carrinho possuem placeholders; não há checkout, autenticação, persistência ou API de comércio implementados.

## Recursos presentes

- Navegação por seções e menu de categorias.
- Banners em carrossel e vitrines de jogos.
- Grid responsivo com estilos Bootstrap e SCSS.
- Scripts jQuery para interação de menu, carrosséis e retorno ao topo.

## Stack e arquitetura

HTML · CSS · SCSS · JavaScript · Bootstrap · jQuery · Owl Carousel · Font Awesome

A página `index.html` utiliza os estilos compilados de `css/`, os scripts de `js/` e os assets de `img/`. O diretório `scss/` preserva os estilos-fonte; a visualização não exige recompilação de SCSS. Parte das bibliotecas e fontes é carregada de CDNs e requer conexão com a internet.

## Execução local

Com Git e Python 3 instalados:

```sh
git clone https://github.com/giulia05tomaz/CapyGames.git
cd CapyGames
python -m http.server 8000 --bind 127.0.0.1
```

Abra `http://127.0.0.1:8000/index.html`. O servidor é usado somente para visualizar arquivos estáticos, sem habilitar vendas ou publicar o projeto.

## Estrutura

```text
index.html      catálogo e seções da interface
css/            estilos compilados
scss/           estilos-fonte e componentes Bootstrap
js/main.js      interações jQuery
lib/            bibliotecas visuais
img/            assets de catálogo e banners
LICENSE.txt     licença do template-base
READ-ME.txt     identificação e orientações do template
```

## Validação e limites

Não há suíte automatizada ou GitHub Actions neste repositório. A verificação do protótipo é manual, cobrindo layout, navegação e recursos visuais em diferentes tamanhos de tela.

Uma evolução técnica pode substituir links vazios, implementar busca real e acrescentar testes de navegação e acessibilidade. Esses itens não fazem parte da versão atual.

## Créditos e licença

O projeto utiliza um template-base e bibliotecas de terceiros. Consulte [LICENSE.txt](LICENSE.txt) e [READ-ME.txt](READ-ME.txt) para autoria, atribuição e condições de uso; esses arquivos foram preservados.
