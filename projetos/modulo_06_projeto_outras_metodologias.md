# Módulo 06 - Projeto: Planejamento Orientado a Funcionalidades (Mini-FDD)

## Descrição do Projeto
Você vai experimentar a abordagem do FDD de "Planejar por Funcionalidade" para um sistema simples de Biblioteca.

## Execução

### Passo 1: Desenvolver um Modelo Geral (Mental)
Imagine as entidades principais: Livro, Autor, Usuário, Empréstimo.

### Passo 2: Construir a Lista de Funcionalidades (Feature List)
No FDD, uma funcionalidade é pequena (<cliente> <ação> <resultado>).
Liste 5 funcionalidades usando o padrão:
*   *verbo* a(o) *result* de um(a) *objeto*
*   (Ex do inglês: "Calculate the total of a Sale").

*Tente traduzir para:*
1.  Cadastrar um novo Livro.
2.  Calcular a multa de um Empréstimo.
3.  ...

### Passo 3: Planejar por Funcionalidade
Agrupe essas funcionalidades em "Conjuntos de Funcionalidades" (Feature Sets) e estime a ordem.
*   Grupo: Gestão de Acervo (Add Livro, Remover Livro).
*   Grupo: Circulação (Emprestar, Devolver, Multar).

### Passo 4: Design e Construção (Simulado)
Para a funcionalidade "Calcular a Multa":
*   Quais dados eu preciso? (Data prevista, Data real, Valor diário).
*   Qual classe é responsável? (Provavelmente a classe `Empréstimo`).

## Entregável
A lista de funcionalidades organizada hierarquicamente (Área -> Conjunto -> Funcionalidade).

---
[Voltar aos Links Rápidos](../README.md#links-rapidos)
