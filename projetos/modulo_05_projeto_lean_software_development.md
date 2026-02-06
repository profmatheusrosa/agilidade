# Módulo 05 - Projeto: Mapa de Cadeia de Valor (Value Stream Mapping) Simples

## Descrição do Projeto
Você vai mapear um processo do seu dia a dia para identificar onde está o tempo de espera (desperdício) vs o tempo de trabalho (valor).

## Cenário
Escolha um processo repetitivo.
*   *Exemplos:* "Aprovar uma compra na empresa", "Fazer o deploy de uma correção", "Preparar o café da manhã", "Renovar a carteira de motorista".

## Execução

1. **Desenhe o Fluxo:** Liste as etapas sequenciais.
2. **Cronometre (ou estime):**
   - **Tempo de Toque (Touch Time):** O tempo que alguém está *efetivamente* trabalhando naquilo.
   - **Tempo de Espera (Wait Time):** O tempo que a tarefa fica parada esperando alguém pegar, ou esperando uma máquina, ou esperando aprovação.
3. **Calcule a Eficiência do Ciclo:**
   - Eficiência = (Tempo de Toque / Tempo Total) * 100.

## Exemplo (Processo de Deploy Antigo):
1.  Dev codifica: 2h (Toque)
2.  Espera Code Review: 4h (Espera)
3.  Reviewer revisa: 0.5h (Toque)
4.  Espera Janela de Deploy: 2 dias (48h) (Espera)
5.  Deploy: 0.5h (Toque)

*   **Total Toque:** 3h
*   **Total Espera:** 52h
*   **Tempo Total:** 55h
*   **Eficiência:** (3 / 55) = **5.4%**

## Análise
Onde está a maior oportunidade de melhoria? Fazer o dev digitar mais rápido (reduzir as 2h) ou eliminar a espera de 2 dias? (Dica: Lean foca na espera).

## Entregável
Seu mapa (desenho ou lista) e o cálculo da eficiência.

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
