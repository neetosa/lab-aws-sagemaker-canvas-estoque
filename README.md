# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Este projeto envolve a utilização do SageMaker Canvas da AWS para realizar previsões de preços de produtos com base em uma base de dados. Utilizando técnicas de Machine Learning, o SageMaker Canvas foi empregado para construir modelos preditivos que ajudam a prever os preços futuros dos produtos.

# 🎯 Objetivos

- **Análise de Desempenho**: Avaliar a precisão e a eficácia dos modelos preditivos gerados.

- **Previsão de Preços**: Utilizar a base de dados para treinar modelos preditivos capazes de estimar os preços dos produtos.

- **Geração de Insights**: Fornecer insights valiosos para a tomada de decisões com base nas previsões de preços.

# 🚀 Passo a Passo

## 1. Selecionar Dataset

-   Foi utilizado o dataset 'dataset-1000-com-preco-variavel-e-renovacao-estoque.csv'. Que está na pasta de dataset

## 2. Análise de Desempenho

- Avg. wQL = 0.065

- MAPE = 0.111

- WAPE = 0.108

- RMSE = 1.678

- MASE = 0.847

## 3. Previsão de Preços

- Produto 13:
[![duRU5HF.md.jpg](https://iili.io/duRU5HF.md.jpg)](https://freeimage.host/i/duRU5HF)

Podemos observar três possivéis casos:
    1. Vermelho: Caso menos otimista, apresenta uma baixa no valor do produto. Significando um queda no lucro, porém um bom indicativo para compra de estoque.

    2. Azul: Caso padrão, apresenta um pequeno aumento no valor do produto. Significando um leve aumento no lucro e uma oportunidade razoavel para compra de estoque.

    3. Amarelo: Caso mais otimista, apresenta um aumento significativo no valor do produto. Sugere um bom aumento no lucro, porém não é indicado compras para estoque.
