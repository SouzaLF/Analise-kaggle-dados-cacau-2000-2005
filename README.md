# 📊 Análise e Previsão de Preços de Cacau (2000-2005)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-orange)
![Scikit-learn](https://img.shields.io/badge/ScikitLearn-1.0%2B-green)
![Plotly](https://img.shields.io/badge/Plotly-5.0%2B-yellowgreen)
![Prophet](https://img.shields.io/badge/Facebook%20Prophet-1.1-blueviolet)

## 📊 Fonte dos Dados
Os dados utilizados neste projeto foram obtidos do Kaggle, uma plataforma conhecida por disponibilizar conjuntos de dados para análise. O dataset específico pode ser encontrado em:
🔗 [Agricultural Futures Dataset](https://www.kaggle.com/datasets/guillemservera/agricultural-futures/data) *(por [Guillem Servera](https://www.kaggle.com/guillemservera))*

## 📌 Visão Geral
Análise completa de séries temporais e modelo preditivo para preços históricos de cacau, demonstrando:
- Pré-processamento de dados financeiros
- Feature engineering temporal avançado
- Modelagem comparativa (ARIMA, Prophet, XGBoost)
- Técnicas de ensemble learning

## 💡 Insights de Negócio
- Padrão Sazonal: Preços tendem a cair 8-12% entre setembro-novembro (período de colheita)
- Volatilidade: Eventos extremos correlacionam com crises econômicas (2001, 2003)
- Recomendação: Hedge financeiro nos meses de maior volatilidade histórica

## 📚 Referências
- Hyndman, R.J. (2021) Forecasting: Principles and Practice
- Géron, A. (2022) Hands-On Machine Learning
- Documentação Prophet

## 📋 Estrutura do Código
```python
cocoa-price-analysis/
├── data/                   # Dados brutos e processados
│   ├── raw/               
│   └── processed/         
├── notebooks/              # Jupyter notebooks
│   ├── 1_EDA.ipynb        
│   ├── 2_Feature_Engineering.ipynb
│   └── 3_Modeling.ipynb    
├── src/                    # Código modularizado
│   ├── preprocessing.py   
│   ├── modeling.py        
│   └── visualization.py   
├── models/                 # Modelos treinados
├── outputs/                # Resultados e gráficos
└── README.md               # Este arquivo
