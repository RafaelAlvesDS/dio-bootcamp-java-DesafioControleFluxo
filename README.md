# Desafio Controle de Fluxo

Exercício do bootcamp de Java da DIO sobre controle de fluxo e exceções.

O programa pede dois números inteiros e imprime uma linha para cada número entre eles, contando quantos são. Se o segundo não for maior que o primeiro, lança a exceção `ParametrosInvalidosException` com a mensagem "O segundo parâmetro deve ser maior que o primeiro."

```
Digite o primeiro parâmetro: 12
Digite o segundo parâmetro: 15
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
```

Note que a contagem sempre começa em 1 e vai até a diferença entre os dois números, não até o segundo número.

## Rodar

Precisa do JDK. Dentro de `DesafioControleFluxo`:

```
javac src/*.java
java -cp src Contador
```
