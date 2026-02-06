# Módulo 07 - Exercícios: Agilidade em Escala

## Exercício Prático 1: Desatando Nós (Dependências)

**Objetivo:** Entender o pesadelo das dependências em escala.

**Cenário:**
Você tem 3 times trabalhando no mesmo E-commerce:
*   **Time A (Checkout):** Vai criar o pagamento por PIX.
*   **Time B (Catálogo):** Vai criar a página de "Ofertas Relâmpago".
*   **Time C (Logística):** Vai criar o cálculo de frete para transportadora nova.

**Problema:**
*   Para a "Oferta Relâmpago" funcionar, ela precisa de um frete especial (Time C).
*   Para o PIX funcionar, ele precisa de dados do carrinho que o Time B está refatorando.

**Instruções:**
Como você, como membro de um "Nexus Integration Team" ou em uma "PI Planning" do SAFe, resolveria visualmente essas dependências?

<details>
<summary>Ver Gabarito Sugerido</summary>

**Solução Visual:** O famoso "Board of Dependencies" (Quadro de Dependências) com linhas vermelhas conectando os post-its.
**Solução de Planejamento:**
1.  O Time C precisa entregar o cálculo de frete na Sprint 1 para que o Time B possa usar na Sprint 2. (Sequenciamento).
2.  Ou, definimos uma interface de contrato (Mock) para que ambos trabalhem em paralelo.
3.  O objetivo é *identificar* isso ANTES da sprint começar, não descobrir no meio.
</details>

## Exercício Prático 2: O Desafio do Product Owner no LeSS

**Objetivo:** Entender a sobrecarga cognitiva.

**Cenário:**
No LeSS, um único Product Owner atende até 8 times. Imagine que cada time tem 5 pessoas (40 pessoas no total).
Se cada pessoa fizer UMA pergunta de 5 minutos para o PO por dia, quanto tempo o PO gasta só respondendo a perguntas individuais?

<details>
<summary>Ver Gabarito Sugerido</summary>

**Cálculo:** 40 pessoas * 5 min = 200 minutos (3 horas e 20 min).

**Reflexão:** Isso é inviável, pois o PO ainda precisa falar com clientes e stakeholders.
**Solução LeSS:** O PO NÃO deve falar com os desenvolvedores individualmente sobre detalhes técnicos menores. Os desenvolvedores devem falar *diretamente* com os usuários/clientes ou ler a documentação de negócio macro. O PO foca na priorização macro e direção do produto.
</details>

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
