# Módulo 05 - Exercícios: Lean Software Development

## Exercício Prático 1: Caça aos Desperdícios (Os 7 Mudas)

**Objetivo:** Identificar os 7 tipos de desperdício em um cenário de TI.

**Instruções:**
Associe o tipo de desperdício Lean ao cenário correspondente.

**Tipos:**
1. Trabalho Parcialmente Feito
2. Funcionalidades Extras
3. Reaprendizagem
4. Handoffs (Passagem de bastão)
5. Troca de Tarefas (Context Switching)
6. Atrasos/Espera
7. Defeitos

**Cenários:**
A. ( ) Um desenvolvedor está trabalhando em 3 projetos ao mesmo tempo, parando um para atender outro.
B. ( ) O analista escreve a especificação, passa para o dev, que passa para o tester, que passa para o deploy. Muita informação se perde no caminho.
C. ( ) O time criou um sistema de relatórios super complexo, mas o cliente só usa o botão "Exportar para Excel".
D. ( ) Um código foi escrito mas ficou 2 semanas esperando Code Review.
E. ( ) O time resolveu um problema complexo mas não documentou a solução. 6 meses depois o problema voltou e tiveram que investigar tudo de novo.

<details>
<summary>Ver Resposta</summary>

A. (5) Troca de Tarefas. O cérebro perde tempo para "carregar o contexto" de cada projeto.
B. (4) Handoffs. Cada passagem de bastão perde conhecimento tácito.
C. (2) Funcionalidades Extras. Ouro de tolo.
D. (1) Trabalho Parcialmente Feito (ou Atrasos). Código não integrado é estoque, não valor.
E. (3) Reaprendizagem. Falta de gestão de conhecimento.
</details>

## Exercício Prático 2: O Último Momento Responsável

**Objetivo:** Praticar o princípio de "Decidir o Mais Tarde Possível".

**Cenário:**
Você está começando um projeto e precisa escolher o Banco de Dados.
*   **Opção A (Tradicional):** Escolher agora o Oracle Enterprise, comprar a licença de 1 ano e modelar tudo, pois "vamos precisar de robustez".
*   **Opção B (Lean):** Usar um banco leve (Postgres ou até memória) e criar uma camada de abstração (Repository Pattern). Adiar a compra da licença cara até que o volume de dados real justifique.

**Perguntas:**
1. Qual o risco da Opção A?
2. Qual o benefício da Opção B?

<details>
<summary>Ver Resposta</summary>

1.  **Risco A:** Gastar dinheiro à toa (se o projeto falhar), ficar "preso" a uma tecnologia complexa desnecessariamente (Lock-in), ou descobrir tarde que o banco não atende a um requisito específico que só surgiria depois.
2.  **Benefício B:** Manter opções abertas. Se o projeto pivotar e virar um app mobile offline, você não gastou com Oracle. Se o projeto explodir de sucesso, você ainda pode migrar (se usou boa arquitetura).
</details>

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
