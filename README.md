# Desafio Técnico - Ciência de Dados (Programa LIGHTHOUSE - Indicium Academy)

Este repositório contém a solução do desafio técnico para previsão de preços de aluguel de imóveis em Nova York, utilizando técnicas estatísticas e de machine learning.

## Objetivo do Projeto
O objetivo é criar um modelo preditivo capaz de estimar o preço de aluguel com base nas características dos imóveis listados.

## Estrutura do Repositório
- "LH_CD_ROBERIO.ipynb" → Notebook contendo o relatório das analises estatisticas e EDA, modelagem e avaliação dos modelos.
- "melhor_modelo.pkl" → Arquivo do modelo final salvo para previsões futuras.
- "teste_indicium_precificacao.csv" → Base de dados utilizada no projeto.
- "requirements.txt" → Lista de pacotes python utilizados e suas versões para rodar o projeto.

## Como Rodar o Projeto
1. Clone o repositório:
git clone https://github.com/EngRoberio/desafio_tecnico_LH_CD_ROBERIO.git
cd desafio_tecnico_LH_CD_ROBERIO

2. Crie um ambiente virtual (opcional)
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Linux/macOS

3. Instale as dependências:
pip install -r requirements.txt


4. Execute o Jupyter Notebook e abra o arquivo `LH_CD_ROBERIO.ipynb` para rodar o código.


## METODOLOGIA
O projeto seguiu as seguintes etapas:
   * Etapa 1: Carregamento dos Dados → Compreensão inicial do dataset e das variáveis;
   * Etapa 2: Análise Exploratória dos Dados (EDA) → Identificação de padrões e inconsistências nos dados;
   * Etapa 3: Pré-processamento → Tratamento de outliers e valores ausentes/inconsistentes;
   * Etapa 4: Engenharia de Atributos → Criação de novas variáveis e codificação das variáveis categóricas;
   * Etapa 5: Modelagem Preditiva → Treinamento de diversos modelos de regressão (Regressão Linear, Ridge, Lasso, Random Forest, Gradient Boosting e Stacking Regressor);
   * Etapa 6: Avaliação dos Modelos → Comparação de métricas como 'MAE', 'RMSE' e 'R²', definindo o melhor modelo como aquele de maior 'R²' (aquele que explica mais a variabilidade dos dados, ou seja, o de melhor capacidade preditiva).

## Resultado Final
O modelo "Stacking Regressor" foi o que apresentou melhor desempenho, sendo o escolhido para prever os preços de aluguel.

## Contato
* Email: engenheirojoseroberio@gmail.com  
* GitHub: [EngRoberio](https://github.com/EngRoberio)

