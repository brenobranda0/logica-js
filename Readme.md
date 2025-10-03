# Resolução dos desafios do curso de lógica de programação

[](https://github.com/jairobr1986)
#### Desafios - Respostas

```js
alert("Boas vindas ao nosso site!");
let nome = "Lua";
let idade = 25;
let numeroDeVendas = 50;
let saldoDisponivel = 1000;
let mensagemDeErro = "Erro! Preencha todos os campos"
```



10) Peça ao usuário para digitar sua idade usando um prompt e armazene-a na variável `idade`. Agora, a idade seja maior ou igual que 18, exiba um alerta com a mensagem "Pode tirar a habilitação!".

```js
nome = prompt("Qual o seu nome?");
idade = prompt("Qual a sua idade?");

if (idade >= 18) {
    alert(`Olá ${nome}, você tem ${idade} anos e Pode tirar a habilitação! `)
} else {`Olá ${nome}, você deve esperar até fazer 18 anos ou mais.`}
```
