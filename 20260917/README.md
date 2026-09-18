# Atividade Prática:  classificação com SVM (Support Vector Machine)
---
"Dando continuidade aos nossos estudos práticos de Aprendizado de Máquina, nesta atividade vamos implementar e avaliar modelos de Support Vector Machines (SVM) para a tarefa de diagnóstico/classificação binária utilizando dados biomédicos reais."

#### Contexto do Dataset
*As características foram computadas a partir de imagens digitalizadas de biópsias por aspiração com agulha fina (FNA) de massas mamárias e descrevem aspectos dos núcleos celulares presentes na imagem. O objetivo é classificar os tumores em Malignos (M) ou Benignos (B).*

## Objetivo
1. ### Exploração e Pré-processamento:
- Realizar o carregamento e limpeza inicial dos dados (remoção de identificadores irrelevantes como id e tratamento de colunas vazias, se houver).
- Codificar a variável alvo (diagnosis).
- Atenção: Como o SVM é sensível à escala dos dados, realize a padronização/normalização dos atributos (ex.: StandardScaler). Buscar informações em fontes confiáveis sobre a padronização do tipo.
2. ### Modelagem com SVM:
- Separar o conjunto em treino e teste.
- Treinar modelos SVM testando diferentes funções de kernel (linear e RBF).
- Ajustar hiperparâmetros essenciais (como C e gamma).

## Links
- [Dataset Utilizado](http://kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- [Notebook desenvolvido](https://www.kaggle.com/code/victorfernandes2020/svc-breast-cancer-wisconsin-victorfernandesa6)
