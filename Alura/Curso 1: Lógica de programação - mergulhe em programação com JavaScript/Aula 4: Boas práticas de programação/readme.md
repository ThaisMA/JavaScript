# Resolução dos desafios - Aula 4
## Desafios finais

---
1) Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.
---

````js
let mensagem = "Boas vindas";
console.log(mensagem);
````

---
2) Crie uma variável chamada **nome** e atribua a ela o seu nome. 
Em seguida, utilize o console.log para exibir a mensagem ***Olá, [seu nome]!*** no console do navegador.
---

````js
let nome = "Thais";
console.log(`Ola ${nome}`);
````

---
3) Crie uma variável chamada **nome** e atribua a ela o seu nome. 
Em seguida, utilize o alert para exibir a mensagem ***Olá, [seu nome]!*** .
---

````js
let nome2 = "Thais";
alert(`Ola ${nome2}`);
````

---
4) Utilize o prompt e faça a seguinte pergunta: ***Qual a linguagem de programação que você mais gosta?***. 
Em seguida, armazene a resposta em uma variável e mostre no console do navegador.
---

````js
let linguagem = prompt("Digite a linguagem favorita: ");
console.log(linguagem);
````

---
5) Crie uma variável chamada **valor1** e outra chamada **valor2**, atribuindo a elas valores numéricos de sua escolha. 
Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada **resultado**. 
Utilize o console.log para mostrar a mensagem **A soma de *[valor1]* e *[valor2]* é igual a *[resultado]*.** no console.
---

````js
let valor1 = parseInt(prompt("Digite um valor: "));
let valor2 = parseInt(prompt("Digite outro valor: "));

resultado = valor1 + valor2;
console.log(`A soma de ${valor1} e ${valor2} eh igual a ${resultado}.`);
````

---
6) Crie uma variável chamada **valor1** e outra chamada **valor2**, atribuindo a elas valores numéricos de sua escolha. 
Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada **resultado**. 
Utilize o console.log para mostrar a mensagem **A diferença entre *[valor1]* e *[valor2]* é igual a *[resultado]*.** no console.
---

````js
let valor3 = prompt("Digite um valor: ");
let valor4 = prompt("Digite outro valor: ");

subtracao = valor1 - valor2;
console.log(`A subtracao de ${valor3} e ${valor4} eh igual a ${subtracao}.`);
````

---
7) Peça ao usuário para inserir sua idade com prompt. 
Com base na idade inserida, utilize um **if** para verificar se a pessoa é maior ou menor de idade, 
exibindo uma mensagem apropriada no console.
---

````js
let idade = prompt("Digite uma idade: ");

if (idade >= 18){
    console.log("maior de idade");
}
else{
    console.log("menor de idade");
}
````

---
8) Crie uma variável **numero** e peça um valor com prompt verifique se é positivo, 
negativo ou zero. Use **if-else** para imprimir a respectiva mensagem.
---

````js
let numero = prompt("Digite um valor: ");

if (numero > 0){
    console.log("Numero digitado eh positivo");
}
else if (numero < 0){
    console.log("numero digitado eh negativo");
}
else{
    console.log("numero digitado eh zero");
}
````

---
9) Use um loop **while** para imprimir os números de 1 a 10 no console.
---

````js
let digito = 1;

while (digito <= 10){
    console.log(digito);
    digito++;
}
````

---
10) Crie uma variável **nota** e atribua um valor numérico a ela. 
Use if-else para determinar se a nota é maior ou igual a 7 e exiba **Aprovado** ou **Reprovado** no console.
---

````js
let nota = prompt("Digite uma nota: ");
if (nota >= 7){
    console.log("aprovado");
}
else{
    console.log("reprovado");
}
````

---
11) Use o ***Math.random*** para gerar qualquer número aleatório e exiba esse número no console.
---

````js
let randomico = parseInt(Math.random() * 10);
console.log(`o numero escolhido foi: ${randomico}`);
````

---
12) Use o ***Math.random*** para gerar um número inteiro entre 1 e 10 e exiba esse número no console.
---

````js
let randomico1 = parseInt(Math.random() * 10 +1);
console.log(`o numero escolhido foi: ${randomico1}`);
````

---
13) Use o ***Math.random*** para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.
---

````js
let num_cem = parseInt(Math.random() * 1000);
console.log(`o numero escolhido foi: ${num_cem}`);
````




