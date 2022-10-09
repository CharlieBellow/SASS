Nesta aula, aprendemos:

O que é Sass e porque usá-lo;
Sass é um pré-processador CSS, que permite adicionar funções que não são possíveis no CSS puro. As principais vantagens de usar o Sass são a facilidade na escrita e sintaxe, e a possibilidade de adicionar funções, mixins, nestings, seletores e herança.
Como instalar o Sass no seu projeto;
Para instalar o Sass é necessário possuir o node na sua máquina, e também um editor de código. Depois, basta digitar o comando "npm install -g sass”.
Como criar e usar variáveis no Sass;
Para criarmos variáveis usamos o símbolo $, junto dele o nome da variável, e depois dos dois pontos o valor que queremos. E para usá-las simplesmente chamamos o seu nome. Por exemplo: $branco: #fff; para criar e, para usá-la, chamaremos ela dentro da propriedade css, como por exemplo: color: $branco;
Como comentar o código no Sass;
Como em outras linguagens de programação, também é possível fazer comentários no Sass. Existem dois tipos: com duas barras (//) ou entre barras e asteriscos (/**/), a diferença entre eles é que no primeiro caso o comentário é por linha, ou seja, caso o enter seja pressionado, o comentário não será continuado, já o segundo permite comentário em múltiplas linhas.


BEM é um padrão de nomenclatura para manter o projeto simples e organizado. Ele foi criado pela Yandex e tenta resolver o problema de nomenclatura e estrutura do CSS permitindo facilitar e escalar o código, de forma que qualquer desenvolvedor tenha autonomia para mexer em qualquer projeto. A sigla BEM significa Block Element Modifier, em português, Bloco, Elemento, Modificador. Esses três pilares são a base dessa metodologia, e também as categorias em que os elementos são divididos.

Vamos supor que você queira construir um componente de card. Nesse caso, o bloco seria o .card. E qualquer outra seção dentro do card seriam elementos. No exemplo, temos uma imagem, uma descrição e um botão. A convenção da nomenclatura do BEM conecta o bloco ao elemento com dois underlines, por exemplo .card__image. Ainda na nossa imagem, nós temos dois tipos de botões, eles seriam os modificadores, e nesse caso para a nomenclatura nós conectamos ao elemento com dois hífens, por exemplo .card__button--success e .card__button--back.

Tela com exemplificação de um card, com uma imagem, descrição e dois botões, e ao lado nomes de classes para cada elemento, sendo respectivamente .card, .card__image, .card__description, card__button--success e .card__button--back.

Mas como saber o que é um elemento e o que é um modificador?

Um elemento sempre será uma parte da estrutura do bloco, já os modificadores são estados que os nossos blocos ou elementos poderão ter, como botões com diferentes aparências ou uma situação de destaque.

Prós e contras:

BEM deixa o nosso CSS com uma estrutura modular. Por conta dos nomes únicos, não acontecerão conflitos entre as classes, o que facilita a manutenção. Porém, às vezes, os nomes das classes ficam muito compridos ao se usar a metodologia, mas com o uso de um pré-processador (como estamos usando no curso), **isso** não será um grande problema (pois usaremos o nesting).

Referências: “What is BEM? And why you should use it in your project”, texto em inglês por Danny Huang (<https://medium.com/@dannyhuang_75970/what-is-bem-and-why-you-should-use-it-in-your-project-ab37c6d10b79>) e “BEM em 5min”, em português, por Julio Lozovei(<https://medium.com/trainingcenter/bem-em-5min-f5c80fd23439>).


Nesta aula, aprendemos:

Como fazer iterações no Sass.
Como em outras linguagens de programação, é possível fazer iterações no Sass com for, each ou while usando os At Rules.
Como criar condicionais no Sass com valores (ex: boolean).
Podemos fazer condicionais no Sass com @if, @else if e @else, para atribuir determinado trecho de estilo dependendo de uma condição específica, por exemplo setar um tema dark ou light no nosso site.
Como usar o While no Sass.
O while também funciona com at rule, ficando @while <expression> { ... }. Ele valida se a expressão é verdadeira, e enquanto ela for válida, ele irá executar o trecho de código contido entre as chaves.
