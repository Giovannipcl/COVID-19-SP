# COVID-19 Estado de São Paulo
***

## Análise exploratória

Análise exploratória sobre os casos de COVID-19 nas cidadades do estado de SP. *Útilma atualização: 21/02/2021*

**Fonte:** https://github.com/seade-R/dados-covid-sp

Mapa abaixo contém o número de novos casos (por 100 mil habitantes) do mês de Fevereiro de 2021.

![mapa](https://raw.githubusercontent.com/Giovannipcl/COVID-19-SP/main/mapas/novoscasosFev.png)

O mapa abaixo contém a porcentagem de ocupação de leitos nos Departamentos Regionais de Saúde (DRS) referente aos mês de Fevereiro.

![mapa2](https://raw.githubusercontent.com/Giovannipcl/COVID-19-SP/main/mapas/ocupFev.png)

O resto da análise está em CovidEA.ipynb.

## Analisando os fatores relacionados ao óbito por COVID-19.

A segunda análise é feita em um conjunto de dados que contém a variável óbito. Essa váriavel indica se o paciente veio a óbito por COVID-19. Além disso, alguns fatores relacionados a esse paciente estão presentes, por exemplo: paciente apresenta o fator de risco diabetes,  paciente apresenta o fator de risco doença renal, idade, entre outras. 

**Objetivo:** Usar o modelo de Regressão Logística e o algoritmo de ML Árvore de decisão para encontrar alguns fatores que mais impactam nos óbitos por COVID-19. Além disso, foi encontrada a  acurácia de cada modelo.

