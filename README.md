# Desafio Controle de Fluxo - DIO

Projeto do bootcamp Java da Digital Innovation One (DIO) que demonstra controle de fluxo, tratamento de exceções e estruturas de repetição.

## Descrição

Aplicação console que recebe dois números inteiros e realiza uma contagem entre eles. Valida se o segundo número é maior que o primeiro, caso contrário lança uma exceção customizada.

## Como executar

1. Compile: `javac src/*.java`
2. Execute: `java -cp src Contador`

## Exemplo de uso

```
Digite o primeiro parâmetro: 12
Digite o segundo parâmetro: 30
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18
```

Se o segundo parâmetro for menor que o primeiro:
```
O segundo parâmetro deve ser maior que o primeiro.
```

## Estrutura

- `Contador.java` - Classe principal
- `ParametrosInvalidosException.java` - Exceção customizada
