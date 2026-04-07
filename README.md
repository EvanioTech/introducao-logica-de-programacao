# Introducao a Logica de Programacao

Este repositorio apresenta conceitos iniciais de logica de programacao usando JavaScript.
O arquivo principal, `index.js`, demonstra como declarar variaveis, constantes, tipos basicos e imprimir mensagens no console.

## Objetivo

Praticar fundamentos de programacao para iniciantes, com foco em:

- Saida no console com `console.log`
- Diferenca entre `let` e `const`
- Reatribuicao de variaveis
- Convencao de nomes em `camelCase`
- Tipos basicos (`Number`, `String`, `Boolean`)


## Como Executar

1. Precisa ter o Node.js instalado.
2. No terminal, acesse a pasta do projeto.
3. Execute o comando:

```bash
node index.js
```

## O que Voce Vera na Saida

Ao executar, o terminal exibira mensagens como:

- Introducao a logica de programacao
- Valor de variaveis antes e depois de alteracoes
- Exemplo de variavel em `camelCase`

## Conceitos Demonstrados no Codigo

### 1. Impressao no console

`console.log(...)` envia texto e valores para o terminal.

### 2. Variaveis com `let`

Variaveis declaradas com `let` podem mudar de valor durante a execucao.

Exemplo:

```js
let cliente = "Matias";
cliente = "Maria";
```

### 3. Constantes com `const`

Constantes nao podem ser reatribuidas apos a declaracao.

Exemplo:

```js
const sexo = "Masculino";
```

### 4. Padrao de nomenclatura `camelCase`

Forma recomendada para nomes compostos em JavaScript:

- Primeira palavra com inicial minuscula
- Demais palavras com inicial maiuscula

Exemplo: `nomeDoCliente`

### 5. Tipos de dados basicos

- `Number`: valores numericos (ex.: idade)
- `String`: textos (ex.: nome)
- `Boolean`: verdadeiro ou falso (ex.: funcionario do mes)


