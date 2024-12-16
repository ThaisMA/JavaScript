# Resolução dos desafios - Aula 2

---
1) Criar uma função que exibe "Olá, mundo!" no console.
---

````js
function exercicioUm(text) {
   return console.log(text)
}
exercicioUm("Exercicio 1: Ola, mundo!");
````

---
2) Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.
---

````js
function exercicioDois(nome) {
    return console.log(`Exercicio 2: Ola, ${nome}!`)
}
exercicioDois("Thais")
````

---
3) Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.
---

````js
function exercicioTres(num) {
    return console.log(`Exercicio 3: O dobro do ${num} eh: ${num*2}!`);
}
let numeroExercicio = parseInt(prompt("Digite um numero:"));
exercicioTres(numeroExercicio);

/*
Outra forma
*/
function exercicioTres(numero) {
  return numero * 2;
}
let resultadoDobro = exercicioTres(5);
console.log(resultadoDobro);

````

---
4) Criar uma função que recebe três números como parâmetros e retorna a média deles.
---

````js
function exercicioQuatro(valor1, valor2, valor3) {
    media = parseInt((valor1+valor2+valor3)/3)
    return console.log(`Exercicio 4: valor da media, ${media}!`)
}
exercicioQuatro(3,4,5)
````

---
5) Criar uma função que recebe dois números como parâmetros e retorna o maior deles.
---

````js
function exercicioCinco(valor4,valor5) {
    if(valor4 > valor5){
        return console.log("Exercicio 5: O primeiro numero eh maior");
    }else if(valor4<valor5){
        return console.log("Exercicio 5: O segundo numero eh maior");
    }else{
        return console.log("Os numeros sao iguais");
    }
}
exercicioCinco(3,1);

/*
Outra forma
*/
function exercicioCinco(a, b) {
  return a > b ? a : b;
}
let maiorNumero = exercicioCinco(15, 9);
console.log(maiorNumero);
````

---
6) Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo
---

````js
function exercicioSeis(valor6) {
    return console.log(`Exercicio 6: valor da multiplicacao, ${valor6**2}!`)
}
exercicioSeis(3)
````
