# Módulo 04 - Projeto: TDD na Prática (Kata FizzBuzz)

## Descrição do Projeto
Você vai implementar o clássico exercício "FizzBuzz" utilizando estritamente o ciclo TDD (Red-Green-Refactor).

## Cenário
Você precisa criar uma função que receba um número inteiro e:
1. Retorne "Fizz" se for divisível por 3.
2. Retorne "Buzz" se for divisível por 5.
3. Retorne "FizzBuzz" se for divisível por 3 e 5.
4. Retorne o próprio número (como string) caso contrário.

## Instruções (Passo a Passo Rígido)

**Não escreva o código da função inteira de uma vez!** Siga os passos:

1.  **RED:** Escreva um teste para o cenário mais simples.
    *   `Teste: Entrada 1 deve retornar "1"`.
    *   Execute. Deve falhar (a função nem existe ou está vazia).
2.  **GREEN:** Escreva o código MÍNIMO para passar.
    *   `return "1"` (Sim, hardcoded! Isso é Baby Steps).
    *   Execute. Passou? Ótimo.
3.  **REFACTOR:** Precisa mudar algo? Ainda não.
4.  **RED:** Próximo teste.
    *   `Teste: Entrada 2 deve retornar "2"`.
    *   Execute. Falha (está retornando "1").
5.  **GREEN:** Código mínimo.
    *   `if (n == 2) return "2"; return "1";` (Ou, agora sim, `return n.toString()`).
6.  **RED:** Próximo teste (Lógica nova).
    *   `Teste: Entrada 3 deve retornar "Fizz"`.
    *   Execute. Falha.
7.  **GREEN:** Implemente a lógica do 3.
    *   `if (n % 3 == 0) return "Fizz";`
8.  **... Continue até cobrir o Buzz e o FizzBuzz.**

## Entregável
Se você sabe programar, entregue o código (JS, Python, Java). Se não sabe, escreva o "pseudocódigo" dos testes e da lógica seguindo os passos acima em um arquivo de texto.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
