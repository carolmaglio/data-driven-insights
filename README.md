# Data Driven Insights: Análise de Vendas  

## Sobre o projeto
O projeto "Data Driven Insights: Análise de Vendas", foi um trabalho desenvolvido como parte do programa Desenvolve do Grupo Boticário e a Escola Koru.

O objetivo é explorar, transformar e visualizar dados com base em estruturas do Python e as principais bibliotecas como Pandas, Numpy e Matplotlib, gerando insights descritivos a partir da análise.

## Base de Dados

A base de dados utilizada é uma simulação de vendas e está disponível na plataforma [Kaggle](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data/code). Ele contém informações de pedidos, produtos, vendas, clientes e dados geográficos.

## Como rodar o Projeto no Google Colab

1. Baixe os arquivos

* Faça o download do notebook do projeto `data_driven_insights.ipynb`
* Base de dados `sales_data_sample.csv`

2. Acesse o Google Colab

* Vá em Arquivo > Fazer upload de notebook
* Selecione o arquivo do projeto (`.pynb`)

3. Faça upload da Base de Dados `.csv`

* No início do notebook, execute a célula abaixo para abrir o seletor de arquivos:
```
from google.colab import files
uploaded = files.upload()
```

* Selecione o arquivo `sales_data_sample.csv` baixado 


## Objetivos
* Leitura e Exploração Inicial da Base: Compreensão da estrutura da base de dados  e os tipos de dados presentes.
* Visualização dos Dados: Utilização de gráficos de linhas, barras e dispersão para compreender tendências e comparações.
* Relatório e Geração de Insights: Conclusões sobre a análise visual e descritiva.

## Tecnologias utilizadas
* Python - Linguagem de programação
* Google Colab - Ambiente de desenvolvimento
* Pandas - Análise e manipulação de dados
* Numpy - Operações numéricas
* Matplotlib - Criação e visualização dos dados
