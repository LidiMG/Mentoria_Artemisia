# Análise de Dados de Filmes de Horror

<div align="center">
  <img src="https://static1.colliderimages.com/wordpress/wp-content/uploads/2025/02/horrorexpress-edit.jpg?q=70&fit=crop&w=1100&h=618&dpr=1" alt="Texto Alternativo" />
</div>

## Introdução
Este projeto analisa dados de filmes de horror utilizando um banco de dados disponível através da plataforma Kaggle.

Fonte: \
**best horror movies** \
https://www.kaggle.com/datasets/bharatkumar0925/best-horror-movies?resource=download

## Motivação
Amo filmes de horror, principalmente os clássicos e mais antigos.

## Objetivo
Avaliar quais filmes de horror são mais populares e tem melhores avaliações, identificar diretores que mais produzem filmes bem como quais são mais populares e identificar roteiristas que mais escrevem filmes de horror assim como quais tem melhor avaliação.

## Instalação e Pré-Requisitos
Para executar o código, você precisará das seguintes bibliotecas Python:

```python
import pandas as pd
import sqlite3
import seaborn as sns
import matplotlib.pyplot as plt
from matplotlib.ticker import MaxNLocator
```

## Uso
* Clone este repositório para sua máquina local.
* Faça download do dataset "horror-movies.csv"
* Navegue até o diretório do projeto.
* Abra o arquivo `Horror_Movies.ipynb` em um ambiente Jupyter Notebook.
* Execute as células de código sequencialmente para carregar e analisar os dados.

## Estrutura dos Dados
Os dados são carregados a partir de um arquivo CSV:

```python
df_backup = pd.read_csv("horror-movies.csv")
```

Para evitar alterações no conjunto de dados original, uma cópia é feita:

```python
df = df_backup.copy()
```

## Análise Inicial

A análise inicial inclui a verificação da estrutura dos dados, verificação da integridade dos dados, presença de valores nulos e duplicatas, limpeza de dados e organização dos dados para análise.


## Lidando com Erros

Para impasses e correções de erros apontadas pelos códigos e aperfeiçoamento da execução foram feitas consultas à documentação do Python, Matplotlb e Seaborn e às IAs Perplexity e GhatGPT.

## Contribuições
Contribuições e sugestões são bem-vindas!