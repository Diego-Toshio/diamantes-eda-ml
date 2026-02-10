# Análise Exploratória e Modelagem Preditiva de Preços de Diamantes

## 📌 Contexto
O preço de diamantes é influenciado por diversas características físicas
e qualitativas, como peso, corte, cor e pureza.
Este projeto tem como objetivo analisar esses fatores e desenvolver
modelos de Machine Learning para estimar o preço dos diamantes.

## 🎯 Objetivo
Realizar uma Análise Exploratória de Dados (EDA) e aplicar diferentes
modelos de Machine Learning para prever o preço de diamantes,
comparando abordagens e avaliando seu desempenho.

## 📊 Dataset
O dataset contém informações sobre diamantes, incluindo:
- Peso (`carat`)
- Qualidade do corte (`cut`)
- Cor (`color`)
- Pureza (`clarity`)
- Dimensões e proporções
- Preço (`price`)

Fonte dos dados:
- Repositório público (FIAP):  
  https://github.com/diogenesjusto/FIAP/blob/9837b368c45359bc2c36863cf3622a4d784790b4/Gradua%C3%A7%C3%A3o/dados/diamonds.csv

## 🧠 Abordagem
- Análise Exploratória de Dados (EDA)
- Pré-processamento dos dados
- Codificação de variáveis categóricas (One-Hot Encoding)
- Treinamento de modelos de regressão
- Validação com K-Fold Cross-Validation
- Comparação de desempenho entre modelos

## 🤖 Modelos Utilizados
- Regressão Linear
- Random Forest Regressor
- XGBoost Regressor

## 📈 Resultados
Os modelos baseados em árvores apresentaram melhor desempenho
em relação ao modelo linear, evidenciando a capacidade de capturar
relações não lineares entre as características dos diamantes e o preço.

## 🛠️ Tecnologias
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## 📁 Estrutura do Repositório
diamantes-eda-ml/
- Diamantes_EDA_ML_Profissional.ipynb
- README.md

## 📌 Observações
Este projeto demonstra um pipeline completo de Data Science,
desde a análise exploratória até a comparação de modelos preditivos.
