# Truss_Solver_Final
Esse é um código criado para resolver qualquer configuração de treliça bidimensional. A teoria utilizada foi baseada no método da rigidez direta.

## Arquivos de texto de input:

Para utilizar o código, é necessário inserir três arquivos de texto que são:

#### Matriz Conectividade
Esse arquivo relaciona o número do elemento com número do nó onde o elemento inicia e termina no formato:
(Numero do elemento, Nó inicial, Nó final)
Um exemplo do arquivo está no repositório como "Matriz_conectividade_exemplo"

#### Matriz Malha
Esse arquivo relaciona o número do nó com suas respectivas posições em relação a um referencial inicial no formato:
(Número do nó, Posição inicial, Posição final)
Um exemplo do arquivo está no repositório como "Matriz_malha_exemplo"

#### Forças
Esse arquivo relaciona a força aplicada com sua direção, levando em conta que para cada nó, possuimos a direção x e y, no formato:
(Número do nó, Posição inicial, Posição final)
Um exemplo do arquivo está no repositório como "forcas_exemplo

## Saída da função
A função retorna o maior deslocamento e maior tensão em módulo, bem como as forças de reação, porém pode ser facilmente modificado para retornar a lista de todas as tensões e deslocamentos.
