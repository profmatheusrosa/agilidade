# Módulo 06: Outras Metodologias

## Sumário
1. [Introdução](#introdução)
2. [Crystal](#crystal)
3. [Feature Driven Development (FDD)](#feature-driven-development-fdd)
4. [DSDM / Atern](#dsdm--atern)
5. [Referências](#referências)

## Introdução
Embora Scrum, Kanban e XP sejam os mais populares, o universo ágil é vasto. Neste módulo, conheceremos metodologias que influenciaram o movimento ou que atendem a nichos específicos.

## Crystal
Criada por Alistair Cockburn (signatário do Manifesto Ágil), a família Crystal foca nas pessoas e na comunicação, acreditando que cada projeto precisa de um conjunto de práticas diferente dependendo do seu tamanho e da criticidade.

### As Cores do Crystal
Crystal classifica projetos em duas dimensões:
1.  **Número de pessoas** (Cores).
2.  **Criticidade** (Conforto, Dinheiro Discrecional, Dinheiro Essencial, Vida).

O nome vem da analogia com cristais geológicos: cores diferentes para durezas diferentes.
*   **Crystal Clear:** Até 6 pessoas (Equivalente ao Scrum/XP).
*   **Crystal Yellow:** Até 20 pessoas.
*   **Crystal Orange:** Até 40 pessoas.
*   **Crystal Red:** Até 80 pessoas.

Quanto mais crítico o sistema ("Vida", por exemplo, software de marca-passo), mais rigoroso deve ser o processo, mesmo com poucas pessoas.

![Triângulo de Ferro vs Ágil](../../imagens/10_triangulo_ferro_vs_agil.png)
*(Comparativo de restrições de projeto)*

## Feature Driven Development (FDD)
Criado por Jeff De Luca, o FDD foca, como o nome diz, em funcionalidades. Tende a ser mais prescritivo na arquitetura do que o Scrum.

**Processo FDD:**
1.  Desenvolver um Modelo Abrangente (Modelagem de Objetos).
2.  Construir uma Lista de Funcionalidades.
3.  Planejar por Funcionalidade.
4.  Detalhar por Funcionalidade (Design).
5.  Construir por Funcionalidade (Build).

É muito focado em "Chief Programmers" (Programadores Chefes) e modelagem de domínio robusta antes de codificar.

## DSDM / Atern
O Dynamic Systems Development Method (DSDM) é talvez o framework ágil mais antigo (1994). Ele foca estritamente em projetos com prazos apertados e fixos. Sua premissa é: "O prazo e o custo são fixos; o escopo é variável" (Invertendo o Triângulo de Ferro tradicional).

### MoSCoW
O DSDM popularizou a técnica de priorização **MoSCoW**:
*   **M**ust Have: Tem que ter (Vital. Sem isso o projeto não serve).
*   **S**hould Have: Deveria ter (Importante, mas existe workaround).
*   **C**ould Have: Poderia ter (Desejável se sobrar tempo).
*   **W**on't Have: Não terá (nesta release).

**Exercício 6:** Segundo a metodologia Crystal, qual fator principal determina o "peso" ou a "cor" da metodologia a ser usada?
a) O orçamento do projeto.
b) O tamanho da equipe e a criticidade do sistema (potencial de dano).
c) A tecnologia escolhida (Java vs Python).
d) A preferência pessoal do Gerente de Projetos.

<details>
<summary>Ver Resposta</summary>

**Resposta:** b) O tamanho da equipe e a criticidade do sistema.

**Explicação:** Alistair Cockburn argumenta que um time de 6 pessoas fazendo um site de fotos (Crystal Clear) precisa de muito menos burocracia que um time de 80 pessoas fazendo um software de controle aéreo (Crystal Red/Diamond).
</details>

## Referências

[1] Cockburn, A. Crystal Clear: A Human-Powered Methodology for Small Teams. Addison-Wesley, 2004.
[2] Coad, P. et al. Java Modeling in Color with UML (onde o FDD foi descrito). Prentice Hall, 1999.
[3] Agile Business Consortium. The DSDM Agile Project Framework.

[Próximo módulo →](../teoria/modulo_07_agilidade_em_escala.md)
[Voltar aos Links Rápidos](../README.md#links-rapidos)
