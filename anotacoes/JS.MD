## Indentificar variavel:
typeof(var ou const) - Indentificar o tipo da variavel

## Variáveis?

Podem guardar valores do tipo Boolean; null;
undefined; Number; String; Array; Object; Function.

Declaração de Variaveis -<br>
**var** – escopo global e local, pode ter seu valor alterado, se não
tiver um valor inicial será tratada como null;<br>
**let** – escopo local de bloco, pode ter seu valor alterado, se não
tiver um valor inicial será tratada como null;<br>
**const** – escopo local de bloco, somente leitura, o valor inicial é
obrigatório e não pode ser alterado.

## Escopo

O escopo em JavaScript define a limitação e visibilidade de um
bloco de código.

**Escopo global|** – quando a variável é declarada fora de qualquer
bloco, sua visibilidade fica disponível em todo o código.

**Escopo local** – quando a variável é declarada dentro de um bloco,
sua visibilidade pode ficar disponível ou não.

## Operadores

### Aritiméticos
- "+" adição;
- "-" subtração;
- "*" multiplicação;
- "/" divisão real;
- "%" divisão inteira;
- "**" potenciação;

### Relacionais

- ">" maior que;
- "<" menor que;
- ">=" maior ou igual a;
- "<=" menor ou igual a;

### Lógicos

- && - “e” – considera que todos os valores sejam true;
- || - “ou” – considera que qualquer valor seja true;
- ! - “não” – inverte o valor de true para false ou vice-versa;

## Arrays

Arrays são um tipo de lista, ou matriz de variáveis, onde cada
variável possui um índice. Os valores podem ser de vários tipos.

O array deve ser declarado entre colchetes “[]”, e podem guardar
qualquer valor dentro de seus índices: inclusive outros arrays.

Ex.: let array = ['string', 1, true, false, [‘array1], [‘array2’]...]
### Manipulação

- forEach() – itera um array;
- push() – add item no final do array;
- pop() – remove item no final do array;
- shift() – remove item no início do array;
- unshift() – add item no início do array;
- indexOf() – retorna o índice de um valor;
- splice() – remove ou substitui um item pelo índice;
- slice() – retorna uma parte de um array existente;

## Objetos

Dados que possuem propriedades e valores que definem suas
características. Deve ser declarado entre chaves “{}”.

### Manipulação

As propriedades de ojbetos podem ser atribuídas à variáveis,
facilitando a manipulação do objeto. Chamamos isso de
desestruturação.

Ex.: `var xicara = {cor: ‘azul’, tamanho: ‘p’, funcao: tomarCafe()}`

    var cor = xicara.cor;
    var tamanho = xicara.tamanho;
    var funcao = tomarCafe();

Outra forma de fazer a desestruturação é utilizando chaves ao
declarar a variável:

Ex.: `var xicara = {cor: ‘azul’, tamanho: ‘p’, funcao: tomarCafe()}`

    var { cor, tamanho, funcao } = xicara;
