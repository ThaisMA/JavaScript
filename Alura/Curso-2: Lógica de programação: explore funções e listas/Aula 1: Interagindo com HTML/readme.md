---
1) Faça o download de outro projeto [clicando neste link](https://github.com/alura-cursos/js-curso-2/tree/desafio_1) e abra no Visual Studio Code.
---
😎👍

---
2) Altere o conteúdo da tag **h1** com ***document.querySelector*** e atribua o seguinte texto: ***Hora do Desafio***.
---

````js
let titulo = document.querySelector('h1');
insere um texto na tag do html selecionada
titulo.innerHTML = 'Hora do Desafio';
````

---
3) Crie uma função que exiba no console a mensagem ***O botão foi clicado*** sempre que o botão Console for pressionado.
---

````js
function verificarChute(){
// Capturar o valor inserido pelo usuário no elemento de entrada (input) do HTML, o retorno é um valor booleano.
    let chute = document.querySelector('input').value;
    console.log('O botao foi clicado');
}
````

> [!TIP]
> A variável com o código ***document.querySelector('input').value*** captura o valor inserido em um elemento HTML ***input***.
> 
> **O que faz cada parte:**
>
> 1) **document.querySelector('input')**:
>
> Seleciona o primeiro elemento ***input*** encontrado no DOM (Document Object Model).
>
> 2) **.value**:
>
> Obtém o valor atualmente presente no campo de entrada do **input**.
>
> **Exemplo de uso:**
>
> Se o HTML tiver o seguinte campo de entrada:
>
> ````js
> <input type="text" value="Olá Mundo">
> ````
> E o código for:
> ````js
> let valor = document.querySelector('input').value;
> console.log(valor);
> ````
> O console exibirá:
> ````js
> Olá Mundo
> ````
> Resumo:
> ***document.querySelector('input').value*** permite acessar ou manipular o texto que o usuário digitou
> ou o valor inicial definido no elemento **input**.

---
4) Crie uma função que exiba um alerta com a mensagem: ***Eu amo JS***, sempre que o botão **Alerta** for pressionado.
---

````js
function verificarChute(){
    let chute = document.querySelector('input').value;
    alert('Eu amo JS')
}
````

---
5) Crie uma função que é executada quando o botão prompt é clicado, perguntando o nome de uma cidade do Brasil.
Em seguida, exiba um alerta com a mensagem concatenando a resposta com o texto: Estive em {cidade} e lembrei de você.
---

````js
let teste = alert('Aperte o botao!')
function botao(){
    cidade = prompt('Digite o nome da cidade: ')
    alert(`Estive em ${cidade} e lembrei de voce, bom jogo`)
}
````

---
6) Ao clicar no botão soma, peça 2 números inteiros e exiba o resultado da soma em um alerta.
---

````js
function soma(){
    let numero1 = parseInt(prompt('Digite o primeiro numero: '))
    let numero2 = parseInt(prompt('Digite o segundo numero: '))
    let soma = numero1+numero2
    alert(`A soma do numero eh ${soma}`)
}
````

