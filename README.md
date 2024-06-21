# AirQuality-WaterPollution-Analytics

## Objetivo

O objetivo principal deste projeto é analisar os dados de qualidade do ar e poluição da água para identificar padrões e tendências, além de fornecer insights valiosos que possam ajudar na tomada de decisões e políticas ambientais. 

## Análises feitas

Dados importantes sobre o banco de dados: 
 - quantas e quais são as colunas e quais são os valores não nulos de cada coluna e o tipo de dado de cada coluna
 - quantos valores diferentes tem para cada coluna e quais são os países que aparecem e quais são 10 que mais aparecem
Métricas Básicas de cada coluna:
 - valores nulos e não nulos
 - valor mínimo e máximo
 - moda, média e mediana
 - quantile 25,50 e 70
 - desvio padrão e variância
Outliers:
  - mostra valores que estão muitos dispersos 
Mostrando os países com as melhores/piores médias nas colunas 'AirQuality' e 'WaterPollution':
  - Separar os valores de cada páises
  - Fazer média para cada país
  - mostrar os 10 primeiros e últimos
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
  - mostra qual a tendência dos dados de uma coluna em relação a outra
Regressão entre as colunas "AirQuality" e "WaterPollution":
  - faz previsões e infere causalidade entre as colunas "AirQuality" e "WaterPollution"

## Ferramentas Utilizadas

- **Excel:** Para a organização inicial dos dados e análises exploratórias.
- **Python:** Para a análise de dados e visualizações, utilizando as seguintes bibliotecas:
  - `pandas`
  - `matplotlib`
  - `seaborn`
