## 	`CTCO02 - ALGORITMOS E ESTRUTURA DE DADOS II `


# Implementação de B-tree em C 

Este repositório contém uma implementação da estrutura de dados B-tree em linguagem C. A B-tree é uma árvore balanceada amplamente utilizada em sistemas de banco de dados e sistemas de arquivos devido à sua eficiência em operações de inserção, busca e remoção, especialmente em grandes conjuntos de dados.

## Funcionalidades Implementadas

- **Inserção de Chaves:** Permite adicionar novos elementos na B-tree mantendo a estrutura balanceada.
  
- **Divisão de Nós (Split):** Quando um nó atinge sua capacidade máxima, ocorre a divisão para manter o balanceamento da árvore.

- **Ordenação de Índices:** Garante que os índices dentro de cada nó estejam sempre ordenados, facilitando operações de busca.

- **Impressão da Árvore:** Função para imprimir a árvore B em ordem, útil para depuração e visualização.

## Como Usar

Para compilar e executar a implementação:

1. Clone o repositório:
`git clone https://github.com/MartinesEmanuel/B-Tree_Insert`

2. Compile o código:
 `gcc -o btree main.c Btree.c`

3. Execute o programa:
`./btree`


Certifique-se de ajustar os parâmetros de compilação conforme necessário para o seu ambiente.



