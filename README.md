# javascript-ativiadade-loops

exercícios de JavaScript 1

Introdução

Um kata é um exercício individual de programação destinado à prática e aprimoramento de habilidades. Neste repositório, você irá praticar o uso de loops, condicionais, e expressões em JavaScript por meio de uma série de exercícios.

Seu objetivo é completar as funções em katas1.js, utilizando estruturas de repetição como for, while e do while. Cada kata concluído vale 1 ponto.

Tarefas

Complete as seguintes funções:

oneThroughTwenty: Retornar os números de 1 a 20.

Resultado esperado: [1, 2, 3, ..., 19, 20]

evensToTwenty: Retornar os números pares de 1 a 20.

Resultado esperado: [2, 4, 6, ..., 18, 20]

oddsToTwenty: Retornar os números ímpares de 1 a 20.

Resultado esperado: [1, 3, 5, ..., 17, 19]

multiplesOfFive: Retornar os múltiplos de 5 até 100.

Resultado esperado: [5, 10, 15, ..., 95, 100]

squareNumbers: Retornar todos os números até 100 que forem quadrados perfeitos.

Resultado esperado: [1, 4, 9, ..., 81, 100]

countingBackwards: Retornar os números de 20 até 1, contando de trás para frente.

Resultado esperado: [20, 19, 18, ..., 2, 1]

evenNumbersBackwards: Retornar os números pares de 20 até 1.

Resultado esperado: [20, 18, 16, ..., 4, 2]

oddNumbersBackwards: Retornar os números ímpares de 20 até 1.

Resultado esperado: [19, 17, 15, ..., 3, 1]

multiplesOfFiveBackwards: Retornar os múltiplos de 5 de 100 até 5, contando de trás para frente.

Resultado esperado: [100, 95, 90, ..., 10, 5]

squareNumbersBackwards: Retornar os quadrados perfeitos de 100 até 1, contando de trás para frente.

Resultado esperado: [100, 81, 64, ..., 4, 1]

Dicas

Para relembrar o que é um número primo ou um quadrado perfeito, confira os seguintes recursos:

Números Primos

Quadrados Perfeitos

Passo a Passo

1. Preparando o Repositório

O arquivo index.html já está pronto para ser utilizado. Agora, você deve abrir o arquivo katas1.js e começar a preencher o código de acordo com as instruções fornecidas.

2. Alterando o Código

Edite as funções para que elas retornem o que é solicitado. Aqui está um exemplo:

function oneThroughFive() {
    let meuRetorno = [];
    for (let counter = 1; counter <= 5; counter++) {
        meuRetorno.push(counter);
    }
    return meuRetorno;
}

console.log(oneThroughFive());

A função acima já está resolvida e funciona corretamente. Use-a como exemplo para criar as outras funções.

Regras Importantes

Utilize apenas estruturas de repetição: while, do while, for.

Não utilize métodos de iteração de array, como forEach, map, filter, reduce, sort.

Não utilize bibliotecas matemáticas como Math.min, Math.max.

Executando os Testes

Para testar se suas funções estão funcionando corretamente, basta chamá-las e verificar o retorno no console.

Exemplo:

console.log(evensToTwenty()); // Deve retornar [2, 4, 6, ..., 20]

Contribuições

Se você encontrar um problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença

Este repositório está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
