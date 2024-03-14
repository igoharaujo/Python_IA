<div align=center>

# Projeto: Análise de Score de Crédito com IA

</div>

Para este projeto, usei as bases de dados fictícias [clientes.csv](/codigo.ipynb) e [novos_clientes.csv](/codigo.ipynb).

Este código foi desenvolvido no Jupyter Notebook e utiliza as seguintes bibliotecas:

- **Pandas**: Para manipulação e análise de dados.
- **Scikit-learn**: Para construção e avaliação de modelos de Machine Learning.



<div align=center>

## Passo a Passo do Projeto

</div>

### 1. Entendendo o Desafio da Empresa

A tarefa é criar um modelo de IA que analise o score de crédito dos clientes e os classifique nas categorias Good, Standard ou Poor.

### 2. Importando a Base de Dados

O código importa os dados dos clientes do arquivo CSV `clientes.csv`.

### 3. Preparando a Base de Dados para a IA

Os dados categóricos são convertidos em numéricos usando o Label Encoder para as colunas 'profissao', 'mix_credito' e 'comportamento_pagamento'.

### 4. Criando um Modelo de IA

São criados dois modelos de classificação: Random Forest Classifier e K-Nearest Neighbors Classifier.

### 5. Escolhendo o Melhor Modelo

Não está explícito no código fornecido.

### 6. Utilizando a IA para Fazer Previsões

- Os modelos são testados usando dados de teste e suas precisões são calculadas.
- Os dados dos novos clientes do arquivo `novos_clientes.csv` são importados e preparados.
- O modelo de Árvore de Decisão é utilizado para fazer previsões sobre os novos clientes.
- 
<div align=center>

## Exemplo:

</div>

Suponha que temos um arquivo CSV chamado `clientes.csv` com informações sobre clientes, incluindo sua profissão, mix de crédito e comportamento de pagamento. E um arquivo chamado `novos_clientes.csv` contendo informações sobre novos clientes para os quais desejamos fazer previsões.

Após importar e preparar os dados do arquivo `clientes.csv`, o modelo é treinado usando dois algoritmos diferentes: Random Forest Classifier e K-Nearest Neighbors Classifier. Em seguida, esses modelos são testados usando dados de teste e suas precisões são calculadas.

Posteriormente, o modelo de Árvore de Decisão é usado para fazer previsões sobre os novos clientes fornecidos no arquivo `novos_clientes.csv`. As previsões indicarão os possíveis scores de crédito (Good, Standard, Poor) para os novos clientes com base nos dados fornecidos.



<div align=center>


## Redes

|  [![Linkedin](/1_img/icone-linkedin.png)](https://www.linkedin.com/in/igor-ferreira-desenvolvedor/)| [![Instagram](/1_img/icone-instagram.png)](https://www.instagram.com/igoh_araujo/) 
|-----------|-----------|

</div>
