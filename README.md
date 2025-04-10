# Projeto de Análise de Score de Clientes - Aula 3 da Jornada Python

## Descrição

Este projeto tem como objetivo realizar uma análise de score de clientes em um banco utilizando Python e técnicas de Inteligência Artificial. Através de uma base de dados com 100.000 clientes, o projeto visa prever se um cliente é considerado bom ou não, com base em seu score de crédito.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Scikit-learn**: Biblioteca para machine learning e modelagem preditiva.

## Etapas do Projeto

1. **Importação da Base de Dados**: Carregar os dados utilizando a biblioteca Pandas.
2. **Verificação de Dados Vazios**: Identificar e tratar valores ausentes na base de dados.
3. **Tratamento de Dados**: Converter colunas de texto em valores numéricos utilizando `LabelEncoder`.
4. **Seleção de Colunas**: Escolher as colunas relevantes para o treinamento do modelo.
5. **Treinamento de Modelos**: Treinar dois modelos de classificação:
   - Árvore de Decisão
   - KNN (K-Nearest Neighbors)
6. **Avaliação de Modelos**: Comparar a acurácia dos modelos treinados.
7. **Identificação de Características Importantes**: Analisar quais características influenciam o score de crédito.

## Resultados

- O modelo de Árvore de Decisão apresentou uma acurácia de 82%, enquanto o modelo KNN teve uma acurácia de 73%.
- As características mais importantes para definir o score de crédito foram identificadas, incluindo `divida_total`, `mix_credito` e `juros_empréstimo`.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/LevyCostta/Python_InteligenciaArtificial_e_Previsoes.git
