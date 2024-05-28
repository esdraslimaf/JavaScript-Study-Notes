# JavaScript Study Notes

## Tipos, Variáveis e Funções

### Tipos de Dados

JavaScript possui diversos tipos de dados, incluindo:

- **Número (`number`)**: Representa valores numéricos, como inteiros e decimais. Por exemplo: `42`, `3.14`.
- **String (`string`)**: Sequências de caracteres. Por exemplo: `'Hello, world!'`, `"JavaScript"`.
- **Boolean (`boolean`)**: Representa um valor verdadeiro (`true`) ou falso (`false`).
- **Null e Undefined**: `null` representa a ausência intencional de qualquer valor ou objeto, enquanto `undefined` é atribuído automaticamente a variáveis que não foram inicializadas.
- **Object**: Uma coleção de pares de chave-valor. Por exemplo: `{ nome: 'João', idade: 30 }`.
- **Array**: Uma lista ordenada de valores. Por exemplo: `[1, 2, 3, 4, 5]`.

### Declaração de Variáveis

Em JavaScript, podemos declarar variáveis usando `var`, `let` ou `const`.

- **var**: Declara uma variável globalmente ou localmente para toda a função, independentemente do escopo de bloco.
- **let**: Declara uma variável local no escopo do bloco em que é definida.
- **const**: Declara uma variável cujo valor é fixo (constante).

Exemplo:

```javascript
var numero = 42; // Declaração de variável usando var
let nome = "Maria"; // Declaração de variável usando let
const PI = 3.14; // Declaração de variável usando const


### Funções
Funções são blocos de código reutilizáveis que podem ser chamados para executar uma determinada tarefa. Em JavaScript, existem diferentes formas de declarar funções:

**Declaração de função**: Define uma função usando a palavra-chave function.
**Expressões de função**: Define uma função como parte de uma expressão.
**Arrow functions**: Uma forma mais curta e concisa de escrever funções introduzida no ES6.

// Declaração de função
function saudacao(nome) {
  return "Olá, " + nome + "!";
}

// Expressão de função
const soma = function(a, b) {
  return a + b;
};

// Arrow function
const quadrado = (x) => x * x;
