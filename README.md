# Exercicios Segunda Chamada: lcbm

## ENCOTEL - Encontre O Telefone (01)
![PyPI - Status](https://img.shields.io/pypi/status/Django.svg)

ENCOTEL é um dos problemas da primeira seletiva para Maratona de Programacao UFRN de 2005 e atualmente encontra-se no [SPOJ](https://br.spoj.com/problems/ENCOTEL/).

### Contexto
Em alguns lugares é comum lembrar um número do telefone associando seus dígitos a letras. Dessa maneira a expressão `MY LOVE` significa `69 5683`. Claro que existem alguns problemas, uma vez que alguns números de telefone não formam uma palavra ou uma frase e os dígitos `1` e `0` não estão associados a nenhuma letra.

Sua tarefa é ler uma expressão e encontrar o número de telefone correspondente baseado na tabela abaixo. Uma expressão é composta por letras maiúsculas (`A-Z`), hifens (`-`) e os números `1` e `0`.

| Letras | Número |
| ------ | ------ |
| ABC | 2 |
| DEF | 3 |
| GHI | 4 |
| JKL | 5 |
| MNO | 6 |
| PQRS | 7 |
| TUV | 8 |
| WXYZ | 9 |


## JFILA14 - Fila (03)
![PyPI - Status](https://img.shields.io/pypi/status/Django.svg)

JQUEUE is a Queue challenge from phase 1 of the Brazilian Computing Olympics 2014. This repo is an attempt to solve [SPOJ's version](https://br.spoj.com/problems/JFILA14/) of the problem.

### Context
With the World CUp approaching, the flow of people in lines (queues) to buy tickets has increased considerably. Since queues are bigger and bigger, less patient people tend to give up the ticket purchase and leave the queue - openning space to other people. When someone leave the queue, everyone that was behind her gives a step ahead, this way there is enver an empty space between two people. Initially, the queue has N people, each with an identifier. Johnzinho knows the initial state of the queue and the identifiers in order of those who left the queue, each with a different identifier. Knowing that after the initial state no one entered the line, Johnzinho wishes to know the final state of the queue.

## 1195 - Binary Search Tree (05)
![PyPI - Status](https://img.shields.io/pypi/status/Django.svg)

Binary Search Tree is a binary tree challenge that can by found at [URI](https://www.urionlinejudge.com.br/judge/en/problems/view/1195).

### Context
In computer science, a binary search tree `(BST)`, which may sometimes also be called an ordered or sorted binary tree is a node-based binary tree data structure which has the following properties:

1. The left subtree of a node contains only nodes with keys less than the node's key;
2. The right subtree of a node contains only nodes with keys greater than or equal to the node's key;
3. Both the left and right subtrees must also be binary search trees.

The major advantage of binary search trees over other data structures is that the related sorting algorithms and search algorithms such as in-order traversal can be very efficient.

For this problem, you will receive many set of numbers and from each set you must to build the BST equivalent. For example, an imput with the sequence of numbers: `8 3 10 14 6 4 13 7 1` will result in the following binary search tree:

                                                      08
                                                    /    \
                                                  03      10
                                                 /  \       \
                                               01   06       14
                                                   / \       /    
                                                 04   07   13
