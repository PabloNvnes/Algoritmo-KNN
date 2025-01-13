# Algoritmo-KNN

Este é um projeto simples e direto que utiliza o algoritmo K-Nearest Neighbors (KNN) para classificar a qualidade do vinho com base em suas características químicas.

## Descrição do Projeto

O objetivo deste projeto é explorar e aplicar o algoritmo KNN para prever a qualidade do vinho. Utilizamos um conjunto de dados de qualidade do vinho que contém várias características químicas e a qualidade do vinho como uma variável alvo.

## Estrutura do Projeto

- `main.ipynb`: O notebook Jupyter onde todo o código é executado. Inclui a exploração dos dados, visualizações, treinamento do modelo e avaliação.
- `README.md`: Este arquivo, que fornece uma visão geral do projeto.

## Passos do Projeto

1. **Importação de Bibliotecas**: Importamos as bibliotecas necessárias, como pandas, numpy, matplotlib, seaborn, e scikit-learn.
2. **Carregamento dos Dados**: Utilizamos a biblioteca `kagglehub` para baixar o conjunto de dados de qualidade do vinho.
3. **Exploração dos Dados**: Exploramos o conjunto de dados, visualizando as primeiras linhas, estatísticas descritivas, e a distribuição das variáveis.
4. **Visualização dos Dados**: Criamos gráficos para entender melhor as relações entre as variáveis e a variável alvo (qualidade do vinho).
5. **Pré-processamento dos Dados**: Dividimos os dados em conjuntos de treino e teste, e padronizamos as características.
6. **Treinamento do Modelo**: Utilizamos o algoritmo KNN para treinar o modelo com os dados de treino.
7. **Avaliação do Modelo**: Avaliamos o desempenho do modelo utilizando métricas como acurácia, precisão, recall e F1 score.
8. **Aprimoramento do Modelo**: Utilizamos `GridSearchCV` para encontrar os melhores parâmetros para o modelo KNN.
9. **Persistência do Modelo**: Salvamos o modelo treinado para uso futuro utilizando a biblioteca `joblib`.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/algoritmo-knn.git
   cd algoritmo-knn