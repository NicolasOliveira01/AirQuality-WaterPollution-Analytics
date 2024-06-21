# AirQuality-WaterPollution-Analytics

## Objetivo

O objetivo principal deste projeto é analisar os dados de qualidade do ar e poluição da água para identificar padrões e tendências, além de fornecer insights valiosos que possam ajudar na tomada de decisões e políticas ambientais. 

Link para o banco de dados: https://www.kaggle.com/datasets/patricklford/water-and-air-quality?select=Cities1.csv

## Análises feitas

### Dados importantes sobre o banco de dados: 
 - Quantas e quais são as colunas e quais são os valores não nulos de cada coluna e o tipo de dado de cada coluna
 - Quantos valores diferentes tem para cada coluna e quais são os países que aparecem e quais são 10 que mais aparecem

Métricas Básicas de cada coluna:
 - Valores nulos e não nulos
 - Valor mínimo e máximo
 - Moda, média e mediana
 - Quantile 25,50 e 70
 - Desvio padrão e variância

Outliers:
  - Mostra valores que estão muitos dispersos

Mostrando os países com as melhores/piores médias nas colunas 'AirQuality' e 'WaterPollution':
  - Separar os valores de cada páises
  - Fazer média para cada país
  - Mostrar os 10 primeiros e últimos

Dados sobre o Brasil:
  - Mostrar a quantidade de vezes que aparece dados sobre cada estado brasileiro
  - Quais estados possuem as piores/melhores médias nas colunas 'AirQuality' e 'WaterPollution'
  - Média do Brasil nas colunas 'AirQuality' e 'WaterPollution'

Teste T:
  - Etapas necessárias antes de realizar o teste t
  - Verificar se a média de Minas Gerais, Espírito Santo e Rio de Janeiro na coluna 'AirQuality' é estatisticamente diferente ou não da média de São Paulo na coluna 'AirQuality'

ANOVA:
  - Verificar se a média dos estados do sudeste são estatisticamente diferentes ou não

Correlação entre as colunas "AirQuality" e "WaterPollution":
  - Mostra qual a tendência dos dados de uma coluna em relação a outra

Regressão entre as colunas "AirQuality" e "WaterPollution":
  - Faz previsões e infere causalidade entre as colunas "AirQuality" e "WaterPollution"

Gerar gráficos:
 - Com os dados de cada análise um gráfico é feito para melhorar o entendimento da análise

Gerar insights:
 - Acada análise é feito uma conclusão sobre os dados gerados

## Ferramentas Utilizadas

- **Excel:** Para a organização inicial dos dados 
- **Python:** Uso de funções para fazer a análise dados com as bibliotecas:  
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
