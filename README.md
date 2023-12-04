[![author](https://img.shields.io/badge/author-henriquewfranco-red.svg)](https://www.linkedin.com/in/henriquewfranco/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) ![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)
# Análise de Dados da Era dos Pontos Corridos da Série A do Campeonato Brasileiro

<p align="center">
  <img alt="Série A" width="80%" src="https://publisher-publish.s3.eu-central-1.amazonaws.com/pb-brasil247/swp/jtjeq9/media/20210924080952_15577685bb1360072c42e868e6fa602b5c2d2fd9e6e968d642648607b828b6c2.jpg">
</p>

## Objetivo do Estudo
Essa é uma análise exploratória dos dados do *dataset* do Campeonato Brasileiro da Série A durante a Era dos Pontos Corridos. O objetivo do estudo foi obter insights sobre variáveis como pontuação, número de vitórias, derrotas e empates, além da distribuição de gols e cartões dessa competição futebolísitca nacional.

**Pode acessar o link abaixo para acessar o projeto completo:**
 - [**Projeto no Google Colab**](https://colab.research.google.com/drive/1sXlmLboty2xJMlC_YGA_uxpQNJGXYA9E?usp=sharing)

É importante ressaltar que a análise de dados é uma ferramenta complementar e que o futebol também envolve fatores intangíveis e imprevisíveis. Afinal, o **'futebol é uma caixinha de surpresas'**.

## Fonte dos Dados
Todos os dados usados aqui foram obtidos a partir do [Kaggle](https://www.kaggle.com/). Para esta análise exploratória inicial, serão utilizados três datasets disponibilizados no link abaixo:

* [Campeonato Brasileiro de futebol](https://www.kaggle.com/datasets/adaoduque/campeonato-brasileiro-de-futebol)


## Tecnologias Utilizadas
<p align="left">  
  <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> 
  <a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="numpy" width="40" height="40"/> 
  <a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://seeklogo.com/images/M/matplotlib-logo-7676870AC0-seeklogo.com.png" alt="matplotlib" width="40" height="40"/> 
</p> 

## Destaques do Projeto
### Divisão do estudo:

### 1. Análise de Pontos e Desempenho dos Clubes
Criei algumas tabelas para verificar o desempenho de todos os clubes que participaram da Série A do Brasileirão. Como exemplo, abaixo há a "Tabela Comparativa de Vitórias, Empates e Derrotas de Mandantes e Visitantes".
<p align="center">
  <img alt="Tabela" width="70%" src="https://github.com/HenriqueWF/Serie_A_Campeonato_Brasileiro/assets/86746927/8cb9f71a-6850-45e9-a82e-7be9e624fbc5">
</p>

Além disso, elaborei alguns gráficos selecionando os dez clubes com maior quantidade de vitórias, derrotas e empates, tanto jogando em casa como fora, em relação ao total de partidas disputadas no Brasileirão.
<p align="center">
  <img alt="Vitórias" width="70%" src="https://github.com/HenriqueWF/Serie_A_Campeonato_Brasileiro/assets/86746927/4e6a1057-25b2-4f8b-8a0d-e29379cba7c8">
  <img alt="Derrotas" width="45%" src="https://github.com/HenriqueWF/Serie_A_Campeonato_Brasileiro/assets/86746927/aa3993ef-e008-4911-8a04-b819fb7b1455">
  <img alt="Empates" width="45%" src="https://github.com/HenriqueWF/Serie_A_Campeonato_Brasileiro/assets/86746927/bff611d5-f838-458c-87f2-df6fdcb5a88c">
</p>

### 2. Análise de Gols
Para essa análise, foi utilizado o dataset denominado df_gols. Nele há informações sobre o Campeonato Brasileiro na Era dos Pontos Corridos a partir de 2014.

Como exemplo, Palmeiras, Atlético-MG e Flamengo, campeões das edições de 2022, 2021 e 2020, respectivamente, são os clubes que mais balançaram as redes entre 2014 e 2022.
<p align="center">
  <img alt="Gols Times" width="80%" src="https://github.com/HenriqueWF/Serie_A_Campeonato_Brasileiro/assets/86746927/dbc97e01-c49b-4dd3-964b-292f2c2a24a4">
</p>

### 3. Análise de Cartões
Para essa análise, foi utilizado o dataset denominado df_cartoes. Nele há informações sobre o Campeonato Brasileiro na Era dos Pontos Corridos a partir de 2014.

Abaixo há um gráfico com a média dos clubes que mais receberam cartões vermelhos entre 2014 e 2022. Verificou-se que os clubes com melhor desempenho procuram evitar condutas que levem à expulsão de jogadores, enquanto que os times com menor sucesso tendem a se envolver em situações mais turbulentas, resultando em um maior número de cartões vermelhos.
<p align="center">
  <img alt="Cartões Vermelhos" width="80%" src="https://github.com/HenriqueWF/Serie_A_Campeonato_Brasileiro/assets/86746927/32d44360-13b3-46dc-93c6-a68ed300efdc">
</p>

### Bônus - Bar Chart Race
No estudo, fiz um "Bar Chart Race" que acompanha a evolução dos clubes com base na pontuação de uma temporada específica. Pode verificar o gráfico e alterar o ano no estudo completo. 

Quero aprimorá-lo posteriormente, de modo que apareça todas as temporadas, bem como as rodadas e informações adicionais.

<p align="center">
  <img alt="Cartões Vermelhos" width="70%" src="https://github.com/HenriqueWF/Serie_A_Campeonato_Brasileiro/assets/86746927/55a4bdce-55af-4a02-9930-b46ec4f42a90">
</p>

## Meus Artigos Relacionados ao Estudo
 - [**Matplotlib e Storytelling com Dados - Pt. I**](https://medium.com/data-hackers/matplotlib-e-storytelling-com-dados-pt-i-48c289943d60)
 - [**Matplotlib e Storytelling com Dados - Pt. II**](https://medium.com/data-hackers/matplotlib-e-storytelling-com-dados-pt-ii-35e0da269a1e)

## Contato
Estou sempre aberto para sugestões e melhorias do trabalho! 

**Links para me acharem:**
* [LinkedIn](https://www.linkedin.com/in/henriquewfranco/)
* [Kaggle](https://www.kaggle.com/henriquewfranco)
* [Medium](https://medium.com/@henriquewfranco)
* [GitHub](https://github.com/HenriqueWF)
