# 📊 Previsão de Score de Crédito com Machine Learning

Este projeto foi desenvolvido para automatizar o processo de análise de crédito de clientes utilizando técnicas de **Ciência de Dados** e **Machine Learning**. Através de uma base de dados com 100 mil registros, o modelo identifica padrões e classifica o score de crédito em três categorias: **Poor**, **Standard** ou **Good**.

## 🚀 Objetivo
O foco principal foi criar um fluxo de dados (pipeline) que pudesse receber dados brutos de novos clientes e retornar uma previsão precisa, auxiliando na tomada de decisão financeira.

## 🛠️ Tecnologias e Bibliotecas
* **Python**: Linguagem base do projeto.
* **Pandas**: Utilizado para limpeza, manipulação e análise exploratória dos dados.
* **Scikit-Learn**: Biblioteca principal para a criação dos modelos de IA.
    * `LabelEncoder`: Para transformar variáveis categóricas (texto) em formatos numéricos.
    * `Train_test_split`: Para garantir que o modelo fosse testado com dados que ele nunca viu.
    * `RandomForestClassifier`, `KNeighborsClassifier`, `SGDClassifier`: Algoritmos testados para comparação de performance.

## 📈 Resultados obtidos
Para garantir a melhor entrega, comparei três modelos diferentes. Os resultados de acurácia foram:

| Modelo | Acurácia |
| :--- | :--- |
| **Random Forest** | **~83.2%** 🏆 |
| KNN | ~75.0% |
| SGD Classifier | ~29.1% |

O modelo **Random Forest** foi o escolhido devido à sua alta performance e robustez ao lidar com as 25 variáveis da base de dados.

## 📋 Funcionalidades
1.  **ETL & Pré-processamento:** Limpeza de dados e conversão de strings para dados numéricos.
2.  **Treinamento:** Divisão de dados em 80% para treino e 20% para teste.
3.  **Comparação de Modelos:** Avaliação real de qual algoritmo resolve melhor o problema.
4.  **Predição de Novos Clientes:** Script pronto para ler um novo arquivo CSV e gerar classificações automáticas.

---
*Este projeto demonstra minhas habilidades em lógica de programação, manipulação de grandes bases de dados e aplicação prática de Inteligência Artificial.*
