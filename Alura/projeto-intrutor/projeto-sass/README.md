# Alura Cursos
## Sass: O CSS com superpoderes

Faça esse curso de HTML e CSS e:
- Descubra as vantagens de utilizar o pré-processador mais conhecido no mundo
- Use variáveis em seu código CSS
- Aprenda a estender seu CSS e evitar repetições
- Facilite a manutenção da folha de estilo
- Implemente funções e lógica na estilização do seu site
- Torne o site responsivo de maneira simples e reutilizável

## Preparando o Ambiente

Para este curso, precisaremos instalar algumas ferramentas — caso você ainda não tenha feito isso anteriormente:

##### NodeJS: 
Se você já fez outros cursos dessa formação, o NodeJS já deve estar instalado. você pode conferir com o comando 
````node --version ou node -v ```` no terminal. Caso retorne um número de versão, como por exemplo, v10.16.0, o NodeJS já está instalado. Caso precise instalar, os links estão na [página oficial do NodeJS](https://nodejs.org/en/download/).

##### Visual Studio Code: 
Caso precise instalar, os links estão na [página do Visual Studio](https://code.visualstudio.com/download).


Grande parte das funções extras do Sass vem no formato de At rules, e nesta aula vimos alguns exemplos como mixins, function, import, extend e include, mas existem diversas At Rules:

@use: carrega mixins, functions e variáveis de outras folhas de estilos Sass e combina o CSS de diversas folhas de estilo juntos.

@forward: carrega uma folha de estilo Sass e torna os mixins, functions e variáveis disponíveis quando a folha de estilo é carregada pela regra do @use.

@import: estende as regras de CSS para carregar styles, mixins, functions e variáveis de outras folhas de estilo.

@mixins e @include: facilitam a reutilização de trechos de código.

@function: define funções customizadas que podem ser utilizadas em expressões.

@extend: permite que os seletores herdem estilos uns dos outros.

@at-root: coloca estilos dentro dele na raiz do documento CSS.

@error: faz com que a compilação falhe com uma mensagem de erro.

@warn: imprime um aviso sem parar totalmente a compilação.

@debug: imprime uma mensagem para fins de debugging.

E também fluxos de controle, como: @if, @each, @for e @while.


Nesta aula, aprendemos:

Como criar um placeholder selector e como usá-lo com extend.
O Placeholder Selector é um tipo especial de seletor que é bem parecido com um seletor convencional mas com um % na frente e ele também não é exibido no arquivo CSS após ser compilado.
O que são os mixins.
Mixins permitem definir estilos que podem ser reutilizados, e isso evita o uso de classes repetitivas e não semânticas como .float-left, e também distribui coleções de estilo para bibliotecas.
Como deixar o site responsivo usando media queries com mixins.
Os media queries já são usados no CSS convencional, porém, com os mixins, é possível setar seus valores em apenas um lugar e reutilizá-lo em todo o código e, caso seja necessário, a alteração dos valores será feita em apenas um lugar.
Como criar funções no Sass.
As funções no Sass permitem definir operações complexas que podem ser reutilizadas em todo o projeto, facilitando abstração de comportamentos em comum.
Como importar arquivos no Sass.
Vimos como abstrair o nosso CSS, deixando ele separado para cada uma das páginas. Dessa maneira a manutenção fica mais fácil e, para os CSS abstraídos funcionarem, nós usamos o @import, que importa os arquivos dentro de um principal.
