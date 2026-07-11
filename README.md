# 📊 Análise e Previsão de Inadimplência de Clientes de Cartão de Crédito

## 📌 Sobre o projeto

Este projeto tem como objetivo desenvolver modelos de Machine Learning capazes de prever a inadimplência de clientes de cartão de crédito, utilizando informações demográficas, financeiras e do histórico de pagamentos.

Além da construção dos modelos preditivos, o projeto contempla todas as etapas de um fluxo de Ciência de Dados, incluindo entendimento do problema de negócio, preparação dos dados, análise exploratória, treinamento, avaliação e comparação de modelos.

---

## 🎯 Problema de negócio

Instituições financeiras enfrentam desafios para identificar clientes com maior risco de inadimplência. Uma previsão antecipada permite reduzir perdas financeiras, apoiar a concessão de crédito e aprimorar estratégias de gerenciamento de risco.

Este projeto busca responder à seguinte pergunta:

> **É possível prever quais clientes possuem maior probabilidade de se tornarem inadimplentes no próximo mês?**

---

## 👥 Público-alvo

- Bancos
- Instituições financeiras
- Empresas de cartão de crédito
- Analistas de Risco
- Cientistas e Analistas de Dados

---

## 📂 Base de dados

- **Fonte:** UCI Machine Learning Repository
- **Registros:** 30.000 clientes
- **Variáveis:** 25 atributos
- **Tipo de problema:** Classificação Binária

A variável alvo indica se o cliente será ou não inadimplente no mês seguinte.

---

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab

---

## 📈 Etapas do projeto

- Compreensão do problema de negócio
- Conhecimento dos dados
- Preparação dos dados
- Análise Exploratória (EDA)
- Construção do modelo Random Forest
- Construção do modelo XGBoost
- Comparação entre modelos
- Conclusão

---

## 🤖 Modelos desenvolvidos

- Random Forest
- XGBoost

---

## 📊 Principais resultados

- O modelo **Random Forest** apresentou o melhor desempenho geral.
- Acurácia aproximada de **81,5%**.
- O histórico recente de pagamentos foi o principal fator para previsão da inadimplência.
- As variáveis **PAY_0**, **PAY_2**, **PAY_5**, **PAY_4** e **PAY_3** foram as mais relevantes para o modelo.

---

## 📁 Estrutura do repositório

```text
📦 credit_risk_analysis_and_default_prediction

├── Credit_Card_Default_Prediction.ipynb
├── UCI_Credit_Card.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Como executar

1. Clone este repositório.

```bash
git clone https://github.com/SEU-USUARIO/credit_risk_analysis_and_default_prediction.git
```

2. Instale as dependências.

```bash
pip install -r requirements.txt
```

3. Abra o notebook no Jupyter Notebook ou Google Colab.

---

## 📌 Principais insights

- O histórico recente de pagamentos é o principal indicador de inadimplência.
- Variáveis relacionadas ao limite de crédito e valores das faturas também influenciam a previsão.
- A comparação entre os modelos demonstrou desempenho semelhante, com vantagem para o Random Forest.

---

## 👩‍💻 Autora

**Andria Roza**
