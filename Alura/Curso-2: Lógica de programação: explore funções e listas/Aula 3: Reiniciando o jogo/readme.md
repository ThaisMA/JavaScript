---
1) Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, 
a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.
---

````js
function IMC(altura, peso) {
    return numeroIMC = parseFloat(peso/(altura**2)*10000)
}
console.log(IMC(170, 69));
````

---
2) Crie uma função que calcule o valor do fatorial de um número passado como parâmetro.
---

````js
function fatorialNumero(numero) {
    if ( numero == 0 || numero == 1){
        return 1;
    }
   let fatorial = 1;
   for (let i = 2; i<=numero; i++){
    fatorial *=i;
   }
   return fatorial;
}
console.log(fatorialNumero(5));
````

---
3) Crie uma função que converte um valor em dólar, passado como parâmetro, 
e retorna o valor equivalente em reais. Para isso, considere a cotação do dólar igual a R$4,80.
---

````js
function converter(valor) {
    return converteToReal = parseFloat(valor * 4.80)
}
let dolar = 50
console.log(converter(dolar))
````

---
4) Crie uma função que mostre na tela a área e o perímetro de uma sala retangular, 
utilizando altura e largura que serão dadas como parâmetro.
---

````js
function quadrado(altura,largura) {
    let areaTotal =  altura ** 2
    let perimetroTotal = 2 * parseFloat(altura+largura)
    console.log(`Area do quadrado: ${areaTotal} metros quadrados`);
    console.log(`Perimetro do quadrado: ${perimetroTotal} metros`);
}
let altura = 3
let largura = 5
console.log(quadrado(altura,largura))
````

---
5) Crie uma função que mostre na tela a área e o perímetro de uma sala circular, 
utilizando seu raio que será fornecido como parâmetro. Considere Pi = 3,14.
---

````js
function circulo(raio) {
    let area = Math.PI * raio**2 //Math.PI representa o valor de PI
    let diametro = Math.PI * 2 * raio
    console.log(`Area do circulo: ${area} metros quadrados`);
    console.log(`Perimetro do circulo: ${diametro} metros`);
}
let raio = 4
console.log(circulo(raio))
````

---
6) Crie uma função que mostre na tela a tabuada de um número dado como parâmetro.
---

````js
function tabuada(numero2) {
    let cont = 0
    let total = 0
    console.log(`Tabuada do ${numero2}: `)
    while (cont <= 10){
        total = numero2 * cont
        console.log(`${numero2} X ${cont} = ${total}`)
        cont++;
    }
}
tabuada(3)
````
