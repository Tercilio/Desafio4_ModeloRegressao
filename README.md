Construindo um Modelo de Regressão para Marketing

I - Contexto: 
  Este projeto foi desenvolvido como parte de um desafio no curso de Formação em Ciência de Dados. O objetivo era aplicar técnicas de regressão para analisar um dataset de campanhas de marketing e construir um modelo preditivo que estimasse o retorno de vendas baseado     em investimentos em publicidade.
  A empresa fictícia utilizada no desafio investe mensalmente em plataformas de publicidade online, como YouTube, Facebook e jornal, e deseja entender a relação entre esses investimentos e os retornos de vendas gerados. Com isso, pretende-se identificar os fatores que     mais impactam na geração de leads e criar um modelo de predição de valores.

II - Estrutura do Projeto
  O projeto está dividido nas seguintes etapas:

  1. Análise Descritiva
    Nesta etapa, realizamos uma exploração inicial dos dados para obter uma compreensão geral das variáveis e suas distribuições. As ações incluem:

    * Descrição estatística das variáveis
    * Identificação de valores ausentes ou inconsistentes
  
  2. Análise Exploratória
    A análise exploratória busca investigar mais a fundo as relações entre as variáveis, identificando correlações e padrões que possam informar a modelagem preditiva. As ações incluem:

    * Visualização de correlações entre variáveis
    * Análise de dispersão para identificar relações lineares
    
  3. Modelagem
    Nesta etapa, desenvolvemos e treinamos um modelo de regressão para prever os retornos de vendas a partir dos investimentos em publicidade. As ações incluem:

    * Divisão dos dados em conjuntos de treinamento e teste
    * Treinamento de modelos de regressão linear
    * Avaliação do desempenho dos modelos
  4. Predição
    Utilizamos o modelo treinado para realizar previsões sobre novos dados de investimento e avaliamos o desempenho preditivo. As ações incluem:

    * Predição dos retornos de vendas para novos investimentos
    * Cálculo de métricas de desempenho, como RMSE e R²


III - Requisitos
  Para executar o projeto, é necessário ter instalado:

    * Python 3.x
    * Jupyter Notebook
    * Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn
