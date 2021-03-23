/* # Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js */

// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function fun(arg1, arg2){
    return arg1 + arg2;
};

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var total = fun(2,4) + 5;

// Qual o valor atualizado dessa variável?
total
console.log("🚀 ~ file: README.md ~ line 17 ~ total", total)

// Declare uma nova variável, sem valor.
var novaVar;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/

function adicionarVar(){
    novaVar = "VALOR";
    return " O valor da variavel agora e VALOR";
}

// Invoque a função criada acima.
adicionarVar();

// Qual o retorno da função? (Use comentários de bloco).
console.log(adicionarVar());

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function novaFuncao(arg1, arg2, arg3){
    if(arg1 === undefined && arg2 === undefined && arg3 == undefined){
        return 'Preencha todos os valores corretamente!';
    }
    else{
        return arg1 * arg2 * arg3 + 2;
    }
}

// Invoque a função criada acima, passando só dois números como argumento.
var result = novaFuncao(1,2);


// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
console.log("🚀 ~ file: README.md ~ line 57 ~ result", result);

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
result = novaFuncao(2,2,2);


// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
console.log("🚀 ~ file: README.md ~ line 64 ~ result", result);

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/

function novaFuncao(arg1, arg2, arg3){
    if(arg1)
}


// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
