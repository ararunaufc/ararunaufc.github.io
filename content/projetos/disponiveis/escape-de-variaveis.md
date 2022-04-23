+++
title = "Algoritmos de detecção de escape de variáveis"
description = "Para linguagens que gerenciam memória de maneira automática, geralmente uma das tarefas do compilador, na intenção de otimizar o uso de memória, é decidir se os dados referenciados por uma variável devem residir no heap ou na pilha de execução. Para isso, é necessário detectar se, por assim dizer, aqueles dados podem ou não ser compartilhados entre funções com tempo de vida distintos, o que chamamos de \"Análise de escape\". Este projeto visa estudar e avaliar as soluções já propostas para esse fim."

weight = 15

date = 2022-01-01
updated = "2022-04-21"

[taxonomies]
area = [ "Compiladores", "Interação Humano-Computador", ]
academic_level = [ "TCC" ]

[extra]
type = "Research"
available = true
has_applicants = false
+++

## Nível acadêmico compatível

Trabalho de Conclusão de Curso

## Descrição

Para linguagens que gerenciam memória de maneira automática, geralmente uma das tarefas do compilador, na intenção de otimizar o uso de memória, é decidir se os dados referenciados por uma variável devem residir no heap ou na pilha de execução. Para isso, é necessário detectar se, por assim dizer, aqueles dados podem ou não ser compartilhados entre funções com tempo de vida distintos, o que chamamos de \"Análise de escape\".

Este projeto visa estudar e avaliar as soluções já propostas para esse fim.

## Possíveis Atividades

- Investigar publicações sobre o tema
- Investigar publicações com comparativos entre soluções
- Implementação e validação ou comparação de soluções
- Identificar fatores determinantes dos algoritmos ou das semânticas de linguagem para a eficiência das soluções

## Escopo

{{ ui_message(content="O escopo definitivo do trabalho ainda não está definido.", type="warning") }}

## Conhecimento

### Cursos desejáveis

{{ ui_message(content="Os cursos a seguir são os têm perfil mais próximo ao necessário para o projeto. Isso não significa que os demais cursos sejam indesejados.", type="info") }}

1. Ciência da Computação
2. Engenharia de Software

### Disciplinas desejáveis

{{ ui_message(content="As disciplinas a seguir tratam de conteúdos que serão úteis no desenvolvimento do projeto. Entretanto, é possível desenvolver o estudo a partir das noções básicas desses conteúdos, apesar de isso tornar o processo mais lento.", type="info") }}

- Estrutura de Dados Avançada
- Projeto e Análise de Algoritmos
- Compiladores
