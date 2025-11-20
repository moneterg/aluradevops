# Desafios - Soluções em JavaScript

1️⃣ Criar uma função que exibe "Olá, mundo!" no console.
```javascript
function mensagemNoConsole() {
    console.log("Olá, mundo!");
}
mensagemNoConsole ();
```

2️⃣ Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.
```javascript
let nome = prompt ("Digite seu nome");
nomeNoConsole (nome);
function nomeNoConsole(nome) {
    console.log(`Olá, ${nome}!`);
}
```

3️⃣ Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.
```javascript
let numero = prompt ("Digite um número");
alert ("O dobro de " + numero + " é " + dobrarNumero (numero));
function dobrarNumero (numero) {
    return numero * 2;
}
```

4️⃣ Criar uma função que recebe três números como parâmetros e retorna a média deles.
```javascript
let num1 = parseInt(prompt ("Digite o número 1"));
let num2 = parseInt(prompt ("Digite o número 2"));
let num3 = parseInt(prompt ("Digite o número 3"));
alert (`A média dos números digitados ${num1}, ${num2} e ${num3} é de ` + mediaTresNumeros (num1, num2, num3));
function mediaTresNumeros (num1, num2, num3) {
    return (num1 + num2 + num3)/3;
}
```

5️⃣ Criar uma função que recebe dois números como parâmetros e retorna o maior deles.
```javascript
let num1 = parseInt(prompt ("Digite o número 1"));
let num2 = parseInt(prompt ("Digite o número 2"));
alert (`De ambos números digitados ${num1} e ${num2}, o maior é ` + maiorNumero (num1, num2));
function maiorNumero (num1, num2) {
    if (num1 > num2) {
        return num1;
    } else return num2;
}
```

6️⃣ Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo
```javascript
let numero = parseInt(prompt ("Digite um número"));
alert (`O resultado da multiplicação de ${numero} por ele mesmo é ` + multiplicaPorEleMesmo (numero));
function multiplicaPorEleMesmo (numero) {
    return numero * numero;
}
```
