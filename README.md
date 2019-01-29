# Cognitivo

## Analise descritiva e preditiva do problema de qualidade dos vinhos.

### Os detalhes da modelagem estão presentes no arquivo principal.

### a. Como foi a definição da sua estratégia de modelagem?
Começando com a limpeza dos dados, detectando outliers e erros de imput nos dados, em seguida 
tentamos predizer o valor do score da qualidade dos vinhos como um problema de regressão; por último categorizamos o score de qualidade
para abordar o problema de classificação.

### b. Como foi definida a função de custo utilizada?
Para problemas de regressão usamos as métricas de custo: MAE e MRSE.
Para problemas de classificação usamos o AUC.

### c. Qual foi o critério utilizado na seleção do modelo final?
Sempre observamos o gap entre o custo no treinamento e na validacao/teste. Modelos que apresentam baixo valor de gap indicam boa
capacidade de generalização, pois o comportamento do modelo no treino e teste foram proximos, indicando estabilidade do modelo no problema 
preditivo.

### d. Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar
este método?
Usamos o cross validation do tipo holdout.

### e. Quais evidências você possui de que seu modelo é suficientemente bom?
Varios pontos de melhoria foram indicados no relatório, os modelos apresentados foram construidos de acordo com a boa pratica de modelagem,
com as fases de limpeza e descrição das variaveis e cross validation para evitar overfiting.



