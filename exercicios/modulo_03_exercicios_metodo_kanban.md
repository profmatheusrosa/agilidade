# Módulo 03 - Exercícios: Método Kanban

## Exercício Prático 1: Identificando Gargalos

**Objetivo:** Analisar um fluxo e identificar onde melhorar.

**Instruções:**
Imagine um processo de desenvolvimento com as seguintes etapas e capacidades diárias (Vazão máxima):
1.  Análise: Capaz de 5 itens/dia
2.  Desenvolvimento: Capaz de 2 itens/dia
3.  Testes: Capaz de 6 itens/dia

Responda:
1.  Onde está o gargalo deste sistema?
2.  O que acontecerá com a coluna de "Análise Pronta/Aguardando Desenvolvimento" se não houver limite de WIP?
3.  Se contratarmos mais 3 testadores, o sistema entregará mais rápido? Por quê?

<details>
<summary>Ver Gabarito Sugerido</summary>

1.  **Gargalo:** Desenvolvimento (2 itens/dia). É a etapa mais lenta que dita o ritmo de todo o sistema.
2.  **Acúmulo:** A fila crescerá infinitamente, pois a Análise "empurra" 5 coisas, mas o Dev só consegue "puxar" 2. WIP alto, Lead Time alto.
3.  **Não.** O gargalo é Desenvolvimento. Melhorar Testes (que já é rápido) apenas aumentará a ociosidade dos testadores. Para entregar mais rápido, precisamos elevar a capacidade do Desenvolvimento.
</details>

## Exercício Prático 2: Políticas Explícitas

**Objetivo:** Definir critérios de qualidade e transição.

**Instruções:**
Escreva uma "Definition of Done" (Política de Saída) para a coluna **"Em Desenvolvimento"** antes de mover um cartão para **"Em Testes"**. O que deve ser verdade sobre o código?

*Exemplo de itens para considerar:* Testes unitários, Code Review, Critérios de Aceitação.

<details>
<summary>Ver Gabarito Sugerido</summary>

**Política de Saída: Desenvolvimento -> Testes**

Para mover um cartão, é necessário:
1.  Todo o código comitado no repositório.
2.  Testes unitários automatizados passando.
3.  Code Review realizado e aprovado por outro par.
4.  Ambiente de testes atualizado com a build.
5.  Nenhum erro de lint/estilo conhecido.

*Sem isso, o cartão NÃO SAAI de Dev.*
</details>

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
