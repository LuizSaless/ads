# Conversor Decimal para Binário com Express.js

Projeto simples desenvolvido com **Node.js** e **Express.js** para converter um número decimal em seu equivalente binário por meio de uma API REST.

## Tecnologias utilizadas

* Node.js
* Express.js
* JavaScript

## Como executar o projeto

### 1. Clone o repositório

```bash
git clone <url-do-repositorio>
cd nome-do-repositorio
```

### 2. Instale as dependências

```bash
npm install
```

### 3. Inicie a aplicação

```bash
node index.js
```

O servidor será iniciado na porta **3000**.

## Endpoint da API

### Converter decimal para binário

**GET**

```text
http://localhost:3000/to-binary/:decimal
```

**Exemplo**

```text
http://localhost:3000/to-binary/10
```

**Resposta**

```json
{
  "decimal": 10,
  "binary": "1010"
}
```

### Tratamento de erro

Se o valor informado não for um número válido, a API retorna:

```json
{
  "error": "Invalid decimal number"
}
```

## Estrutura do projeto

```text
.
├── index.js
├── package.json
└── README.md
```

## Objetivo do projeto

Este exercício tem como objetivo praticar:

* Criação de uma API com Express.js.
* Criação de rotas com parâmetros.
* Conversão de números utilizando JavaScript.
* Versionamento do projeto com Git e GitHub.
