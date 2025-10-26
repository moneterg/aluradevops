# Desafios 2 - Soluções em JavaScript

1️⃣ Pergunte ao usuário qual é o dia da semana.
Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!".
Caso contrário, mostre "Boa semana!".

```javacript
let weekDay = prompt("Responda: qual é o dia da semana?");

if (weekDay == "Sábado") {
    alert("Bom fim de semana!");
} else if (weekDay == "Domingo") {
    alert("Bom fim de semana!");
} else {
    alert("Boa semana!");
}
```

2️⃣ Verifique se um número digitado pelo usuário é positivo ou negativo.
Mostre um alerta informando.

```javacript
let number = prompt("Digite um número para verificação");

if (number >= 0) {
    alert("O número digitado \"" + number + "\" é positivo!");
} else {
    alert("O número digitado \"" + number + "\" é negativo!");
}
```


3️⃣ Crie um sistema de pontuação para um jogo.
Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!".
Caso contrário, mostre "Tente novamente para ganhar.".

```javacript
let pontos = prompt("Digite sua quantidade de pontos");

if (pontos >= 100) {
    alert("Parabéns, você venceu, pois obteve pontuação >= a 100 pontos");
} else {
    alert("Tente novamente para ganhar.");
}
```

4️⃣ Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.

```javacript
let saldoConta = 5000;
alert(`O saldo da sua conta é ${saldoConta}`);
```

5️⃣ Peça ao usuário para inserir seu nome usando prompt.
Em seguida, mostre um alerta de boas-vindas usando esse nome.

```javacript
let nome = prompt("Digite seu nome");
alert(`Boas-vindas ${nome}!`);
```
