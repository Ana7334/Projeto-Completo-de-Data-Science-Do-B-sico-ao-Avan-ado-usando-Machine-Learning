# 📊 Projeto de Data Science e Machine Learning – Análise de Clientes

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo analisar o comportamento de clientes e aplicar técnicas de **Machine Learning** para:

* Prever o número de compras mensais (Regressão)
* Identificar se um cliente vai abandonar a empresa (Classificação – Churn)
* Segmentar clientes por comportamento (Clusterização – KMeans)

Dataset utilizado: **base fictícia criada para fins educacionais** com 500 registros.

---

## 🧠 Fluxo do Projeto (Etapas)

### ✅ 1. Criação do Dataset

Um dataset sintético foi criado contendo:

* Idade
* Renda mensal
* Score de gastos
* Compras mensais (variável de regressão)
* Churn (variável de classificação)

> Esses dados simulam um cenário real de análise de clientes.

---

### ✅ 2. Análise Exploratória (EDA)

* Visualização de distribuição de variáveis
* Estatísticas descritivas
* Verificação de valores ausentes

Exemplo de insights:

* Clientes com maior score de gastos tendem a fazer mais compras no mês.
* Existe relação entre gastos e chance de churn.

---

### ✅ 3. Modelagem – Machine Learning

Foram treinados modelos para cada objetivo:

#### 🔹 Regressão (previsão de compras)

Modelo utilizado: **Regressão Linear**

#### 🔹 Classificação (previsão de churn)

Modelos utilizados:

* Decision Tree
* Random Forest
* Rede Neural (MLPClassifier)

> O modelo com melhor desempenho foi o **Random Forest**.

#### 🔹 Clusterização (segmentação de clientes)

Modelo: **KMeans (k=3)**

> Grupou os clientes em 3 perfis (baixo gasto, médio, alto consumo).

---

### ✅ 4. Otimização do Melhor Modelo

Foi aplicado **GridSearchCV** para otimizar o Random Forest.

Resultado:

* Acurácia aumentou
* Melhor conjunto de hiperparâmetros foi encontrado automaticamente

---

## 📈 Principais resultados

* **Random Forest** apresentou a melhor acurácia para prever churn.
* A clusterização permitiu identificar perfis de clientes, útil para estratégias de marketing.
* Regressão ajudou a prever compras mensais com base em renda e comportamento.

| Técnica          | Objetivo               | Resultado                        |
| ---------------- | ---------------------- | -------------------------------- |
| Regressão Linear | Prever compras mensais | MSE baixo, bom ajuste            |
| Random Forest    | Classificação (churn)  | Melhor acurácia entre os modelos |
| KMeans           | Segmentação            | 3 grupos distintos de clientes   |

---

## 🛠 Tecnologias utilizadas

* Python
* Pandas / NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Google Colab

---

## 🚀 Como executar o projeto

1. Baixe o notebook `.ipynb`
2. Faça upload no Google Colab
3. Carregue o CSV do dataset
4. Rode as células na ordem

---

## 📂 Estrutura do Projeto

```
📁 Projeto-DataScience-Churn
│── projeto_data_science_completo.ipynb
│── dataset_analise_clientes.csv
│── README.md (este arquivo)
```

---

## 🧑‍💻 Autor(a)

**Ana Raquel** – Projeto para portfólio de Data Science e Machine Learning

---
> Este projeto demonstra do zero todo o processo: *explorar dados → modelar → otimizar → gerar insights de negócio*.


