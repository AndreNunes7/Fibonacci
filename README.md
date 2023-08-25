# Sequência de Fibonacci

Este é um programa em C# que gera e exibe a sequência de Fibonacci até um número especificado pelo usuário.

## Funcionamento

A sequência de Fibonacci é uma série numérica onde cada número é a soma dos dois números anteriores (começando com 0 e 1). O programa começa pedindo ao usuário para inserir um número. Em seguida, ele gera e exibe a sequência de Fibonacci até o número inserido.

O programa utiliza um laço `while` para calcular e exibir os números da sequência. Ele inicializa três variáveis (`n1`, `n2` e `n3`) para começar a sequência e um contador `i` para acompanhar o progresso. A cada iteração do laço, ele calcula o próximo número `n3` somando os valores de `n1` e `n2`. Em seguida, ele atualiza as variáveis `n1` e `n2` e incrementa o contador `i`.

## Como usar

1. Certifique-se de ter o ambiente de desenvolvimento C# configurado em sua máquina.

2. Copie o código fornecido e cole-o em um arquivo `.cs`.

3. Compile e execute o programa.

4. O programa pedirá para você inserir um número. Insira um número inteiro positivo e pressione Enter.

5. O programa exibirá a sequência de Fibonacci até o número inserido.

## Observações

- Este código é um exemplo simples de como gerar e exibir a sequência de Fibonacci em C#. Ele não lida com entradas inválidas ou valores negativos, portanto, certifique-se de inserir um número inteiro positivo.

- Para fins educacionais, o código mantém as variáveis de estado na mesma função (`Main`). Em situações reais, seria uma prática melhor encapsular a lógica da sequência de Fibonacci em uma função separada para melhor modularidade e reutilização.

- Lembre-se de que a sequência de Fibonacci pode crescer rapidamente, portanto, o programa pode ficar lento para números muito grandes, dependendo da eficiência do algoritmo usado.
