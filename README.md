# Análise de Eficiência Energética: Dataset Auto MPG (1970–1982)

## Visão Geral
Este projeto realiza uma análise exploratória de dados (EDA) sobre a evolução da eficiência de combustível na indústria automobilística entre 1970 e 1982. 
O objetivo principal é identificar como variáveis técnicas (peso, potência e cilindrada) influenciam o consumo, utilizando o dataset Auto MPG.

## Destaques do Projeto 
Práticas de ciência de dados aplicadas:
* **Engenharia de Atributos:** Criação da métrica `w/hp` (Razão Peso-Potência) para capturar a carga mecânica sobre o motor.
* **Normalização Internacional:** Conversão de MPG para o sistema métrico (km/L) para melhor interpretabilidade no contexto brasileiro.
* **Análise Multivariada:** Uso de matrizes de correlação e visualizações (Pairplots) para identificar agrupamentos de veículos.

## Tecnologias Utilizadas
* **Python** (Linguagem base)
* **Pandas** (Manipulação e limpeza de dados)
* **Seaborn & Matplotlib** (Visualização estatística avançada)

## Principais Insights
* **Segmentação por Motorização:** O número de cilindros é o maior preditor de comportamento; carros de 8 cilindros formam um grupo isolado de baixo rendimento e alta massa.
* **A Regra do Equilíbrio:** A economia de combustível não é ditada apenas pelo peso, mas pela relação entre peso e potência (`w/hp`).

