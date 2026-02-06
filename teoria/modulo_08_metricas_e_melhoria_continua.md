# Módulo 08: Métricas e Melhoria Contínua

## Sumário
1. [Introdução](#introdução)
2. [Métricas de Processo x Negócio](#métricas-de-processo-x-negócio)
3. [Técnicas de Retrospectiva](#técnicas-de-retrospectiva)
4. [Kaizen](#kaizen)
5. [Referências](#referências)

## Introdução
"O que não pode ser medido, não pode ser gerenciado". No entanto, na agilidade, medir a coisa errada (como linhas de código) pode ser desastroso. Precisamos medir resultado (Outcome) e fluxo, não apenas esforço (Output). E usamos esses dados para alimentar a melhoria contínua.

## Métricas de Processo x Negócio

### Métricas de Processo (Eficiência)
Ajudam o time a entender como está trabalhando.
*   **Velocidade (Velocity):** Média de pontos entregues por Sprint. Útil *apenas* para o time prever capacidade futura. **Nunca** deve ser usada para comparar times.
*   **Lead Time:** Tempo total de entrega.
*   **Burn-down / Burn-up:** Gráficos para acompanhar o progresso diário da Sprint ou do Release.

![Gráfico Burndown](../../imagens/imagem_burndown_chart.png)
*(Acompanhamento do trabalho restante vs tempo)*

### Métricas de Negócio (Eficácia)
Indicam se estamos construindo a coisa certa.
*   **Valor de Negócio (Business Value):** Atribuído pelo PO.
*   **NPS (Net Promoter Score):** Satisfação do cliente.
*   **OKRs (Objectives and Key Results):** Objetivos estratégicos conectados aos resultados-chave mensuráveis. Agilidade sem direção estratégica é apenas correr rápido em círculos.

## Técnicas de Retrospectiva
A Retrospectiva é o motor da melhoria. Se as suas são chatas, mude o formato.

### Starfish (Estrela do Mar)
Divide o quadro em 5 áreas para gerar insights mais ricos que o simples "Bom/Ruim":
1.  **Keep (Manter):** Coisas boas que não queremos perder.
2.  **Stop (Parar):** Coisas que não agregam valor ou atrapalham.
3.  **Start (Começar):** Novas ideias para tentar.
4.  **More (Mais):** O que já fazemos mas deveríamos intensificar.
5.  **Less (Menos):** O que fazemos mas deveríamos reduzir.

![Retrospectiva Starfish](../../imagens/imagem_retrospectiva_starfish.png)
*(Modelo visual de retrospectiva de 5 pontas)*

### Sailboat (Barco a Vela)
Metáfora visual:
*   **Vento:** O que nos empurra para frente (Forças).
*   **Âncora:** O que nos segura/atrasa (Problemas).
*   **Iceberg:** Riscos futuros.
*   **Ilha:** O objetivo/paraíso.

### 5 Porquês (Root Cause Analysis)
Diante de um problema, pergunte "Por quê?" cinco vezes para chegar à causa raiz, em vez de tratar o sintoma.

## Kaizen
Palavra japonesa para "mudança para melhor". Representa a filosofia de que tudo pode ser melhorado sempre. Não é um projeto, é uma cultura.

**Exercício 8:** Você percebe que a velocidade do time (Story Points entregues) aumentou de 20 para 30, mas o número de bugs em produção dobrou. O que isso indica?
a) O time está muito produtivo e os bugs são normais.
b) O time provavelmente começou a sacrificar qualidade (cortar caminho nos testes ou reviews) para "bater a meta" de pontos.
c) Você deve premiar o time pelo aumento da velocidade.
d) Os pontos estavam mal estimados.

<details>
<summary>Ver Resposta</summary>

**Resposta:** b) O time provavelmente começou a sacrificar qualidade...

**Explicação:** A Lei de Goodhart diz que "Quando uma medida se torna um alvo, ela deixa de ser uma boa medida". Focar apenas em aumentar a velocidade geralmente destrói a qualidade. Velocidade é uma consequência, não uma meta.
</details>

## Referências

[1] Derby, E. & Larsen, D. Agile Retrospectives: Making Good Teams Great. Pragmatic Bookshelf, 2006.
[2] Doerr, J. Measure What Matters (sobre OKRs). Penguin Portfolio, 2018.

[Próximo módulo →](../teoria/modulo_09_transformacao_agil_e_cultura.md)
[Voltar aos Links Rápidos](../README.md#links-rapidos)
