# Telecom X - Parte 2: Previsão de Churn

Este projeto faz parte do desafio Telecom X, onde meu objetivo foi construir modelos preditivos para identificar clientes com maior risco de cancelar seus serviços (churn).

## Descrição

Neste desafio, desenvolvi um pipeline completo de Machine Learning para previsão de churn, que incluiu:

- Pré-processamento dos dados (limpeza, codificação das variáveis categóricas, balanceamento)
- Divisão dos dados em treino e teste
- Treinamento de dois modelos de classificação:
  - Regressão Logística (com normalização)
  - Random Forest (sem necessidade de normalização)
- Avaliação dos modelos utilizando métricas como acurácia, precisão, recall, F1-score e ROC AUC
- Visualização da importância das variáveis para o modelo Random Forest
- Interpretação dos resultados para apoiar decisões estratégicas na retenção de clientes

## Dataset

Utilizei o dataset previamente tratado na Parte 1 do desafio, que contém informações sobre clientes, serviços contratados e se houve churn.

## Tecnologias

- Python 3  
- Pandas  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Matplotlib e Seaborn  
- Google Colab (ambiente de desenvolvimento)  

## Como usar

1. Faça upload do arquivo CSV limpo gerado na Parte 1 do desafio.  
2. Execute o notebook passo a passo para treinar e avaliar os modelos.  
3. Analise os resultados e a importância das variáveis para entender os fatores que influenciam a evasão.  

## Resultado esperado

Identificar clientes com maior probabilidade de churn para que a empresa possa tomar ações preventivas.

## Sobre mim

Meu nome é Mariana Melo e estou em processo de aprendizado e desenvolvimento na área de Ciência de Dados e Machine Learning.

