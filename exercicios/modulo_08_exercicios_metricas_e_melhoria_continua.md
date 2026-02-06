# Módulo 08 - Exercícios: Métricas e Melhoria Contínua

## Exercício Prático 1: Análise de Causa Raiz (5 Porquês)

**Objetivo:** Sair do sintoma e achar a cura.

**Cenário:** O servidor caiu na Black Friday.

**Instruções:**
Aplique os 5 Porquês para chegar na causa raiz.

1.  **Por que o servidor caiu?**
    *   Porque a memória estourou.
2.  **Por que a memória estourou?**
    *   Porque houve um pico de acessos não previsto e o Auto-scaling não funcionou.
3.  **Por que o Auto-scaling não funcionou?**
    *   ... (Continue) ...

<details>
<summary>Ver Gabarito Sugerido</summary>

3.  **Por que o Auto-scaling não funcionou?**
    *   Porque ele estava configurado com um limite máximo muito baixo (hard limit).
4.  **Por que estava com limite baixo?**
    *   Porque esquecemos de atualizar a configuração de "Ambiente de Teste" para "Produção" no script de infraestrutura.
5.  **Por que esquecemos?**
    *   Porque o processo de deploy é manual e depende de alguém lembrar de editar um arquivo texto.

**Causa Raiz:** Processo de configuração manual e propenso a erro humano.
**Ação:** Automatizar a configuração via IaC (Infrastructure as Code) separada por ambiente.
</details>

## Exercício Prático 2: Vanity Metrics vs Actionable Metrics

**Objetivo:** Distinguir métricas de vaidade vs acionáveis.

**Instruções:**
Classifique as métricas abaixo:
1.  Número total de downloads do App.
2.  Taxa de retenção diária (quantos % voltam no dia seguinte).
3.  Número de horas trabalhadas pelo time.
4.  Lead Time (tempo para resolver um problema do cliente).

<details>
<summary>Ver Gabarito Sugerido</summary>

1.  **Vaidade.** (Pode ter 1 milhão de downloads e ninguém usando).
2.  **Acionável.** (Indica se o produto é bom/viciante).
3.  **Vaidade (ou Pior).** (Trabalhar muito não significa gerar valor).
4.  **Acionável.** (Mede eficiência do serviço e satisfação potencial).
</details>

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
