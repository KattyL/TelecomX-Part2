# TelecomX-Part2

# Previsão de Churn — TelecomX

## Contexto

Este projeto é a segunda etapa de uma análise de cancelamento de clientes para a empresa fictícia **TelecomX**. O objetivo principal é desenvolver um modelo preditivo que antecipe quais clientes têm maior probabilidade de cancelar seus serviços, permitindo que a empresa atue de forma estratégica para prevenir perdas e fortalecer o relacionamento com o cliente.

A previsão de churn é um dos principais desafios para empresas de telecomunicações, impactando diretamente a receita recorrente. Antecipar quais clientes estão em risco de sair permite a implementação de ações preventivas mais eficazes.

O projeto busca responder a perguntas estratégicas:
* Quem são os clientes com maior risco de evasão?
* Quais variáveis mais influenciam esse comportamento?
* Que tipo de perfil a empresa precisa manter mais próximo?

---

## Objetivo

O principal objetivo é construir, avaliar e selecionar o melhor modelo de machine learning para prever o churn. A previsão é de uma classificação binária, com foco na capacidade de generalização do modelo utilizando validação cruzada.

---

## Etapas do Projeto

O desenvolvimento deste projeto seguiu uma metodologia estruturada, incluindo as seguintes etapas:
1.  **Exploração e Preparação dos Dados:** Análise de qualidade e estrutura dos dados, tratamento de colunas irrelevantes e diagnóstico do desbalanceamento da variável-alvo.
2.  **Engenharia e Análise de Variáveis:** Criação de novos atributos, agrupamento de variáveis categóricas e identificação de correlações importantes.
3.  **Transformações para Modelagem:** Codificação de variáveis categóricas e normalização de variáveis numéricas para preparar o conjunto de dados para os modelos.
4.  **Treinamento de Modelos Preditivos:** Aplicação de diferentes modelos, como Regressão Logística, Random Forest e XGBoost, com o uso de técnicas para lidar com o desbalanceamento dos dados.
5.  **Avaliação e Explicação dos Modelos:** Avaliação do desempenho dos modelos usando métricas como ROC-AUC, F1-Score, Matriz de Confusão e Curva Precision-Recall. Análise da importância das variáveis (feature importance) para interpretar os perfis de risco de churn.
6.  **Conclusão Estratégica:** Síntese dos resultados para identificar os perfis de clientes críticos, os fatores-chave para a evasão e a elaboração de recomendações práticas para a retenção.

---

## Resumo dos Resultados

* **Modelos testados:** Regressão Logística, Decision Tree, Random Forest, XGBoost, Gradient Boosting, KNN, entre outros.
* **Modelo final escolhido:** `Regressão Logística`
* **Principais métricas do modelo final:**
    * AUC: 0.82
    * Recall: 0.80
    * Precision: 0.49
    * F1-Score: 0.61
O modelo final demonstrou um `Recall` relevante, o que é crucial para identificar o maior número possível de clientes que efetivamente irão cancelar.

