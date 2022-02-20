# Notas delicinhas de Js **:3**

Galera abaixo está algumas notas de JavaScript que fiz mediante ao aprendizado com o passar do tempo. Espero que gostem, e o repo está publico, então se quiser contribuir com alguma nota fique avontade! **É tudo nosso!** 🚀📚

# Tópicos

- [Notas delicinhas de Js **:3**](#notas-delicinhas-de-js-3)
- [Tópicos](#tópicos)
- [Console log](#console-log)
- [Comentários](#comentários)
- [Variáveis](#variáveis)
  - [**LET**](#let)
  - [**CONST**](#const)
  - [**VAR**](#var)
- [Tipos de dados primitivos](#tipos-de-dados-primitivos)
  - [**TYPEOF** - Ver o tipo da variavél](#typeof---ver-o-tipo-da-variavél)
  - [Valores por referencia](#valores-por-referencia)
- [Operadores aritimeticos](#operadores-aritimeticos)
  - [Contatenação utilizando strings](#contatenação-utilizando-strings)
  - [Adição e subtração](#adição-e-subtração)
  - [Potenciação](#potenciação)
  - [Resto da divisão](#resto-da-divisão)
  - [Incremento decremento](#incremento-decremento)
- [Conversão de tipo de dados](#conversão-de-tipo-de-dados)
- [Alert](#alert)
  - [Confirm](#confirm)
  - [prompt](#prompt)
- [String](#string)
  - [Escapar um caracter](#escapar-um-caracter)
  - [Posições / Index](#posições--index)
    - [indexOf](#indexof)
    - [lastIndexOf](#lastindexof)
  - [concat](#concat)
  - [Endwith](#endwith)
  - [replace](#replace)
  - [length](#length)
  - [slice](#slice)
  - [subString](#substring)
  - [split](#split)
  - [toUpperCase](#touppercase)
  - [toLowerCase](#tolowercase)
- [Expressões regulares](#expressões-regulares)
  - [match](#match)
  - [search](#search)
  - [Replace com regex](#replace-com-regex)
- [Numbers](#numbers)
  - [Numero para string](#numero-para-string)
  - [Casas decimais](#casas-decimais)
    - [tofixed - Escolher quantas casas decimais aparecer](#tofixed---escolher-quantas-casas-decimais-aparecer)
  - [Saber se o numéro é inteiro](#saber-se-o-numéro-é-inteiro)
  - [Saber ser é um NaN (Not a number)](#saber-ser-é-um-nan-not-a-number)
  - [Padrão de calculo - IEEE 754-2008](#padrão-de-calculo---ieee-754-2008)
- [Math](#math)
  - [Arrendondar numeros](#arrendondar-numeros)
    - [Para baixo - Math.floor](#para-baixo---mathfloor)
    - [Para cima - Math.ceil](#para-cima---mathceil)
    - [Para o mais próximo - Math.round](#para-o-mais-próximo---mathround)
  - [Achar maior e menor numero](#achar-maior-e-menor-numero)
  - [Gerar numeros aleatórios](#gerar-numeros-aleatórios)
  - [Potenciação](#potenciação-1)
  - [Divisão por zero](#divisão-por-zero)
    - [Tratando divisão por zero](#tratando-divisão-por-zero)
- [Arrays](#arrays)
  - [Obter valores do array](#obter-valores-do-array)
  - [Mudando os valores do array](#mudando-os-valores-do-array)
  - [Passando valores entre arrays](#passando-valores-entre-arrays)
  - [Comprimento do array - length](#comprimento-do-array---length)
  - [Inserir valores no array - push/unshift](#inserir-valores-no-array---pushunshift)
  - [Romover valores do array - pop/shift/delete](#romover-valores-do-array---popshiftdelete)
  - [Fatiar um array - slice](#fatiar-um-array---slice)
  - [Checkar instancia de array](#checkar-instancia-de-array)
  - [Remover e inserir valores - Splice](#remover-e-inserir-valores---splice)
  - [Concatenar array](#concatenar-array)
  - [Filtrar o array](#filtrar-o-array)
  - [Mapear o array](#mapear-o-array)
  - [Reduce](#reduce)
  - [Foreach](#foreach)
- [Funções](#funções)
  - [Criar função - function](#criar-função---function)
  - [Arrow function](#arrow-function)
  - [Parametros de função](#parametros-de-função)
    - [Parametros de resto - Rest operator](#parametros-de-resto---rest-operator)
  - [Funções dentro de uma variavel - Function expression](#funções-dentro-de-uma-variavel---function-expression)
  - [Passando função como parametro](#passando-função-como-parametro)
  - [Arguments](#arguments)
    - [Arguments em functions](#arguments-em-functions)
  - [Closures - Function dentro de function](#closures---function-dentro-de-function)
  - [Função de callback](#função-de-callback)
  - [IIFE - Immediately invoked function expression](#iife---immediately-invoked-function-expression)
  - [Funções geradoras](#funções-geradoras)
  - [Funções recursivas](#funções-recursivas)
- [Objetos](#objetos)
  - [Criar objeto](#criar-objeto)
  - [Acessar valores do objeto](#acessar-valores-do-objeto)
  - [Fabrica de objetos](#fabrica-de-objetos)
  - [Factory Functions](#factory-functions)
    - [Utilizando Getter](#utilizando-getter)
    - [Utilizando Setter](#utilizando-setter)
  - [Contructor functions](#contructor-functions)
  - [Congelar objeto - freeze](#congelar-objeto---freeze)
  - [Métodos do objeto](#métodos-do-objeto)
  - [Propriedades do objeto](#propriedades-do-objeto)
    - [Apenas um atributo](#apenas-um-atributo)
    - [Todos os atributos](#todos-os-atributos)
  - [Propiedades do objeto com getters e setters](#propiedades-do-objeto-com-getters-e-setters)
  - [Metodos uteis para objetos](#metodos-uteis-para-objetos)
    - [Copiar objeto](#copiar-objeto)
    - [Checar como estão as propiedades do objeto](#checar-como-estão-as-propiedades-do-objeto)
    - [Pegar o valor do objeto](#pegar-o-valor-do-objeto)
    - [Pegar valor do objeto com entries](#pegar-valor-do-objeto-com-entries)
  - [Prototypes](#prototypes)
    - [Manipulação de prototype](#manipulação-de-prototype)
    - [Criando objeto pelo prototype](#criando-objeto-pelo-prototype)
  - [Herança](#herança)
  - [Polimorfismo](#polimorfismo)
  - [Factory Functions + Prototype](#factory-functions--prototype)
  - [Composing / Mixing](#composing--mixing)
  - [Object map](#object-map)
- [Class](#class)
  - [Getter & Setter](#getter--setter)
  - [Herança com classes](#herança-com-classes)
  - [Metodos estaticos](#metodos-estaticos)
    - [Valores primitivos e por referencia](#valores-primitivos-e-por-referencia)
      - [Valores primitivos (imutaveis)](#valores-primitivos-imutaveis)
      - [Valores do referencia (mutavel)](#valores-do-referencia-mutavel)
  - [window.document](#windowdocument)
  - [Seção 3 - JavaScript Lógica de programação](#seção-3---javascript-lógica-de-programação)
    - [Operações de comparação](#operações-de-comparação)
    - [Operadores lógicos](#operadores-lógicos)
    - [Avaliação de curto circuito (Short-circuit)](#avaliação-de-curto-circuito-short-circuit)
      - [Valores que avalião em false](#valores-que-avalião-em-false)
      - [Operador && and](#operador--and)
      - [Operador || or](#operador--or)
    - [Estruturas condicionais](#estruturas-condicionais)
      - [if else if e else](#if-else-if-e-else)
      - [Avaliação por curto-circuito](#avaliação-por-curto-circuito)
      - [Operação ternario](#operação-ternario)
    - [Objeto date](#objeto-date)
      - [Obter ano, mes, dia, horas, minutos, segundos, milesimos](#obter-ano-mes-dia-horas-minutos-segundos-milesimos)
      - [Formatar data](#formatar-data)
    - [Switchs](#switchs)
    - [Atribuição via desestruturação (Arrays)](#atribuição-via-desestruturação-arrays)
    - [Atribuição via desestruturação (Objetos)](#atribuição-via-desestruturação-objetos)
    - [Estrutura de repetição](#estrutura-de-repetição)
      - [For](#for)
      - [For in](#for-in)
      - [For of](#for-of)
    - [DOM - Document object model](#dom---document-object-model)
      - [Seletores](#seletores)
        - [Selecionar elemento](#selecionar-elemento)
        - [Selecionar mais de um elemento](#selecionar-mais-de-um-elemento)
        - [Buscar pai de um elemento](#buscar-pai-de-um-elemento)
      - [Remover elmento](#remover-elmento)
        - [remover pai do elemento](#remover-pai-do-elemento)
      - [Pegar o texto de um elemento](#pegar-o-texto-de-um-elemento)
      - [Eventos e listeners](#eventos-e-listeners)
        - [Adicionar listener a um elemento](#adicionar-listener-a-um-elemento)
        - [Selecionar element via evento](#selecionar-element-via-evento)
      - [Criar elemento](#criar-elemento)
      - [Inserir dados a elemento](#inserir-dados-a-elemento)
        - [Inserir filhos em um elemento](#inserir-filhos-em-um-elemento)
        - [Pegar estilos de elementos](#pegar-estilos-de-elementos)
        - [Mudar estilos de um elemento](#mudar-estilos-de-um-elemento)
    - [While do while](#while-do-while)
      - [While](#while)
      - [Do while](#do-while)
    - [Break e continue](#break-e-continue)
      - [Continue](#continue)
      - [Break](#break)
    - [Try Catch finally](#try-catch-finally)
      - [Errors](#errors)
    - [Interval e Time outs](#interval-e-time-outs)
      - [setInterval](#setinterval)
      - [setTimeout](#settimeout)
    - [JSON](#json)
      - [Passar para json](#passar-para-json)
      - [Passar Json para um objeto JavaScript](#passar-json-para-um-objeto-javascript)
    - [LocalStorage](#localstorage)
      - [Salvar no localStorage](#salvar-no-localstorage)
      - [Buscar dados](#buscar-dados)
      - [Deletar do localStorage](#deletar-do-localstorage)
    - [Promise](#promise)
      - [Métodos uteis para promisses](#métodos-uteis-para-promisses)
        - [Promise.all](#promiseall)
        - [Promise race](#promise-race)
        - [Promise resolve e reject](#promise-resolve-e-reject)
        - [Async await](#async-await)
    - [Requisições](#requisições)
      - [XMLHttpRequest](#xmlhttprequest)
      - [Fetch API](#fetch-api)
      - [Axios](#axios)
    - [Compiladores e transpiladores (Acho que é assim)](#compiladores-e-transpiladores-acho-que-é-assim)
      - [Babel](#babel)
        - [Instalação](#instalação)
        - [Conversão de código](#conversão-de-código)
        - [Automazar a conversão de código](#automazar-a-conversão-de-código)
    - [WebPack](#webpack)
      - [Instalação](#instalação-1)
        - [configuração](#configuração)
    - [Import & Export](#import--export)
      - [Export](#export)
      - [import](#import)
  



<a id='console.log'></a>

# Console log

```js
console.log('Vamos printar algo');
console.log("print 'com aspas simples'");
console.log('print "com aspas duplas"');
console.log(1234, 56.789, 'Números');
console.log(` 'tudo isso' "é um print" ${123}`);
console.log(` 'tudo isso' "é um print" ${variable}`);
```

<a id='comentarios'></a>

# Comentários

```js
// Comentário na linha
/*
    Comentário
    Longo
*/
```
<a id='variaveis'></a>

# Variáveis

> Em váriaveis geralmente se utiliza camelCase, por exemplo: **nomeVariavel**

<a id='let'></a>

## **LET**

- Podem ser iniciliadas vazias
- Seus valores podem ser alterados no decorrer do código
- Só existe dentro do escopo em que foi criada

```js
let nome;
nome = 'Albert';
let sobreNome = 'Einstein';
```

<a id='const'></a>

## **CONST**

- Não pode ser inicializada vazia
- Seu valor não pode ser diretamente alterado (Seu endereço de memória não pode ser alterado)
- Só existe dentro do escopo informado

```js
const nome = 'Einstein';
const dez =  10;
```

<a id='var'></a>

## **VAR**

- Não utilize var
- Utilize let ou const :)
- Var é global, oque pode trazer problemas para sua aplicação

```js
var teste = 'teste'
```
<a id='tipos-primitivos'></a>

# Tipos de dados primitivos

```js
const nome = 'Einstein' // string
const numero = 10 // number
const numero = 2.5 // number
let teste // undefined
const nulo = null // null
const aprovado = true // boolean
//symbol
```

<a id='typeof'></a>

## **TYPEOF** - Ver o tipo da variavél

```js
const nome = 'Einstein'
typeof nome // string
const numero = 10
typeof numero // number
typeof nome, numer // string number
```
<a id='valores-referencia'></a>

## Valores por referencia

Aqui os valores trabalham como ponteiros, onde uma variavel aponta para o mesmo endereço de memória que a outra. Dessa forma quando uma variavel que faz referencia (ponteiro) a outra for alterada, tanto a variavél ponteiro quanto a varaivel referenciada será alterada.

Confuso? Dale exemplo abaixo :)

```js
const a = [1,2,3]
const b = a
console.log(a,b) // [1,2,3] [1,2,3]
b.push(4)
console.log(a,b) // [1,2,3,4] [1,2,3,4]
// tando 'a' como 'b' apontam para os mesmos valores
```

<a id='operadores-aritimeticos'></a>

# Operadores aritimeticos

[**Precedencia** documentação](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)

- **( )** - Primeiro - Resolve oque está no parênteses
- **/ * %**  - Segundo - Resolve oque aparecer primeiro desses
- **-**  Terceiro
- **+**  Quarto

<a id='concatenacao'></a>

## Contatenação utilizando strings

```js
console.log('Albert' +  ' ' + 'Einstein') // 'Albert Einstein'
console.log('Albert ' + 1) // 'Albert 1'
```

<a id='adicao-subtracao'></a>

## Adição e subtração

```js
console.log(10 + 10) //20
console.log('10' + 10) // 20 Ele faz algumas conversões sozinho
console.log(20 - 10) // 10
console.log('10' - 10) // 0 Conversão novamente
```

<a id='potenciacao'></a>

## Potenciação

```js
console.log(2**2) // 4
```

<a id='resto-divisao'></a>

## Resto da divisão

```js
console.log(10 % 3) // 1
```

<a id='incremento-decremento'></a>

## Incremento decremento

```js
let num = 10
num++ // 11
num-- // 9
++num // 11
--num // 9
num = num + 10 // 20
num += 10 // 20
num = num - 10 // 0
num -= 10 // 0
num *= 10 // 100
num **= 2 // 10000
```

> **NaN = not a number**

<a id='conversao-tipo-dados'></a>

# Conversão de tipo de dados

```js
parseInt('5') //number - 5
parseInt('5.2') //number - 5 - Remove a casa decimal
parseFloat('5.2') //number - 5.2

// Melhor maneira
Number('5') //number - 5
Number('5.2') //number - 5.2
String(50) //string - '50'
```

<a id='alerts'></a>

<a id='alert'></a>

# Alert

É utilizado para trazer mensagens para o usuário na tela. Porém existem jeitos mais elegantes para se fazer isso :3

> Ele habita dentro do objeto window, assim como o método console.log.

- retorna undefined

```js
window.alert('alerta')
alert('alerta')
alert(123)
```

<a id='confirm'></a>

## Confirm

É bem parecido com o Alert, porém neste existe botões para aceitar, então você pode aceitar ou não oque a caixa flutuante de texto diz.

- retorna um boolean

```js
window.confirm('mensagem')
confirm('mensagem')
```

<a id='prompt'></a>

## prompt

Igualmente parecido com os outros dois citados anteriormente (Alert, Confirm). Aqui é possível inserir valores na caixa de texto flutuante

- retorna uma string, então se você inserir um Number, terá que converter

```js
window.prompt('mensagem')
confirm('mensagem')
```

<a id='string'></a>

# String

É um tipo de dado que representa um texto.

```javascript
typeof 'Isso é um texto' // string
typeof "Isso também é um texto" // string
typeof `Isso é um texto com números ${123}` // string
typeof 'Isso também é um texto com números ' + {123} // string
```

<a id='escapar-caracter'></a>

## Escapar um caracter

Beleza, as vezes queremos printar esse caracter '\', e se você fizer isso dará problema, pois esse caracter representa outra coisa dentro de uma string, então para isso você utiliza ele da forma abaixo:

```js
'Barra invertida \\' // Barra invertida \
'Posso pegar a aspa \' assim' // Posso pegar a aspa ' assim
```

<a id='posicao-index'></a>

## Posições / Index

Uma string tem um tamanho e cada caracter tem um posição.

> Uma Srting sempre começa no index 0 

```js
 012345678
'Meu texto'
```

Então para obter o valor de uma determinada posição podemos fazer da seguinte forma

```javascript
const meuTexto = 'Meu texto'
meuTexto[0] // M
meuTexto[1] // e
meuTexto[2] // u
meuTexto[3] //  
meuTexto[4] // t
meuTexto[5] // e
meuTexto[6] // x
meuTexto[7] // t
meuTexto[8] // o
```

<a id='indexof'></a>

### indexOf

Usado para buscar a posição de um valor informado na String

> Ele retornará a primeira posição que achar com o valor que for informado

```js
const texto = 'teste'
texto.indexOf('e') //1
texto.indexOf('w') //-1 - Retorna -1 quando valor não é encontrado
```

<a id='lastindexof'></a>

### lastIndexOf

Faz a mesma coisa que o indexOf, porém ele começa a percorrer as posições de trás para frente

```js
const valor = 'teste'
valor.lastIndexOf('e') // 1  
valor.lastIndexOf('s') // 2
```

<a id='concat'></a>

## concat

Usado para juntar textos

```js
'string' + 'string' // Primeira forma
`${umaString} mais outra string` // Forma mais utilizada
umaString.concat('outraString') // Terceira forma
```

<a id='endwith'></a>

## Endwith

Para checar se a string acaba com o valor que você informar

> Retorna um boolean

```javascript
'string'.endsWith('a') // false
```

<a id='replace'></a>

## replace

Usado para trocar valores

```js
'teste'.replace('s', 'x') // texte
```

<a id='length'></a>

## length

Pegar o comprimento da string (Conta a quantidade de caracteres)

```javascript
'teste'.length //5
```

<a id='slice'></a>

## slice

Usado para buscar um range de caracteres

```javascript
'teste'.slice(2,4) // 's'
'teste'.slice(1,-1) // este
```

<a id='subString'></a>

## subString

Retorna os valores dentro de um range informado

```javascript
'teste'.subString(0, 2) // te
```

<a id='split'></a>

## split

Esse cara aqui consegue fatiar sua string, você informar em qual caracter ele vai fatiar e pronto :3

> Retorna um array

```javascript
'isso vai cortar'.split(' ') // ['isso', 'vai', 'cortar']
```

<a id='toUpperCase'></a>

## toUpperCase

Função utilizada para deixar em maiusculo

```js
'teste'.toUpperCase() // 'TESTE'
```

<a id='toLowerCase'></a>

## toLowerCase

função utilizada para deixar em minusculo

```js
'TESTE'.toLowerCase()
```

<a id='expressoes-regulares'></a>

# Expressões regulares

<a id='match'></a>

## match

Usado para encontrar uma cadeia de caracteres (Regex) em uma string.

> Retorna um array

```js
//Encontrar somente as letras minusculas
'teste'.match(/[a-z]/g) // ['t', 'e', 's', 't', 'e']
//Encontrar letras minusculas e maisculas
'Teste'.match(/[a-zA-Z]/g) //['T', 'e', 's', 't', 'e']
//Encontrar números
'tenho 1 número'.match(/[0-9]/g) // [1]
```

<a id='search'></a>

## search

Usado para encontrar um valor, passando como parametro uma cadeia de caracteres (Regex)

> Retonar o index / posição do elemento encontrado

```js
'Teste'.search(/s/) 2
```

<a id='replace-regex'></a>

## Replace com regex

Da para utilizar as cadeias de carateres no replace também

```js
// Trocar a primeira letra 's' para 'x'
'tesssste'.replace(/s/, 'x') // texssste
// Trocar todas as letras 's' para 'x'
'tesssste'.replace(/s/g, 'x') // texxxxte
```

<a id='numbers'></a>

# Numbers

> JavaScript faz as contas com base no padrão IEEE 754-2008. Existe sempre uma pequena imprecisão na hora de calcular numéros flutuantes abaixo de 1 (Com cadas decimais).

```javascript
let num1 = 10 // number
let num2 = 10.0123012 // number
```

<a id='numero-string'></a>

## Numero para string

```javascript
let num = 10 
num.toString() // '10'
```

<a id='casas-decimais'></a>

## Casas decimais

<a id='tofixed'></a>

### tofixed - Escolher quantas casas decimais aparecer

```javascript
let num = 10.123124324
num.toFixed(2) // 10.12
//number.toFixed(numero_casas_decimais)
```

<a id='saber-numero-inteiro'></a>

## Saber se o numéro é inteiro

```javascript
let num1 = 10
Number.isInteger(num1) // true

let num2 = 10.312
Number.isInterger(num2) //false -  É um Number (Casas decimais)
```

<a id='saber-nan'></a>

## Saber ser é um NaN (Not a number)

```javascript
const ola = 'ola'
Number.isNaN(ola) //true

const num = 10
Number.isNaN(num) //false
```

<a id='padrao-calculo'></a>

## Padrão de calculo - IEEE 754-2008

```javascript
let num1 = 0.1
let num2 = 0.3

console.log(num1 + num2) //0.399999999999 - Aqui está a imprecisão
// Solução
console.log(parseFloat((num1 + num2).toFixed(2)) //Pouco elegante mas funciona
console.log(Number((num1 + num2).toFixed(2)) //Pouco elegante mas funciona
(num1 * 100) + (num2 * 100) / 100 // 0.4 - Muito pouco elegante, mas funciona
```

<a id='math'></a>

# Math

<a id='arredondar-numeros'></a>

## Arrendondar numeros

<a id='para-baixo'></a>

### Para baixo - Math.floor

```js
Math.floor(9.123) // 9
```

<a id='para-cima'></a>

### Para cima - Math.ceil

```js
Math.ceil(9.123) // 10
```

<a id='para-mais-proximo'></a>

### Para o mais próximo - Math.round

- Abaixo de 50 arredonda par abaixo
- Acima de 0.49 arredonda para cima

```javascript
Math.round(0.49) // 0
Math.round(0.50) // 1
```

<a id='achar-maior-menor-numero'></a>

## Achar maior e menor numero

```javascript
let numbers = [1,2,3,4,5,6]
Math.min(numbers) //1
Math.max(numbers) // 6
```

<a id='gerar-aleatorio'></a>

## Gerar numeros aleatórios

```javascript
Math.random() // 0.56487434
//gerar aleatório em um intervalo
Math.random() * (max - min) + min
//exemplo
const number = Math.random()* (10 - 5) + 5 // numeros entre 5 e 10
```

<a id='potenciacao'></a>

## Potenciação

```javascript
Math.pow(2,2) // 4
// Mas assim também da certo
2**2 // 4
```

<a id='divisao-zero'></a>

## Divisão por zero

> É necessário tomar cuidado, pois o JavaScript permite a divisão por zero classificando a variavel como infinity e true

```js
10 / 0 // Infinity - true
```

<a id='tratamento-divisao-zero'></a>

### Tratando divisão por zero

[Maneira citada StackOverflow por Mike Samuel](#https://stackoverflow.com/questions/8072323/best-way-to-prevent-handle-divide-by-0-in-javascript)

```js
function notZero(n) {
  n = +n;  // Coerce to number.
  if (!n) {  // Matches +0, -0, NaN
    throw new Error('Invalid dividend ' + n);
  }
  return n;
}

numerator / notZero(denominator)
```

<a id='arrays'></a>

# Arrays

> Deve tomar cuidado com atribuições diretas, isso ocasiona em ponteiros. Então tudo oque você fizer em uma variavel ira refletir na outra. Para isso existem maneiras corretas descritas abaixo para fazer a atribuição de valores.

```javascript
const users = ['Albert', 'Nikola', 'Leonardo', 1, 2, 3] //Da para colocar oque quiser aqui no meio
users[0] //Albert
users[0] = 'Einstein'
users[0] // Einstein
```

<a id='obter-valores-array'></a>

## Obter valores do array

```javascript
const users = ['Albert']
users[0] // Albert
```

<a id='mudando-valores-array'></a>

## Mudando os valores do array

```javascript
const users  = ['Albert']
users[0] = ['Nikola']
users[0] // Nikola
```

<a id='passando-valores-arrays'></a>

## Passando valores entre arrays

Aqui é necessário ter atenção, para não referenciar diretamente um array a outra variavél. Pois dessa forma a variavel vai apontar para o mesmo endereco de memoria do array.

Exemplo

```js
const array_1 = [1,2,3]
const array_2 = array_1

array_2[2] = 123123123

// Eles teram os mesmo valores, pois as duas variaveis apontam para o mesmo endereço de memoria
array_1 // [1,2,123123123]
array_2 // [1,2,123123123]
```

**Uma das maneiras correta de se passar o valor do array para outra variavél**

```js
const array_1 = [1,2,3]
const array_2 = [...array_1] // maneira correta de se fazer 
array_2[2] = 123123123

array_1 // [1,2,3]
array_2 // [1,2,123123123]
```

> Esses ... que está antes de array_1 [...array_1] significa que todo o valor de array_1 será espalhado, e como no caso a variável array_2 está recebendo [...array_1], significa que o valor de array_1 será espalhado dentro de array_2.

<a id='comprimento-array'></a>

## Comprimento do array - length

```javascript
const users = ['Albert', 'Nikola', 'Leonardo']
users.length //3
```

<a id='inserir-valores-array'></a>

## Inserir valores no array - push/unshift

```javascript
const users = ['Albert', 'Nikola']

//Inserir no final
users.push('Leonardo')
users // ['Albert', 'Nikola', 'Leonardo']

//Inserir no começo
users.unshift('Thomas')
users // ['Thomas', 'Albert', 'Nikola', 'Leonardo']
```

<a id='remover-valores-array'></a>

## Romover valores do array - pop/shift/delete

```javascript
const users = ['Albert', 'Nikola', 'Leonardo']

//Remover do final
// pop retorna o valor removido
users.pop()
users // ['Albert', 'Nikola']

//Remover do começo
//shift retorna o valore removido
users.shift()
users // ['Nikola']

//Remover item deixando espaço vazio
delete users[0]
users // [<emptyitem>]
```

<a id='fatiar-array'></a>

## Fatiar um array - slice

Quando o array é fatiado pelo metodo slice, ele não tem o seu valor realmente modificado,  slice apenas retorna os valores entre o intervalo que você informar.

```js
const users = ['Albert', 'Nikola', 'Leonardo'] 
users.slice(0,2) // ['Albert' , 'Nikola']
users.slice(0,-1) // ['Albert', 'Nikola', 'Leonardo'] 
```

> -1 Inidica a última posição do array

<a id='checar-instancia-array'></a>

## Checkar instancia de array

```javascript
const users = ['Albert', 'Nikola']
users instanceof Array // true
```

<a id='remover-inserir-valores-splice'></a>

## Remover e inserir valores - Splice

Esse método pode remover ou inserir valores.

```javascript
// array.splice(posicao_inicial, quantidade_elementos_a_deletar, addElement, addElement, addElement)
const array = [1,2,3,4,5]
const elementos_removidos = array.splice(3,2)
array // [1,2,3]
elementos_removidos // [4,5]

//Example utilizando MAX_VALUE
const array = [1,2,3,4,5]
const elementos_removidos = array.splice(2, Number.MAX_VALUE)
elementos_removidos // [3,4,5]

//Adicionando valores com splice
const array = [1,2,3,4,5]
array.splice(3,0,'value')
array // [ 1, 2, 3, 'value', 4, 5 ]

//Removendo e adicionando ao mesmo tempo
const array = [1,2,3,4,5]
array.splice(3,2,'Albert', 'Nikola')
array // [1,2,3,'Albert', 'Nikola']
```

<a id='concatenar-array'></a>

## Concatenar array

```javascript
const array1 = [1,2,3,4]
const array2 = [5,6,7,8]

array1.concat(array2) // [1,2,3,4,5,6,7,8 ]
```

<a id='filtrar-array'></a>

## Filtrar o array

> Sempre retorna um array

```javascript
//forma classica
const array = [1,2,3,4,5]

function callBackFilter(value, index, array){
    return value > 2; 
}

const newArray = array.filter(callBackFilter)
newArray // [3,4,5]

//Forma mais elegante
const array = [1,2,3,4,5]

const newArray = array.filter(value => value > 2)
newArray // [3,4,5]

//Da para fazer assim também
const array = [1,2,3,4,5]

const newArray = array.filter((value, index, array) => {
    // use value index array logic
    //return 
})
```

<a id='mapear-array'></a>

## Mapear o array

Esse método permite passar por todas as posições do array. É bem parecido com um for, você também pode colocar sua lógica para ser executada em cada posição.

> Sempre retorna um array

```javascript
const array = [1,2,3]

array.map((value,index,array) => {
    return value
})

// Exemplo - retonar um novo array que valores dobrados
const array = [1,2,3]
const newArray = array.map(value => value * 2)
newArray // [2,4,6]

// Exemplo - Retornar apernas o nome dos objetos
const peoples = [
    {name: 'Albert', surname: 'Einstein'},
    {name: 'Nikola', surname: 'Tesla'}
]

const arrayWithNames = peoples.map(value => value.name)
arrayWithNames // ['Albert', 'Nikola']
```

<a id='reduce'></a>

## Reduce

Permite você por todas as posições, e também ter um único retorno. Por exemplo fazer a soma de todos os valores dentro do array, aqui teremos um unico retorno que será o valor total.

> Reduzir array a um elemento

```javascript
// Exemplo de soma
const array = [1,2,3]
const total = array.reduce(function(acumulador, valor, indice, array){
    acumulador += valor
    return acumulador
})
total // 6

// Exemplo de retorno de array
const array = [1,2,3]
const anotherArray = array.reduce(function(acumulator, value ){
    acumulador.push(value)
    return acumulador
}, [] )// Valor inicial do acumulador)
anotherArray // [1,2,3]

// Exemplo - Retornar o mais velho
const pessoas = [
    {name: 'Albert', age: 76},
    {name: 'Nikola', age: 86},
    {name: 'Isaac', age: 84}
]

const pessoaMaisVelha = pessoas.reduce(function(acumulador, valor){
    // O acumulador sempre inicia pegando o valor da primeira posição
    // O 'Valor' sempre inicia pegando o valor da segunda posição
    if (acumulador.age > valor.age) return acumulador
    return valor
})

pessoaMaisVelha // {name: Nikola, age: 86}
```

<a id='foreach'></a>

## Foreach

> Apenas passa sobre o array, assim como um for clássico

```javascript
const array = [1,2,3]
array.forEach((value, index, array) => {
    //logic
})
```

<a id='funcoes'></a>

# Funções

<a id='cria-funcao'></a>

## Criar função - function

> Funções podem ter retornos ou não, assim como parametros

```js
//Quando se declar uma função da maneira abaixo, a função poderá ser chamada em qualquer lugar do código - Efeito Hosting
//Escopo básico de função
function name (parameters) {
    //logic
}

// Função com retorno
function teste(){
    return alert('teste')
}
```

<a id='arrow-function'></a>

## Arrow function

É a mesma coisa que a função normal, porém ela veio para deixar o código mais elegante

```javascript
//Escopo básico
(parameters) => {logic}

//example
//Aqui como é uma linha não precisa de return, o return é automatico
(num) => num ** 0.5
//or
num => num ** 0.5
//or
const raiz = num => num ** 0.5
```

<a id='parametro-funcao'></a>

## Parametros de função

```javascript
//Pegar parametro via desestruturação de objeto
const obj = { name: 'Albert', surname: 'Einstein'}

//Pegando somente o nome
function getName({name}) {
    console.log(name)
}
getName(obj) // Albert

//Pegar valores via desestruturação de um array
const array = [1,2,3,4]

const getThreeFirstNumbers = ([num1,num2,num3]) => {
    console.log(num1,num2,num3)
}
getThreeFirstNumbers(array) // [1,2,3]

// Função com valores padrões. Funciona também para desestruturação
function soma(x=10, y=20){
    return x + y
}
```

<a id='parametro-resto'></a>

### Parametros de resto - Rest operator

O parametro de resto deve ser o ultimo parametro da funcão

```js
//Rest operator
const a = 1
const b = 2
const c = 3
const d = 4
const e = 5

function example(a,b,...rest){
    console.log(a,b,rest)// 1 2 [3,4,5]
}

example(a,b,c,d,e)
```

<a id='funcao-dentro-variavel'></a>

## Funções dentro de uma variavel - Function expression

```javascript
const sayHello = function () {
    console.log('Hello')
}
// or
const sayHello = () => console.log('Hello')
```

<a id='funcao-como-parametro'></a>

## Passando função como parametro

```javascript
const sayHello = () console.log('Hello')
const talking = (sayHello) => sayHello()
```

<a id='arguments'></a>

## Arguments

<a id='arguments-functions'></a>

### Arguments em functions 

Funciona apenas em function e não em arrow function. Para fazer funcionar de forma semelhante em  arrow function, utilize o rest operator

```javascript
function soma (){
    let total = 0
    //dentro de arguments, se encontra todos os valores
    for (let argument of arguments){
        total += Number(argument)
    }
    return total
}
//Vai somar todos esses valores 
soma(1,2,3,4,5,123,123,4,56,7,23,8)

```

<a id='closures'></a>

## Closures - Function dentro de function

Habilidade da função acessar seu escopo léxico (Onde foi definida)

```javascript
function multiplica(multiplicador){
    return function(n){
        return n * multiplicador
    }
}

const duplica = multiplica(2) // Recebe a função dentro da função, por conta do return
duplica(4) // 8
```

<a id='funcao-callback'></a>

## Função de callback

Passar funções para ser executadas após outras funções. É bem semelhante ao exemplo mais acima

```javascript
const first = (callback) => {
    console.log('first')
    if (callback)
        callback()
}
const second = (callback) => {
    console.log('second')
    if (callback)
        callback()
}
const third = (callback) => {
    console.log('third')
    if (callback)
        callback()
}

first(() => second(() => third())) // first second third
```

<a id='IIFE'></a>

## IIFE - Immediately invoked function expression

> A função é executada assim que é invocada

```javascript
// Escopo classico
(function (parameters){
    // logic
})(parameters);
// Escopo com arrow function
(() => {
    //logic
})()
//exemplo
(() => console.log('teste'))()
```

<a id='funcao-geradora'></a>

## Funções geradoras

Entrega um valor por chamada. Quando se utilizar [return] a função geradora será parada

> A funcão geradora podem usar * 

```javascript
function* geradora1() {
    // ... Lógica
    yield 'valor1'
    // ... Lógica
    yield 'valor2'
    // ... Lógica
    yield 'valor3'
}

const valorGerado = geradora1()
valorGerado.next() // valor 1
valorGerado.next() // valor 2
valorGerado.next() // valor 3

//Exemplo de delegação
function geradora2(){
    //Delega a primeira chamada a geradora 1
    yield* geradora1()
    yield 4
    yield 5
    yield 6
}

//Consultar os valores da função geradora
const valores = geradora2()
for (value of valores){
    console.log(valores)
}

//Utilizando chamadas de funções em sequencia com funções geradoras
const function_1 = () => console.log('function 1')
const function_2 = () => console.log('function 2')

function functionsSequence(){
    yield function_1()
    yield function_2()
}

const callInSequence = functionsSequence()
callInSequence.next() //function_1
callInSequence.next() //function_2
```

<a id='funcao-recursiva'></a>

## Funções recursivas

Função que chama ela mesma

```javascript
//Fará o laço de repetição 5 vezes
const recursive = (max) => {
    if (max >= 5)
        return
    max++;
    recursive(max)
}
recursive(0)
```

<a id='objetos'></a>

# Objetos

> Lembrete - Quando for criar um metodo que se repete em cada objeto, é bem mais performatico utilizar o prototype. Para que o metodo seja criado em apenas um lugar ;)

<a id='cria-objeto'></a>

## Criar objeto

```js
// Criação literal - Dicionario
const pessoa = {
    nome: 'Albert',
    sobrenome: 'Einstein'
}
// or
const pessoa = new Object()
pessoa.nome = "Albert"
pessoa.sobrenome = "Einstein"
```

<a id='valores-objeto'></a>

## Acessar valores do objeto

```javascript
const people = {
    name: 'Albert',
    surname: 'Einstein'
}

people.name // Albert
people['name'] // Albert
```

<a id='fabrica-objeto'></a>

## Fabrica de objetos

```js
// forma padrão
function criaPessoa (name, surname){
    return {
        name,
        surname,
        getAllName: () => `${this.name} ${this.surname}`
    }
}

//Se os parametros tiverem os mesmos nomes dos atributos, ficara dessa forma.

//Equivalente a forma de cima
function criaPessoa (nome, sobrenome){
    return {
        nome,
        sobrenome
    }
}
```

<a id='factory-functions'></a>

## Factory Functions

> Funções fabricas

```javascript
const createPeople = (name, surname) => {
    return {
        name,
        surname,
        sayHello: () => {
            //This sempre se refere ao objeto chamado
            return `Hello! I'm ${this.name}.`
        }
    }
}

const people = createPeople()
people.sayHello()
```

<a id='getter'></a>

### Utilizando Getter 

```js
createPeople = (name, surname, age) => {
    name,
    surname,
    age,
    get completeName(){
        return `${this.name} ${this.surname}`;
    }
}

const people = createPeople('Albert', 'Einstein', 76 )
people.compleName // Albert Einstein
```
<a id='setter'></a>

### Utilizando Setter

```js
createPeople = (name) => {
    return {
        name,
        surname: '',
        set setSurname(surname){
            this.surname = surname
        }
    }
}

const people = createPeople('Albert')
people.setSurname = 'Einstein'
people.surname // Einstein
```

<a id='constructor-functions'></a>

## Contructor functions

> É interessante iniciar com letra maiuscula por convenção.

```javascript
function Pessoa(nome, sobrenome) {
    //Atributos privados
    const id = 1;
    //metodos privados
    const metodo_privado = () => {}
    //Atributos publicos
    this.nome = nome;
    this.sobrenome = sobrenome;

    this.metodo = function (){

    };
}

const pessoa1 = new Pessoa('Albert', 'Einstein')
const pessoa2 = new Pessoa('Nikola', 'Tesla')
```

<a id='congelar-objeto'></a>

## Congelar objeto - freeze

Não permitir alteração no objeto.

```javascript
//Congelar na criação
function People(name, surname) {
    this.name = name
    this.surname = surname

    Object.freeze(this)
}

//Congelar depois da criação
function People(name, surname) {
    this.name = name
    this.surname = surname
}

const people = new People('Albert', 'Einstein')
Object.freeze(people)
```

<a id='metodo-objeto'></a>

## Métodos do objeto

```javascript
const pessoa = {
    nome,
    sobrenome,

    falar(){
       console.log('Hello World!') 
       console.log(`i'm ${this.nome}!`)
    },

    pular(){
        console.log(`${this.nome} pulou!`)
    }
}
```

<a id='propriedade-objeto'></a>

## Propriedades do objeto 

<a id='apenas-um-atributo'></a>

### Apenas um atributo

```js
function People (name, surname){
    this.name = name
    this.surname = surname

    Object.defineProperty(this, 'surname', {
        enumerable: true, // show key
        value: surname, // show value
        writable: false, // update
        configurable: true, // reset configurations
    })
}
const people = new People('Albert', 'Einstein')
```

<a id='todos-atributos'></a>

### Todos os atributos

```js
function People (name, surname){
    this.name = name
    this.surname = surname

    Object.defineProperties(this, {
        name : {
            enumerable: true, // show key
            value: name, // show value
            writable: false, // update
            configurable: true, // reset configurations
        },
        surname: {
            enumerable: true, // show key
            value: surname, // show value
            writable: false, // update
            configurable: true, // reset configurations
        }
    })
}

const people = new People('Albert', 'Einstein')
Object.keys(people) // name, surname
```

<a id='prorpiedades-objeto-geter-setter'></a>

## Propiedades do objeto com getters e setters

```javascript
function People (name, surname){
    this.name = name
    // let surname = surname
    Object.defineProperty(this, 'surname', {
        enumrable: true,
        configurable: true,
        get: function() {
            return surname
        },
        set: function(value) {
            if(typeof value !== 'string')
                throw new TypeError('message')
            surname = value
        }
    })
}

const people = new People('Albert', 'Einstein')
people.surname // 'Einstein'
people.surname = 1 // Error :)
```

<a id='metodos-uteis-objetos'></a>

## Metodos uteis para objetos

<a id='copiar-objeto'></a>

### Copiar objeto

```javascript
const people = {name: 'Albert', surname: 'Einstein'}
//example 1
const copyPeople = {...people, age: 76}
//example 2
const copyPeople = Object.assign({}, people, {age : 76})

people // {name: 'Albert', surname: 'Einstein'}
copyPeople // {name: 'Albert', surname: 'Einstein', age: 76}
```

<a id='checar-propiedade-objeto'></a>

### Checar como estão as propiedades do objeto

```javascript
const people = {name: 'Albert', surname: 'Einstein'}
Object.getOwnPropertyDescriptor(people, 'name') /*
    {value: 'name',
    writable: true,
    enumerable: true,
    configurable: true}
*/
```

<a id='pegar-valor-objeto'></a>

### Pegar o valor do objeto

```javascript
const people = {name: 'Albert', surname: 'Einstein'}

Object.values(people) // ['Albert', 'Einstein']
```

<a id='pegar valor-objeto-entries'></a>

### Pegar valor do objeto com entries

> Retorna um array com os valores do objeto

```javascript
const people = {name: 'Albert', surname: 'Einstein'}
console.log(Object.entries(people)) // ['name', 'Albert'], ['surname', 'Einstein']
```

<a id='prototypes'></a>

## Prototypes 

> Cara é muito bom! Cria uma função apenas para todos os objetos. Mantendo assim uma melhor performance.

```javascript
function People(name, surname){
    this.name = name
    this.surname = surname
}

People.prototype.completeName = function(){
    return `${this.name} ${this.surname}`
}
```

<a id='manipulacao-prototype'></a>

### Manipulação de prototype

```js
const object_A = { keyExample_A: 'ExampleA'}
const object_B = { keyExample_B: 'ExampleB'}

// O object_A vai ser o protótipo do object_B
Object.setPrototypeOf(object_B, object_A)
object_B.keyExample_A // 'ExampleA'
```

<a id='copiar-objeto-prototype'></a>

### Criando objeto pelo prototype

```javascript
function People(name) {
    this.name = name
    People.prototype.getName = function (){
        return `Here return name`
    }
}

const example = Object.create(People.prototype, {
    newKey: {
        writable : true,
        configurable: true,
        enumerable : true,
        value: 'example'
    }
})

example // People {newKey: 'Example'}
example.getName() // Here return name
```

<a id='herança'></a>

## Herança

```javascript
function Produto(nome, preco){
    this.nome = nome
    this.preco = preco
}
Produto.prototype.aumento = function(quantia){
    return this.preco += quantia
}

function Camiseta(nome, preco, cor){
    //Onde a herança acontece
    Produto.call(this, nome, preco)
    this.cor = cor
}

//Setar o mesmo prototype do produto
Camiseta.prototype = Object.create(Produto.prototype)
// Para setar o objeto como uma Camiseta, senão vai ficar como produto
Camiseta.prototype.constructor = Camiseta
// Camiseta se torna uma especialização de produto

const camiseta = new Camiseta('Camiseta', 100, 'Azul')
camiseta.aumento(10)
camiseta.preco // 110
//Para reescrever um metodo do pai
Camiseta.prototype.aumento = function(parameters){
    //logic
    //Quando aumento for chamado, ele fará oque essa função pedir, em vez de fazer oque o pai está passando
}
```

<a id='polimorfismo'></a>

## Polimorfismo

> Fazer uma classe filha se comportar de forma diferente do pai (Sobreescrita de métodos)

<a id='factory-functions-prototype'></a>

## Factory Functions + Prototype

```javascript
function createGenius(name, surname) {
    const pessoaPrototype = {
        sayHello (){
            console.log('Hello')
        }
    }

    return Object.create(pessoaPrototype, {
        name: {value: name},
        surname: {value :surname}
    })
}
const people = createGenius('Albert', 'Einstein')
```

<a id='composing-mixing'></a>

## Composing / Mixing 

```javascript
const sayHello = {
    sayHello () {
        console.log(`Hello i'm ${this.name}!`)
    }
}

const peoplePrototype = {...sayHello}
// const peoplePrototype =  Object.assign({}, sayHello)

function createGenius(name, surname) {
    return Object.create(peoplePrototype, {
        name: {value: name},
        surname: {value: surname}
    })
}

const people = createGenius('Albert', 'Einstein')
```

<a id='objet-map'></a>

## Object map

```javascript
const genius = [
    {name: 'Albert', surname:'Einstein'},
    {name: 'Nikola', surname: 'Tesla'},
    {name: 'Charles', surname: 'Darwin'}
]

const newGenius = new Map()
for (const people of genius) {
    const {name} = people
    newGenius.set(name, {...people})
}
console.log(newGenius)
console.log(newGenius.get('Albert'))
```

<a id='class'></a>

# Class

> Cara que maravilha linkar os prototypes aqui

```javascript
class People {
    constructor(name, surname){
        this.name = name,
        this.surname = surname
    }

    sayHello(){
        console.log(`Hello i'm ${this.name}!`)
    }
}
const people = new People()
```

<a id='getter-setter-class'></a>

## Getter & Setter

```javascript
const _velocity = Symbol('Velocity')
class Car {
    constructor(name){
        this.name = name
        this[_velocity] = 0
    }

    get velocity(){
        return this[_velocity]
    }
    
    set velocity(value){
        if (typeof value !== 'number') return
        if (value >= 100 || value <= 0) return

        this[_velocity] = value
    }
}

const car = new Car('Fusca')
car.velocity = 50
car.velocity // 50 
```

<a id='herança-class'></a>

## Herança com classes

```javascript
class Genius{
    constructor(name){
        this.name = name
    }

    sayHello(){
        console.log('Hello')
    }
}

class People extends Genius{
    constructor(name, age){
        super(name) //Construtor pai
        this.age = 76
    }

    //Sobre escrever o metodo da classe pai
    sayHello(){
        console.log("I'm another hello")
    }
}
```

<a id='metodos-estaticos'></a>

## Metodos estaticos

> Acessa a classe sem instanciar a classe

```javascript
class Genius{
    constructor(name){
        this.name = name
    }

    //metodo de instancia
    sayHello(){
        console.log('Hello')
    }
    //metodo estatico
    static sayHelloToEverybody(){
        console.log('Hello world!')
    }
}

Genius.sayHelloToEverybody() // Hello world
```

### Valores primitivos e por referencia

#### Valores primitivos (imutaveis)

> Esses valores criam uma nova cópia quando são copiados

- string
- number
- boolean
- undefined
- null
- bigint
- symbol

```javascript
// Não da para mudar fazendo isso
let a = 10
a[0] = 20 //Isso não muda o valor
a // 10
```

> Para que os valores por referencia não apontem para o mesmo lugar da memoria, você pode fazer da forma abaixo

```javascript
//vou usar array, mas funciona da mesma forma se utilizar objeto
const original = ['Albert', 'Nikolas'] 
const duplicate = [...users]

//Dessa forma se você alterar duplicate, original não sera alterado

duplicate.push('Leonardo')
original // ['Albert', 'Nikolas']
duplicate // ['Albert', 'Nikolas', 'Leonardo']
```

#### Valores do referencia (mutavel)

> Esses valores apontam para o mesmo lugar da memória quando são copiados

- Array
- Object
- Function

```javascript
//Da para mudar seus valores
const teste = [1,2,3]
teste[0] = 50
teste // [50,2,3]
```

## window.document

```js
document.body.innerHTML = 'teste'
document.body.innerHTML += 'teste <br/>'
```

## Seção 3 - JavaScript Lógica de programação

### Operações de comparação

-  \> Maior que
-  < Menor que
-  \> Maior ou igual que
-  <= Menor ou igual que
-  == Igualdade
-  === Igualdade estrita - Checa valor e tipo (Recomendado)
-  != Diferença
-  !== Diferença estrita - Checa valor e tipo (Recomendado)

### Operadores lógicos

- && (and - e)
- || (or - ou)
- !  (not - negação)

> And - Para a comparação lógica ser verdadeira, todas as outras comprações devem ser verdadeiras
> 
> Or - Para a comparação lógica ser verdadeira, pelo menos uma das comparações devem ser verdadeiras
> 
> ! - Nega a operação lógica

Exemplo

```javascript
//&& - And - Todas devem ser verdadeiras
0 === 0 && 1 === 1 //true
0 === 0 && 1 === 2 //false

//|| - Or - Pelo menos uma dever ser verdadeira
0 === 0 && 1 === 1 //true
0 === 0 && 1 === 2 //true
0 === 1 && 1 === 2 //false

//! - Negação
true //true
!true //false

false //false
!false //true

!!false //false
!!!false //true
```

### Avaliação de curto circuito (Short-circuit)

> Retorno de valores e operações lógicas

#### Valores que avalião em false

- false
- 0
- '' 
- null
- undefined
- NaN

#### Operador && and

> false - Retorna o valor falso quando for encontrado
> 
> true - Sempre retornará o ultimo valor avaliado

```javascript
//false
'Luiz Otavio' && 0 && 'Maria' // 0 pois 0 avalia em falso
//true
'Luiz' && 'Willian' && 'Maria' // Maria - Retorna o ultimo valor avaliado
```

#### Operador || or

> Retorna o primeiro valore verdadeiro encontrado
> 
> Caso não haja valor verdadeiro, retorna o ultimo valor falso encontrado

```javascript
false || false || 'Willian' || true // 'Willian' - Pois Willian é o primeiro resultado verdadeiro encontrado
```

Exemplos de validação
```javascript
const cor = ''
const corPadrao = cor || '#fcfcfc'
corPadrão // '#fcfcfc' - Pois '' é avaliado como false
```

### Estruturas condicionais

#### if else if e else

- If pode ser utilizado sozinho
- Para se usar else, é necessário ter um if antes
- Pode haver vários if else
- Só pode haver um else na checagem
- Não é necessário ter else/else if

```javascript
//estrutura simples
if (true)
    return 'verdadeiro'
else
    return 'falso'

//estrutua composta
if (true)
    return 'verdadeiro'
else if (false)
    return 'falso'

//exemplo
const num = 10

if (num > 9){
    console.log(num)
    console.log('Numero maior que 9')
} else if (num === 10) {
    console.log(num)
    console.log('Numero igual a 10')
} else if (num < 5) {
    console.log(num)
    console.log('Numero menor que 5')
} else {
    console.log(num)
    console.log('Numero entre 9 e 5')
}
```

#### Avaliação por curto-circuito

> É utilizada para tomar uma ação somente quando a condição for verdadeira. Esse método de avaliação não aceita else.

```javascript
condition && trueLogic
//Exemplo
1 === 1 && console.log('True') // true
```

#### Operação ternario

> Pode substituir parte do código com condicionais mais simples

```javascript
condition ? true : false
//example
5 > 10 ? 'Maior' : 'Menor'
```

### Objeto date

```javascript
const data = new Date() // Data atual por padrão
new Date(0) // 01/01/1970 - Timestamp unix ou época unix
new Date(2019, 3, 20, 15, 14, 27, 500) // 2019/4/20 - 15:14:27:500
new Date('2019-04-20 20:20:59')
Date.now() //Data atual em milesimos de segundos
new Date(Date.now()) // Data atual
//data.toString()
```

#### Obter ano, mes, dia, horas, minutos, segundos, milesimos

```js
const data = new Date()
data.getFullYear() //ano
data.getMonth() //mes - Começa do zero
data.getDate() //dia
data.getHours() //horas
data.getMinutes() //minutos
data.seconds() //segundos
data.getMilliseconds() //milesimos
data.getDay() //dia da semana - 0 Domingo - Sábado
```

#### Formatar data

```javascript
const data = new Date()
data.toLocaleTimeString('pt-BR', {
    hour: '2-digit',
    minute: '2-digit',
    second: '2-digit',
    hour12: false
}) // 00/00/00 00:00:00
```

### Switchs

```js
switch (variable){
    case condition:
        //logic
        break
    case condition:
        //logic
        break
    default:
        //logic
        break //Não tem necessidade
}
```

### Atribuição via desestruturação (Arrays)

```javascript
//exemplo simples
let a
let b
let c
[a,b,c] = [1,2,3]
a //1
b //2
c //3

//desestruturação
const numbers = [1,2,3,4]
const [first, second, ...rest] = numbers
first // 1
second // 2
rest // [3, 4]

//pulando valores
const [number1 , , number3] = numbers
number1 // 1
number3 // 3
```

### Atribuição via desestruturação (Objetos)

```javascript
const awesomePeople = {
    name: 'Albert',
    surname: 'Einstein',
}

const {name, surname} = awesomePeople
// com valores padrões, para caso os valores não existam no objeto
const {name='Albert', surname='Einstein'} = awesomePeople
//mudar o nome das variaveis para não seguir os nomes dos atributos dos objetos
const {name: sayYourName, surname: sayYourName} = awesomePeople
sayYourName // 'Albert'
sayYourSurname // 'Einstein'

//another example

const people = {
    name: 'name',
    address: {
        street: 'california',
        number: 124
    },
    age: 10
}

const {name, address:{street}, ...rest} = people
name // 'name'
street // 'california'
rest // age: 10
```

### Estrutura de repetição

- For clássico - Geralmente com iteráveis (Array ou string)
- For in - Retorna o indice ou chave (string, array, objetos)
- For of - Retorna o valor (iteráveis, arrays ou string)

#### For

```javascript
for (let i = 0; i > length; i++){
    //logic
}
```

#### For in

```javascript
const names = ['Albert', 'Nikola', 'Thomas']
for (let index in names){
    // first enter
    index //1
    // Second enter
    index // 2
}

const people {
    name: 'Albert',
    surname: 'Einstein'
}

for (let key in people){
    //first enter
    console.log(people[key]) // Albert
    //second enter
    console.log(people[key]) //Einstein
}
```

#### For of

```javascript
for (let value of list){
    //logic
}

//example
const peoples = [
    {name: 'Albert'},
    {name: 'Nikola'},
    {name: 'Thomas'},
]

for (let people of peoples){
    //first
    people // {name: Albert}
    //Second
    people // {name: Nikoa}
    //third
    people // {name: Thomas}
}

```

### DOM - Document object model

> Estrutura básica do DOM
> 
> Window > Document > Html > Head | Body

> O Dom possui uma api que nos permite interagir com ele. Podemos criar e modificar os dados que estão dentro dele

#### Seletores

##### Selecionar elemento

```javascript
document.getElementById('id')
document.querySelector('#id') //mais moderno
document.querySelector('.class') //mais moderno
```

##### Selecionar mais de um elemento
```javascript
documet.querySelectorAll('element')
// Example
const elements = document.querySelectorAll('p')
elements // NodeArray p's

//another example
const container = document.querySelector('.container')
container.querySelectorAll('p') // Get all p's inside in container

//Select with contains
container.classList.container('class')
```

##### Buscar pai de um elemento

```javascript
const element = document.qurySelector('p')
element.parentElement // elemento pai
```

#### Remover elmento

```javascript
const element = document.querySelector('element')
element.remove()
```

##### remover pai do elemento

```javascript
const element = document.querySelector('element')
element.parentElement.remove()
```

#### Pegar o texto de um elemento

```javascript
const element = document.querySelector('element')
element.innerText //Return text
```

#### Eventos e listeners

##### Adicionar listener a um elemento

```js
const input = document.querySelector('.input')
input.addEventListener('event', function(event){
  //logic  
})

//Example
const input = document.querySelector('.input')
input.addEventListener('click', () => console.log('teste'))
```

##### Selecionar element via evento

```javascript
document.addEventLister('click', (event) => {
    const element = event.target
})
```

```js
const container = document.querySelector('.container')

```

#### Criar elemento

```javascript
document.createElement('element')
//example
const p = document.createElement('p')
p.classList.add('class-name')
p.innerHTML += 'text'

//Exemplo de criação de nó de texto
const textNode = document.createTextNode('text')
p.appedChild(textNode) // inserir o texto na tag p
```

#### Inserir dados a elemento

```javascript
const example = document.querySelector('#id')
example.innerHTML = 'html'
axample.innerText = 'text'
```

##### Inserir filhos em um elemento

- appendChild(element)

```javascript
const example = document.querySelector('#id')
//criar p
const p = document.createElement('p')
//Adicionar class a p
p.classList.add('class-name')
//Adicionar p dentro de example
example.appendChild(p)
```

##### Pegar estilos de elementos

```javascript
const styleBody = getComputedStyle(document.body) // get all styles of body

//get background of body

styleBody.backgroundColor // background of body 
```

##### Mudar estilos de um elemento

```javascript
//Exemplo de mudança de cor
const element = document.querySelector('.class')
element.style.backgroundColor = 'red' // mudar a cor
```

### While do while

#### While

> Checa a condição e depois entra no laço de repetição

```javascript
while (i <= 10){
    //logic
    i++;
}
```

#### Do while

> Entra pelo menos uma vez no laço e depois checa a condição

```javascript
do {
    //logic
} while (condition)
```

### Break e continue

> Controle do laço. Funciona em todos os laços

- Break - Parar o laço
- Continue - Passar o laço para a próxima entrada

#### Continue

```javascript
const nums = [1,2,3]

for (let num of nums){
    //pulando o console.log do número dois
    if (num === 2)
        continue
    console.log(num)
}
```

#### Break

```javascript
const nums = [1,2,3]

for (let num of nums){
    //Parando o laço quando encontrar o número dois
    if (num === 2)
        break
}
```

### Try Catch finally

```javascript
try{
    // Execuçãoq uando não há erros
} catch (err){
    // Execução caso haja erro
} finally{
    // Sempre executado
}
```

#### Errors 

```javascript
throw new Error('message')
// Example
const number = 'text'
if (typeof number !== 'number')
    throw new Error('Precisa ser número')
```

### Interval e Time outs

#### setInterval

> Executa função em tempos definidos

```javascript
setInterval(function, milliseconds)
//example
setInterval(() => console.log('teste'), 1000)
```

#### setTimeout

> Define um tempo de expiração para um intervalo

```javascript
//Criando uma função para executar em um intervalo
const interval = setInterval(() => console.log('teste'), 1000)

//Definindo o intervalo de 5 segundos para a função
setTimeout(() => {
    clearInterval(interval)
}, 5000)
```

### JSON

#### Passar para json

```javascript
const tasks = [1,2,3,4]
const tasksJson = JSON.stringify(tasks)
tasksJson = [] // '[1,2,3,4]'
```

#### Passar Json para um objeto JavaScript

```javascript
const tasks = [1,2,3,4]
const tasksJson = JSON.stringify(tasks)
tasksJson = [] // '[1,2,3,4]'

const realTasks = JSON.parse(tasksJson)
realTasks // [1,2,3,4]
```

### LocalStorage

> Base de dados do navegdor

#### Salvar no localStorage

```javascript
localstorage.setItem('name', string)
//example
const array = [1,2,3]
const arrayJson = JSON.stringify(array)
localStorage.setItem('array', arrayJson)
```

#### Buscar dados

```javascript
localStorage.getItem('name-item')
```

#### Deletar do localStorage

```javascript
 
```

### Promise

- Pending
- fullfilled - Resolvida
- Rejected

> Execução em pararélo, assincrono 

> Muito utilizado em conexões com banco de dados e chamadas em API. Esse método é utilizado quando não sabemos a hora correta que vamos receber um retorno da requisição feita. Então é retornado uma promessa de resultado, e podemos usar métodos para esperar essa promessa ser cumprida.

```javascript
//Example - Modelo classico
function esperaAi(msg, tempo) {
    return new Promise((resolve, reject) => {
        if (typeof msg !== 'string') {
            reject('Valor incorreto')
            return
        }
        setTimeout(() => {
            resolve(msg)
        }, tempo)
    })
}

esperaAi('Frase 1', 1000)
    .then(resposta => {
        console.log(resposta)
        return esperaAi('Frase 2', 1000)
    })
    .then(resposta => {
        console.log(resposta)
    })
    .catch(e => {
        console.log('Erro: ',e)
    })
```

#### Métodos uteis para promisses

##### Promise.all

> Resolve promessas em sequencia e retorna um array com os resultados

```javascript
function esperaAi(msg, tempo) {
    return new Promise((resolve, reject) => {
        if (typeof msg !== 'string') {
            reject('Valor incorreto')
            return
        }
        setTimeout(() => {
            resolve(msg)
        }, tempo)
    })
}

promisses = [
    esperaAi('Frase 1', 1000),
    esperaAi('Frase 2', 1000),
    esperaAi('Frase 3', 1000),
]

Promise.all(promisses)
    .then(valor => console.log(valor))
    .catch(error => console.log(error))

// ['Frase 1', 'Frase 2', 'Frase 3']
```

##### Promise race

> Retorna o primeiro valor que for resolvido

```javascript
function esperaAi(msg, tempo) {
    return new Promise((resolve, reject) => {
        if (typeof msg !== 'string') {
            reject('Valor incorreto')
            return
        }
        setTimeout(() => {
            resolve(msg)
        }, tempo)
    })
}

promisses = [
    esperaAi('Frase 1', 1000),
    esperaAi('Frase 2', 5000),
    esperaAi('Frase 3', 500),
]

Promise.race(promisses)
    .then(valor => console.log(valor))
    .catch(error => console.log(error))
```

##### Promise resolve e reject

> Retorna uma promise resolvida

```javascript
function emCache(){
    const cache = true

    if (cache){
        return Promise.resolve('Em cache!')
    } else {
        return Promise.reject('Página sem cache')
    }
}

emCache()
    .then(mensagem => console.log(mensagem))
    .catch(mensagem => console.log(mensagem))
```

##### Async await

> Método para facilitar resolver promessas de moto sincrono

```javascript
function esperaAi(msg, tempo) {
    return new Promise((resolve, reject) => {
        if (typeof msg !== 'string') {
            reject('Valor incorreto')
            return
        }
        setTimeout(() => {
            resolve(msg)
        }, tempo)
    })
}

// É necessário utilizar com funções
async function executa(){
    // Para capturar as rejeições é necessário utilizar try catch
    try{
          const frase1 = await esperaAi('Frase 1', 1000)
        console.log(frase1)
        const frase2 = await esperaAi('Frase 2', 2000)
        console.log(frase2)
        const frase3 = await esperaAi('Frase 3', 500)
        console.log(frase3)
    } catch(e) {
        console.log(e)
    }
    
}
executa()
```

### Requisições

> Utilização de requisições AJAX

#### XMLHttpRequest

> Quase não se usa mais, pois o Axios está dominando geral

```javascript
//Exemplo de requisição para o Google (Funciona dentro do site do Google)
const xhr = new XMLHttpRequest()
// xhr.open(method, url, async)
xhr.open('GET', 'https://www.google.com', true)
xhr.send()
xhr.status // 200
```

#### Fetch API

> Maneira simples de fazer requisições

- Retorna um Promise

```javascript
//Exampo - Requisição para o Google (Funciona dentro do site do Google)
fetch('https://www.google.com')
    .then(result => result.text())
    // result.text() - Retorna outra promise
    .then(html => console.log(html))
```

#### Axios

> Ele não é nativo do JS então precisa entrar na Doc dele no Github e baixar por lá

[GitHub](https://github.com/axios/axios)

```javascript
axios('target').then().catch()
```

### Compiladores e transpiladores (Acho que é assim)

#### Babel

[Documentação](https://babeljs.io/docs/en/)

##### Instalação

```js
npm install --save-dev  @babel/cli @babel/preset-env @babel/core
```

##### Conversão de código

```javascript
npx babel main.js -o bundle.js --presets=@babel/env
```

##### Automazar a conversão de código

> Dentro do arquivo package.json, na linha de scripts

```json
"babel": "babel ./main.js -o ./bundle.js --presets=@babel/env -w"
```

### WebPack

#### Instalação

```js
npm i --save-dev @babel/preset-env @babel/cli @babel/core babel-loader webpack webpack-cli 
npm i core-js regenerator-

// loader para css
npm i style-loader css-loader

```

##### configuração

> Dentro do arquivo webpack.config.js

```javascript
//configuração padrão
const path = require('path')
 
module.exports = {
    mode: 'development',
    //Arquivo de entrada
    entry: './src/main.js',
    //Arquivo de saida
    output: {
        path: path.resolve(__dirname, 'public', 'assets','js'),
        filename: 'bundle.js'
    },
    module: {
        rules: [{
            exclude: /node_modules/,
            test: /\.js$/,
            use: {
                loader: 'babel-loader',
                options: {
                    presets: ['@babel/env']
                }
            }
        },
    {
        //loader do CSS
        test: /\.css$/,
        use: ['style-loader','css-loader']
    }]
    },
    devtool: 'source-map'
}
```

### Import & Export

> Cara, existem várias formas. Irei listar as mais usada abaixo, mas é bom ver a doc :3

#### Export

```javascript
const name = 'Albert'
const surname = 'Einstein'
export name
export default name
export name as genius
export const name = 'Albert'
export {name as genius, surname as default}
```

#### import

```javascript
import { name } from './path/file_name'
// If have export default
import anyName from './path/file_name'

import { name, surname as surnameOfGenius} from './path/file_name'
import defaultModule { surnameOfGenius } from './path/file_name'
```




