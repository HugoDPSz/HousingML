
# Previsão de Preços de Imóveis 🏡

Este projeto é baseado no conteúdo do livro **"Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras e TensorFlow"**, de Aurélien Géron. O objetivo principal é aplicar técnicas de aprendizado de máquina para **prever os preços de imóveis na Califórnia**, utilizando um conjunto de dados real e fluxos completos de machine learning, do pré-processamento à avaliação final do modelo.

## 📌 Objetivo

Desenvolver um pipeline de machine learning para:

- Analisar um dataset de preços de imóveis.
- Realizar limpeza e exploração dos dados.
- Construir e treinar modelos de regressão.
- Avaliar e melhorar o desempenho dos modelos.
- Fazer previsões com novos dados.

## 🧠 Técnicas e Conceitos Aplicados

- Exploração e visualização de dados com **Pandas**, **Matplotlib** e **Seaborn**.
- Engenharia de atributos e tratamento de dados faltantes.
- Divisão do dataset em treino/teste com **Stratified Sampling**.
- Construção de pipelines com o **Scikit-Learn**.
- Modelos de Regressão Linear, Árvore de Decisão, Floresta Aleatória e Redes Neurais.
- Ajuste de hiperparâmetros com **GridSearchCV**.
- Validação cruzada e análise de erros.

## 🗃️ Dataset

O dataset utilizado é o **California Housing Prices**, disponível via `fetch_california_housing()` do Scikit-Learn. Ele contém informações como:

- Latitude e longitude
- Média de renda dos residentes
- Número médio de quartos e dormitórios
- População da região
- Preço médio dos imóveis (target)

## 🛠️ Tecnologias e Bibliotecas

- Python 3.10+
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/previsao-precos-imoveis.git
   cd previsao-precos-imoveis
   ```

2. Crie um ambiente virtual e instale as dependências:
   ```bash
   python -m venv venv
   source venv/bin/activate  # ou venv\Scripts\activate no Windows
   pip install -r requirements.txt
   ```

3. Execute os notebooks no Jupyter:
   ```bash
   jupyter notebook
   ```

## 📈 Resultados Esperados

O modelo final, após otimizações, deve ser capaz de prever o valor médio dos imóveis com uma margem de erro razoável (avaliada por RMSE), demonstrando a eficácia do pipeline de machine learning construído.

## 📚 Referência

- Géron, A. (2020). **Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras e TensorFlow**. 2ª edição. O'Reilly.
