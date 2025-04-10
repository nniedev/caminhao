# 🚛 Desafio do Caminhão
Este repositório busca resolver o desafio BeeCrowd 1476 da Maratona de Programação da SBC Brasil, e contém o desenvolvimento de uma atividade envolvento grafos, ela consiste em: 

- **`Gerar`**: Gerar um grafo a partir de uma entrada txt de números ordenados, este grafo deve transformar os números ilhas e pontes (Vértices e Arestas).
- **`Relacionar`**: De acordo com a entrada, definir e plotar as ilhas e suas respectivas pontes.
- **`Definir o Vencedor`**: Destacar os caminhos solicitados de forma a priorizar o maior peso possível.

## 🔍 Objetivo
O objetivo do trabalho é desenvolver meus conhecimentos sobre a Biblioteca NetworkX em Python e utilizar grafos na prática, o desafio busca encontrar o melhor caminho possível entre duas ilhas, priorizando o caminho que possibilita carregar o maior peso.

## 💾 Regras
- **`Entrada`**
1. A primeira linha de um caso de teste contém três inteiros N(2 ≤ N ≤ 2 x 104), M(1 ≤ M ≤ 105) e S(1 ≤ S ≤ 5 × 104), indicando, respectivamente, o número de ilhas da Nlogônia, o número de pontes que ligam as ilhas e o número de sedes.
2. As ilhas nlogonianas são numeradas de 1 a N. Cada uma das M linhas seguintes descreve uma ponte. A descrição de cada ponte consiste de uma linha contendo três inteiros A, B(1 ≤ A,B ≤ N, A != B) e P(0 ≤ P ≤ 105), indicando as duas ilhas ligadas por aquela ponte e o peso máximo permitido naquela ponte, em toneladas.
3. Todas as pontes são de mão dupla; cada par de ilhas é ligado por no máximo uma ponte; é possível ir de qualquer ilha para qualquer outra ilha utilizando apenas as pontes do arquipélago (mas pode ser preciso passar por outras ilhas primeiro). Cada uma das S linhas seguintes descreve uma sede.
4. A descrição de cada sede consiste de uma linha contendo dois inteiros A e B, indicando, respectivamente, a ilha onde está a sede e a ilha onde está o depósito que irá fornecer os balões àquela sede. O final da entrada é determinado por EOF (fim de arquivo).

- **`Saída`**
1. Para cada sede, na ordem em que elas foram descritas na entrada, seu programa deve imprimir uma linha contendo um único inteiro, indicando o maior peso bruto, em toneladas, que pode ser transportado por caminhão do depósito que irá fornecer os balões até ela.

## 📝 Conteúdo do Repositório
- `Graphs_and_Social_2nd_Assignment.ipynb` - Notebook contendo o código.
- `README.md` - Documento explicativo sobre o projeto.

## 💪 Tecnologias Utilizadas
- **Linguagem:** Python (NetworkX, Pandas, Matplot.lib e Numpy)
- **Ambiente:** Google Collaboratory e Jupyter Notebook
