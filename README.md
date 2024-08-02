# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.


O dataset escolhiodo foi **dataset-500-curso-sagemaker-canvas-dio.csv**
## CONCLUSAO:

To analyze the data and create visualizations, I'll load the dataset, inspect it, and generate some plots. Let's start by examining the data.

The dataset contains 9,360 records and 6 columns:

date: The date of the record.
product_name: The name of the product.
category: The category of the product.
stock_quantity: The quantity of the product in stock.
unit_price: The price per unit of the product.
total_value: The total value of the product in stock.
Some observations include:

The date column's type is already in datetime format.
The product_name and category columns are object types, indicating categorical data.
The stock_quantity, unit_price, and total_value columns are numerical.
Next, I'll create visualizations to help understand the data, such as:

A time series of total stock value.
A breakdown of stock value by product category.
A comparison of stock quantity for the top products.
Let's proceed with these visualizations. ​​

Here are the visualizations based on the dataset:

Total Stock Value Over Time:

The total stock value fluctuates monthly, with notable peaks and troughs, indicating variability in stock value over time.
Total Stock Value by Product Category:

Categories with the highest total stock value are displayed, with some categories contributing more significantly than others to the total inventory value.
Top 10 Products by Stock Quantity:

The top 10 products with the highest stock quantity are shown, highlighting the most abundant items in the inventory.
