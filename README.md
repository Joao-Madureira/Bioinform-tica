# Grupo 14
### Constituído por:
PG53937 - João Madureira

PG53701 - Bruna Matos

PG53809 - Filipa Ribeiro

PG54086 - Marta Ferreira

# Dataset
Dataset: Caco-2 (Cell Effective Permeability), Wang et al.

Linhas: 909 

Colunas: Drug_ID, Drug, Y 

Input: Drug (SMILES)

Objetivo: Prever a permeabilidade efetiva dos vários fármacos existentes no dataset.

Link: https://tdcommons.ai/single_pred_tasks/adme/#caco-2-cell-effective-permeability-wang-et-al

### Descrição:

A linha celular de cancro do epitélio do cólon humano, Caco-2, é utilizada como um modelo in vitro para simular o tecido intestinal humano. O resultado experimental da taxa de passagem do medicamento (Permeabilidade Efetiva) através das células Caco-2 pode aproximar-se da taxa com que o medicamento permeia através do tecido intestinal humano.

# Metodologia

### Etapa 1:
Carregar o conjunto de dados e adicionar ao dataset vários descritores relacionados com o SMILES referentes a cada fármaco, obtendo assim um conjunto de dados com variáveis numéricas. Analisar os dados e realizar os passos de pré-processamento.

### Etapa 2:
Usar as técnicas de redução de dimensionalidade adequadas aos dados. Aplicar métodos de clustering que considere adequados aos dados.
Reportar/ analisar os métodos usados e os resultados.

### Etapa 3:
(alterar segundo o que vamos aplicar)
Comparar o comportamento de pelo menos três modelos/ algoritmos de Aprendizagem Máquina no conjunto de dados. Analisar o comportamento dos algoritmos calculando métricas de erro apropriadas e usando métodos de estimação do erro adequados. Fazer um processo de otimização dos modelos selecionados e reportar o melhor modelo obtido e uma estimativa dos seus erros.
Reportar/ analisar os resultados.
