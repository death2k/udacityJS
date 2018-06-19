# udacityJS

"Fizzbuzz" é uma famosa pergunta de entrevista utilizada em entrevistas de programação. Funciona mais ou menos assim:

Faça um loop dos números 1 a 100
Se o número for divisível por 3, exiba "Fizz"
Se o número for divisível por 5, exiba "Buzz"
Se o número for divisível por ambos 3 e 5, exiba "FizzBuzz"
Se o número não for divisível por 3 nem 5, exiba o número
DICA: um número x é divisível por um número y se o resultado de x / y tem um resto 0. Por exemplo, 10 é divisível por 2, pois 10 / 2 = 5, sem resto. Você pode checar se um número é divisível por outro verificando se x % y === 0.

Vamos deixar que você programe sua própria versão do FizzBuzz, chamada "JuliaJames" (sim, construtivo, certo?). Tenha em mente que, em uma entrevista, você deveria escrver um código eficiente com pouca duplicação. Não queremos que se preocupe com isso nesta pergunta. Apenas foque na prática do uso de loops.

Direções:
Escreva um loop while que:

Faça um loop dos números 1 a 20
Se o número for divisível por 3, exiba "Julia"
Se o número for divisível por 5, exiba "James"
Se o número for divisível por 3 e 5, exiba "JuliaJames"
Se o número não for divisível por 3 nem 5, exiba o número

my code .. is incorrect whyy???

/*
 * Programming Quiz: JuliaJames (4-1)
 */
var x = 1;

while(x <= 20){
if(x % 3 === 0 && x % 5 === 0 ){
        console.log("JuliaJames");
    }if(x % 3 === 0){
        console.log("Julia");
    }if (x % 5 === 0){
        console.log("James");
    }if(x % 3 !== 0 && x % 5 !== 0 ){
        console.log(x);
    }
    x = x + 1;
}
