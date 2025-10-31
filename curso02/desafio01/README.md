# Exercícios Resolvidos – JavaScript
#### 2️⃣ Altere o conteúdo da tag h1 com document.querySelector e atribua o seguinte texto: `Hora do Desafio`.

```javascript
let titulo = document.querySelector("h1");
titulo.innerHTML = "Hora do Desafio";
```

#### 3️⃣ Crie uma função que exiba no console a mensagem `O botão foi clicado` sempre que o botão Console for pressionado.

- Primeiro no `index.html`, adicionar dentro do bloco `container__botoes` a linha abaixo:

```html
<button onclick="mensagemNoConsole()" class="container__botao">Console</button>
```
- Após, no `app.js`, adicionar a função:

```javascript
function verificarChute() {
    console.log("O botão foi clicado!");
}
```

#### 4️⃣ Crie uma função que exiba um alerta com a mensagem: `Eu amo JS`, sempre que o botão `Alerta` for pressionado.

- Primeiro no `index.html`, adicionar dentro do bloco `container__botoes` a linha abaixo:

```html
<button onclick="mensagemDeAlerta()" class="container__botao">Alerta</button>
```
- Após, no `app.js`, adicionar a função:

```javascript
function mensagemDeAlerta() {
    alert("Eu amo JS");
}
```

#### 5️⃣ Crie uma função que é executada quando o botão `prompt` é clicado, perguntando o nome de uma cidade do Brasil. Em seguida, exiba um alerta com a mensagem concatenando a resposta com o texto: `Estive em {cidade} e lembrei de você`.

- Primeiro no `index.html`, adicionar dentro do bloco `container__botoes` a linha abaixo:

```html
<button onclick="mensagemDePrompt()" class="container__botao">Prompt</button>
```
- Após, no `app.js`, adicionar a função:

```javascript
function mensagemDePrompt() {
    let cidade = prompt ("Digite o nome de uma cidade do Brasil");
    alert (`Estive em ${cidade} e lembrei de você`);
}
```
#### 6️⃣ Ao clicar no botão `soma`, peça 2 números inteiros e exiba o resultado da soma em um alerta.

- Primeiro no `index.html`, adicionar dentro do bloco `container__botoes` a linha abaixo:

```html
<button onclick="somarDoisNumeros()" class="container__botao">Soma</button>
```
- Após, no `app.js`, adicionar a função:

```javascript
function somarDoisNumeros() {
    let numero1 = parseInt(prompt ("Digite um número"));
    let numero2 = parseInt(prompt ("Digite outro número"));
    alert ("A soma de ambos os números é " + (numero1 + numero2) + "!");
}
```
