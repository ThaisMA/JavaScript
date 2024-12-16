# Resolução dos desafios

1) Pergunte ao usuário qual é o dia da semana. 
Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". 
Caso contrário, mostre "Boa semana!".
---

````js
let diaSemana = prompt("Digite o dia da semana: ");
console.log(diaSemana);
let chute = "sabado";
if (diaSemana == "sabado" || diaSemana == 'domingo') {
    console.log(diaSemana == chute);
    alert("Bom final de semana");
}else{
   alert("Boa semana");
}
````

2) Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.
--- 

````js
let numero = prompt("Digite um numero: ")
if (numero >=0){
    alert("numero positivo")
}else{
    alert("numero negativo")
}
````


3) Crie um sistema de pontuação para um jogo. 
Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". 
Caso contrário, mostre "Tente novamente para ganhar.".


````js
let numero = prompt("Digite um numero: ")
console.log(numero)
if (numero >=100){
    alert(`Parabéns, você venceu e digitou o numero: ${numero} !`)
}else{
    alert("Tente novamente para ganhar.")
}
````


4) Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.


````js
let saldo = prompt("Digite o seu saldo: ")
alert(`Seu saldo eh: R$${saldo}`)
````


5) Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.


````js
 let nome = prompt("Digite seu nome: ")
 alert(`Ola ${nome}!!`)
````
