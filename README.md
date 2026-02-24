# 🎤 Turnê Mundial - Sistema de Planejamento de Shows

Projeto desenvolvido para a disciplina de **Algoritmos e Estruturas de
Dados II** do curso de **Bacharelado em Ciência da Computação**.

## 📚 Sobre o Projeto

Uma empresa de eventos precisa organizar turnês mundiais para diversos
artistas.\
Cada artista deve viajar da cidade de origem até a cidade destino no
**menor tempo possível**, realizando shows nas cidades por onde passar.

O sistema:

-   📍 Modela cidades como um **grafo direcionado ponderado**
-   ✈️ Calcula o menor tempo de voo usando **Dijkstra**
-   🎵 Simula apresentações considerando duração fixa de show
-   📆 Determina em quais dias cada artista se apresentou
-   📄 Gera saída formatada conforme especificação do problema

------------------------------------------------------------------------

## 🧠 Conceitos Aplicados

-   Grafos direcionados
-   Lista de adjacência
-   Algoritmo de Dijkstra
-   Critérios de desempate:
    -   Menor tempo total
    -   Menor número de cidades
    -   Ordem lexicográfica
-   Manipulação de strings em C
-   Controle rigoroso de formatação de saída

------------------------------------------------------------------------

## 🛠 Tecnologias Utilizadas

-   Linguagem C
-   Compilador GCC
-   Estruturas de dados estáticas

------------------------------------------------------------------------

## 📂 Estrutura do Projeto

. ├── main.c ├── entrada.in ├── saida.out └── README.md

------------------------------------------------------------------------

## ▶️ Como Compilar

``` bash
gcc main.c -o turne
```

------------------------------------------------------------------------

## ▶️ Como Executar

``` bash
./turne < entrada.in
```

------------------------------------------------------------------------

## 🎯 Objetivos Acadêmicos

Este projeto reforça conceitos fundamentais de:

-   Modelagem de problemas com grafos
-   Algoritmos de caminho mínimo
-   Simulação temporal
-   Implementação baseada em especificação formal

------------------------------------------------------------------------

## 👨‍💻 Autor

Willian Torres\
Bacharelado em Ciência da Computação\
Universidade Federal do Agreste de Pernambuco
