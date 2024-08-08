
### 1. Selecionar Dataset
  dataset-1000-com-preco-promocional-e-renovacao-estoque.csv

### 2. Construir/Treinar
  Col Target: QUANTIDADE_ESTOQUE 
  Col ID: ID_PRODUTO 
  Col TIME: DATA_EVENTO 
  Feriados: Brasil 
  Nº de dias para Predição: 7

### 3. Analisar
  Média do desvio absoluto ponderado (wQL): 0.226
  Erro percentual absoluto médio (MAPE): 1.495%
  Erro percentual absoluto ponderado (WAPE): 0.326%
  Raiz do erro quadrático médio (RMSE): 28.478
  Erro absoluto médio escalado (MASE): 1.284

### 4. Prever

  Podemos usar o P50 normalmente, mas nos dias próximos ao P90, é melhor considerar o P90 para evitar falta de itens e maximizar as vendas. O estoque é uma alocação de recursos, e o lucro vem da liquidez. Mesmo se restarem     poucas unidades, isso será revisado na próxima reposição.
  Através das predições podemos reduzir o investimento excessivo em produtos com baixa demanda.
