# 💳 Credit Card Fraud Detection (ML + Power BI)

Projeto de detecção de fraudes em cartões de crédito utilizando Machine Learning e visualização de dados com Power BI.

## 🚀 Objetivo
Identificar transações fraudulentas e comparar o desempenho de diferentes modelos de classificação, considerando o trade-off entre detecção de fraude e falsos positivos.

## 🧠 Modelos utilizados
- Logistic Regression
- Random Forest

## ⚙️ Tecnologias
- Python (Google Colab)
- Scikit-learn
- Power BI
- Dataset: Kaggle (Credit Card Fraud Detection)

## 🔎 Principais insights
- Apenas **0,2% das transações** são fraudes (base altamente desbalanceada)
- Transações fraudulentas possuem, em média, valores mais altos
- **Logistic Regression** detecta mais fraudes, porém com muitos falsos positivos
- **Random Forest** apresenta maior precisão (~96%) e menos falsos positivos, porém deixa passar mais fraudes

## 📊 Dashboard
O dashboard foi desenvolvido no Power BI para facilitar a análise comparativa entre os modelos e visualização dos principais indicadores.

## 🔗 Acesse o projeto
- Google Colab: https://colab.research.google.com/drive/16XkaP_cDWfQr5jyCBrdJY4p1h_9UMMgS?usp=sharing
- GitHub: https://github.com/GabrielProzin/credit-card-fraud-detection-ml-bi

## 📁 Arquivos do projeto
- `FraudeCartaoPowerBI.pbix` → Dashboard no Power BI
- `resultado_modelo.csv` → Base com resultados das previsões
- Notebook → Treinamento dos modelos (Google Colab)

## 📌 Conclusão
A escolha do modelo ideal depende do contexto de negócio, equilibrando a detecção de fraudes e a experiência do cliente.

---

💡 Projeto desenvolvido para consolidar conhecimentos em Machine Learning e análise de dados.
