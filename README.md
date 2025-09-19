# **Checkpoint 02 - Projeto de Análise e Modelagem de Dados: Regressão e Classificação**


Este projeto explora duas frentes da **Ciência de Dados** e do **Aprendizado de Máquina (Machine Learning)** em Python:

  * **Regressão:** Previsão do consumo de energia de eletrodomésticos.
  * **Classificação:** Análise da estabilidade em uma rede elétrica inteligente.

O trabalho utiliza dados ambientais para prever o consumo de energia e dados de rede para classificar a estabilidade. Diferentes modelos de machine learning são aplicados e avaliados com métricas específicas para cada tarefa.

-----

## **Notebook do Projeto**

O código completo, a exploração dos dados e os modelos de Machine Learning estão disponíveis no notebook Python no Google Colab.

[Link do Python notebook no Colab]([https://www.google.com/search?q=https://colab.research.google.com/drive/...](https://colab.research.google.com/drive/1QS1T9J18vEeLufJRxHUaufJqSQpzS0SP?usp=sharing))

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

### **Parte 3: `SolarPrediction.csv`**

  * **Objetivo:** Este dataset foi utilizado para um exercício de classificação onde o objetivo era prever o nível de radiação solar.
  * **Tarefa:** Classificação.
  * **Variável Alvo:** Uma nova coluna, `Radiation_Level`, foi criada com base na mediana da variável `Radiation`, categorizando os dados em "High Radiation" ou "Low Radiation".

### **Parte 4: `T1.csv`**

  * **Objetivo:** Este dataset foi utilizado para um exercício de classificação onde o objetivo era a prever a potência gerada
(kW).
  * **Tarefa:** Classificação.

-----

## **Integrantes**

  *Felipe Krzyzanovski RM - 564878
  *Giovanni de Lela RM - 563066
  *Leonardo Lopes RM - 565437
  *Gabriel Nakamura RM - 562221
  *Murilo Godoy RM - 564840
  *Gisleine RM - 563804
