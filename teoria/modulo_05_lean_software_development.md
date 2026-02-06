# Módulo 05: Lean Software Development

## Sumário
1. [Introdução](#introdução)
2. [Origens no Lean Manufacturing](#origens-no-lean-manufacturing)
3. [Os 7 Princípios Lean](#os-7-princípios-lean)
4. [Referências](#referências)

## Introdução
Lean Software Development (LSD) é uma adaptação dos princípios do Lean Manufacturing (Sistema Toyota de Produção) para o mundo do desenvolvimento de software. Foi popularizado por Mary e Tom Poppendieck. O foco principal é a eficiência do fluxo de valor e a eliminação implacável de desperdícios.

## Origens no Lean Manufacturing
O Lean nasceu no chão de fábrica da Toyota pós-Segunda Guerra. Enquanto a indústria ocidental focava em produção em massa (grandes lotes, estoques altos), a Toyota, com recursos escassos, focou em "Just-in-Time": produzir apenas o necessário, quando necessário, com qualidade perfeita.

No software, isso se traduz em não construir funcionalidades que ninguém pediu ("estoque" de código), não escrever documentação que ninguém vai ler e focar na entrega rápida de valor.

## Os 7 Princípios Lean
Os Poppendiecks traduziram os conceitos de fábrica para o trabalho intelectual:

![Os 7 Princípios Lean](../../imagens/imagem_7_principios_lean.png)
*(Infográfico dos 7 princípios)*

### 1. Eliminar Desperdício (Eliminate Waste)
Tudo que não gera valor para o cliente é desperdício (Muda).
*   *Exemplos:* Funcionalidades não usadas (o maior desperdício), espera, troca de contexto, defeitos, burocracia excessiva.

### 2. Amplificar o Aprendizado (Build Quality In / Amplify Learning)
O desenvolvimento é um processo de descoberta. Use ciclos curtos, testes e feedback para aprender rápido. Qualidade não se insere no final (testes), ela é construída desde o início.

### 3. Decidir o Mais Tarde Possível (Defer Commitment)
Não tome decisões irreversíveis antes de ter informações suficientes. Mantenha as opções abertas até o "último momento responsável". Isso reduz o risco de decidir errado por falta de dados.

### 4. Entregar o Mais Rápido Possível (Deliver Fast)
Quanto mais rápido você entrega, mais rápido recebe feedback e menos tempo o cliente espera. Velocidade habilita a postergação de decisões (Princípio 3).

### 5. Capacitar o Time (Respect People)
Quem faz o trabalho sabe melhor como fazê-lo. Dê autonomia e propósito para as pessoas.

### 6. Construir Integridade (Optimize the Whole)
O software deve ter integridade percebida (usabilidade, adequação ao propósito) e conceitual (arquitetura limpa).

### 7. Ver o Todo (See the Whole)
Evite a sub-otimização. Não adianta otimizar o desenvolvimento se o processo de deploy leva 3 semanas. Otimize a cadeia de valor inteira, do conceito ao dinheiro ("Concept to Cash").

**Exercício 5:** Qual é considerado o MAIOR desperdício no desenvolvimento de software segundo o pensamento Lean?
a) Reuniões longas.
b) Documentação desatualizada.
c) Funcionalidades desenvolvidas que nunca são usadas pelos usuários.
d) Bugs encontrados em produção.

<details>
<summary>Ver Resposta</summary>

**Resposta:** c) Funcionalidades desenvolvidas que nunca são usadas pelos usuários.

**Explicação:** O Standish Group estima que mais de 60% das funcionalidades em sistemas típicos raramente ou nunca são usadas. Isso representa meses de trabalho (análise, dev, teste, manutenção) jogados no lixo. Bugs e reuniões são ruins, mas construir o produto errado é o desperdício supremo.
</details>

## Referências

[1] Poppendieck, M. & Poppendieck, T. Lean Software Development: An Agile Toolkit. Addison-Wesley, 2003.

[Próximo módulo →](../teoria/modulo_06_outras_metodologias.md)
[Voltar aos Links Rápidos](../README.md#links-rapidos)
