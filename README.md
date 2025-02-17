# proj-series-temporais

Este projeto consta na aplicação de algortimos de análise de séries temporais em três bases de dados reais para propósitos de extração de características, padrões e comportamentos, bem como predição de valores futuros. Todos os modelos criados foram testados utilizando conjuntos de treino e teste para testar a eficiência. 

Este repositório possui 3 notebooks, cada um referente a uma base de dados diferente:

* ast-fortaleza: precipitações atmosféricas anuais em Fortaleza, Ceará, abrangindo o período de 1849 a 1997.
* ast-lavras: precipitações mensais em Lavras, Minas Gerais, de janeiro de 1966 a dezembro de 1997.
* ast-tetuan: consumo energético diário em três diferentes zonas de Tetuan, Marrocos, no ano de 2017

Obs: a base de dados presente no repositório é somente necessária para o notebook ast-tetuan. Nos demais notebooks, os dados são obtidos diretamente por linha de código, por meio do site da IME-USP

## Algortimos utilizados

- ARIMA
- SARIMA
- Suavização Exponencial Simples
- Suavização Exponencial de Holt
- Suavização Exponencial de Holt-Winter
- Árvore de Decisão
- Prophet 
