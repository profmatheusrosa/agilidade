# Módulo 04 - Exercícios: Extreme Programming (XP)

## Exercício Prático 1: Refactoring Mental

**Objetivo:** Identificar oportunidades de melhoria de código (mesmo sem codificar).

**Instruções:**
Analise o pseudocódigo abaixo e identifique o que está errado (Code Smell) e como o conceito de Simplicidade e Refatoração poderia ser aplicado.

```
função calcularPreco(produto, cliente) {
    se (produto.tipo == "ELETRONICO") {
        se (cliente.vip == verdadeiro) {
            retornar produto.preco * 0.90;
        } senão {
            se (cliente.novo == verdadeiro) {
                 retornar produto.preco * 0.95; 
            }
            retornar produto.preco;
        }
    }
    se (produto.tipo == "LIVRO") {
       // ... lógica repetida com outros valores ...
    }
    // ... mais 50 linhas com ifs aninhados para cada tipo ...
}
```

<details>
<summary>Ver Gabarito Sugerido</summary>

**Problema:** Alta complexidade ciclomática (muitos `ifs` aninhados) e lógica repetida. É difícil de entender e manter.
**Solução XP:**
1.  **Refatoração:** Extrair métodos ou usar polimorfismo (Estratégia).
2.  **Simplicidade:** Em vez de um "Big If", criar classes/estratégias de desconto separadas para cada tipo de produto, tornando o código principal limpo e cada regra fácil de testar isoladamente.
</details>

## Exercício Prático 2: Simulação de Pair Programming

**Objetivo:** Exercitar a comunicação e troca de papéis.

**Instruções:**
Se você estiver estudando sozinho, simule o diálogo. Se estiver com alguém, pratique.
A tarefa é: "Descrever como trocar um pneu furado".
*   **Rodada 1 (5 min):** Pessoa A dita os passos, Pessoa B escreve (mas pode questionar).
*   **Rodada 2 (5 min):** Pessoa B dita melhorias e detalhes de segurança, Pessoa A escreve.

**Reflexão:**
Como a segunda pessoa (o copiloto) ajudou a evitar erros (do tipo "esquecer de puxar o freio de mão" antes de levantar o carro)?

<details>
<summary>Ver Comentário</summary>

O Pair Programming brilha em encontrar falhas de lógica "antes" que elas sejam implementadas. Enquanto o Piloto foca na sintaxe (onde está o macaco?), o Copiloto foca na segurança e estratégia (o carro está em um lugar plano?).
</details>

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
