# **Checkpoint 02 - Análise de Dados de Consumidores de Energia**

Este é um projeto que visa analisar dados de consumidores de energia utilizando tecnicas de: -Data Science - Machine Learning (em python) -Orange Data Mining

# Link do Python notebook no collab 

https://colab.research.google.com/drive/1QS1T9J18vEeLufJRxHUaufJqSQpzS0SP?usp=sharing]
\#Informações detalhadas do dataset

  * Nome: Individual Household Electric Power Consumption

  * URL do Repositório: [https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)

  * Resumo: Contém medições de consumo de energia elétrica em uma residência com taxa de amostragem de um minuto ao longo de quase 4 anos (Dezembro de 2006 a Novembro de 2010). Inclui várias quantidades elétricas e valores de sub-medição.

  * Área: Física e Química

  * Tarefas: Regressão, Agrupamento (Clustering)

  * Características: Multivariada, Série Temporal

  * Número de Instâncias: 2.075.259

  * Número de Atributos: 9

  * Tipo de Atributos: Real

  * Valores Ausentes: Sim (quase 1.25% das linhas, representados pela ausência de valor entre delimitadores)

  * Ano de Criação: 2006

  * Informações das Variáveis:

  * Date: Data no formato dd/mm/yyyy

  * Time: Hora no formato hh:mm:ss

  * Global\_active\_power: Potência ativa global média por minuto da residência (em kilowatt)

  * Global\_reactive\_power: Potência reativa global média por minuto da residência (em kilowatt)

  * Voltage: Tensão média por minuto (em volt)

  * Global\_intensity: Intensidade de corrente global média por minuto da residência (em ampère)

  * Sub\_metering\_1: Sub-medição de energia No. 1 (cozinha) (em watt-hour)

  * Sub\_metering\_2: Sub-medição de energia No. 2 (lavanderia) (em watt-hour)

  * Sub\_metering\_3: Sub-medição de energia No. 3 (aquecedor de água elétrico e ar condicionado) (em watt-hour)

# Integrantes

  * **Felipe Krzyzanovski RM - 564878**
  * **Giovanni de Lela RM - 563066**
  * **Leonardo Lopes RM - 565437**
  * **Gabriel Nakamura RM - 562221**
  * **Murilo Godoy RM - 564840**
  * **Gisleine RM - 563804**
     

Com base no conteúdo do notebook, o README deve ser alterado para refletir um projeto que aborda dois temas principais: **Regressão** para prever o consumo de energia de eletrodomésticos e **Classificação** para determinar a estabilidade de uma rede elétrica inteligente. O texto também deve incluir informações sobre o dataset `SolarPrediction.csv` e a criação de uma variável de radiação.

-----

# **README.md**

# **Projeto de Análise e Modelagem de Dados: Regressão e Classificação**

Este projeto explora duas frentes da **Ciência de Dados** e do **Aprendizado de Máquina (Machine Learning)** em Python:

  * **Regressão:** Previsão do consumo de energia de eletrodomésticos.
  * **Classificação:** Análise da estabilidade em uma rede elétrica inteligente.

O trabalho utiliza dados ambientais para prever o consumo de energia e dados de rede para classificar a estabilidade. Diferentes modelos de machine learning são aplicados e avaliados com métricas específicas para cada tarefa.

-----

## **Notebook do Projeto**

O código completo, a exploração dos dados e os modelos de Machine Learning estão disponíveis no notebook Python no Google Colab.

[Link do Python notebook no Colab](https://www.google.com/search?q=https://colab.research.google.com/drive/...)

-----

## **Datasets Utilizados**

### **Parte 1: Regressão - `energydata_complete.csv`**

  * **Objetivo:** Prever o consumo de energia de eletrodomésticos (`Appliances`) com base em variáveis ambientais (temperatura, umidade, pressão, etc.).
  * **Tarefa:** Regressão.
  * **Modelos Testados:** Regressão Linear, Árvore de Regressão, Random Forest.
  * **Métricas de Avaliação:** R², RMSE, e MAE.

### **Parte 2: Classificação - `smart_grid_stability_augmented.csv`**

  * **Objetivo:** Classificar a estabilidade da rede elétrica (`stabf`) com base em dados da rede.
  * **Tarefa:** Classificação.
  * **Modelos Testados:** Árvore de Decisão, KNN, e Regressão Logística.
  * **Métricas de Avaliação:** Acurácia, Matriz de Confusão, e F1-score.

### **Dataset Adicional: `SolarPrediction.csv`**

  * **Objetivo:** Este dataset foi utilizado para um exercício de classificação onde o objetivo era prever o nível de radiação solar.
  * **Tarefa:** Classificação.
  * **Variável Alvo:** Uma nova coluna, `Radiation_Level`, foi criada com base na mediana da variável `Radiation`, categorizando os dados em "High Radiation" ou "Low Radiation".

-----

## **Integrantes**

  *Felipe Krzyzanovski RM - 564878
  *Giovanni de Lela RM - 563066
  *Leonardo Lopes RM - 565437
  *Gabriel Nakamura RM - 562221
  *Murilo Godoy RM - 564840
  *Gisleine RM - 563804
