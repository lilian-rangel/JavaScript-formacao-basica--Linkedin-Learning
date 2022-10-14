# JavaScript-formacao-basica--Linkedin-Learning
Temáticas aprendidas: <br>
° Elementos básicos do JS; <br>
° Funções e objetos;<br>
° Manipulando elementos no DOM e eventos;<br>
° Loops<br>
° Troubleshooting, validação e minificação<br>

--------------------------------------------------------------------------

Operadores lógicos
And/or
if (a == b && c == d){} (as duas condições tem que ser verdadeira)
if (a == b || c == d){} (uma das duas condições ou ambas são verdadeiras)
Xor 
if ((a == b || c == d) && ((a == b != (c == d) ) {}  (uma das duas verdadeiras mas não ambas)

Operador Ternário (condição ? true : false)
a == b ? console.log("Match") : console.log("No match");


Métodos: 
Reverter o array:
pens.reverse();

Remover o primeiro valor do array:
pens.shift();

Adicionar lista de valores separados por vírgula no início do array:
pens.unshift("purple", "black");

Remove o último valor do array:
pens.pop();

Adiciona uma lista de valores separados por vírgula no final do array:
pens.push("pink", "prussian blue");

Encontra uma posição específica (pos) e remove (n) números de itens do array. Argumento: pens.splice(pos,n):
pens.splice(3, 2) // Começa no terceiro item e remove 2 itens.
console.log("After: ", pens);

Cria uma cópia do array. Tipicamente designa a uma nova variável:
var newPens = pens.slice();
console.log("New pens: ", newPens);

Retorna o primeiro elemento que combina com o parâmetro de busca depois da posição index especificada.
Argumento: pens.indexOf(search, index):
var result = pens.indexOf("orange", 1);
console.log("The search result index is: ", result);

Retorna os itens no array como uma string separaa por vírgulas. Você pode usar o argumento separador para mudar a vírgula por alguma outra coisa como hífen.  Argumento: pens.join('separator'):
var arrayString = pens.join();
console.log("String from array: ", arrayString);

// MDN documentation for Array: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
