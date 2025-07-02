# Análise e Predição do Valor do Bitcoin

## Descrição do Projeto

Este projeto tem como objetivo analisar e prever o preço do Bitcoin usando técnicas de regressão. Utilizando dados históricos, o modelo busca identificar padrões e fatores que influenciam o preço, oferecendo previsões para períodos futuros.

## Tabela de Conteúdos

- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Coleta de Dados](#coleta-de-dados)
- [Preparação dos Dados](#preparação-dos-dados)
- [Análise e Visualização](#análise-e-visualização)
- [Modelagem](#modelagem)
- [Resultados](#resultados)

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Plotly

## Coleta de Dados

Os dados foram coletados através da API do  [Yahoo Finance](https://finance.yahoo.com/). Os dados incluem informações como:

- Preço de abertura
- Preço de fechamento
- Preço máximo
- Preço mínimo
- Volume de transações

## Preparação dos Dados

- Remoção de dados ausentes e duplicados.
- Conversão de datas para o formato adequado.
- Criação de novas variáveis, como médias móveis e desvio padrão.

## Análise e Visualização

Foram realizadas análises descritivas e visualizações para entender a evolução do preço do Bitcoin ao longo do tempo. Gráficos de linha foram utilizados para identificar padrões.

## Modelagem

Utilizamos um modelo de regressão do Gradient Boosting Machine para prever o preço do Bitcoin. O conjunto de dados foi dividido em treinamento e teste para validar a eficácia do modelo. Métricas como R² e MSE foram utilizadas para avaliar o desempenho.

## Resultados

Os resultados mostram a precisão das previsões do modelo em comparação com os valores reais do Bitcoin. Gráficos ilustrativos foram gerados para demonstrar a performance.
