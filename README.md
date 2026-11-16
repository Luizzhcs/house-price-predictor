# House Price Predictor

Projeto de Machine Learning desenvolvido em Python para previsão de valores medianos de imóveis em regiões da Califórnia, utilizando o dataset California Housing.

## Objetivo

Desenvolver e comparar modelos de regressão para estimar valores de imóveis a partir de características socioeconômicas e geográficas das regiões.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Dataset

Foi utilizado o California Housing Dataset, disponibilizado pelo Scikit-learn.

O conjunto contém informações como:

- Renda mediana da região.
- Idade mediana das construções.
- Média de cômodos e quartos.
- População e ocupação.
- Latitude e longitude.
- Valor mediano dos imóveis.

## Desenvolvimento

O projeto seguiu as seguintes etapas:

1. Carregamento e exploração dos dados.
2. Separação das variáveis de entrada e da variável-alvo.
3. Divisão dos dados em conjuntos de treinamento (80%) e teste (20%).
4. Treinamento de modelos de regressão.
5. Realização de previsões.
6. Avaliação e comparação dos resultados.
7. Análise de overfitting e experimentação com hiperparâmetros.

## Modelos implementados

Foram utilizados dois algoritmos:

- Linear Regression
- Random Forest Regressor

## Resultados

O Random Forest apresentou o melhor desempenho no conjunto de teste.

| Modelo | MAE | R² |
|---|---:|---:|
| Linear Regression | 0.5332 | 0.5758 |
| Random Forest | **0.3277** | **0.8046** |

O Random Forest alcançou um erro absoluto médio aproximado de US$ 32.773.

## Como executar

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
```

Entre na pasta:

```bash
cd house-price-predictor
```

Crie e ative um ambiente virtual e instale as dependências:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

Inicie o Jupyter Notebook:

```bash
jupyter notebook
```

Abra `notebooks/analise_e_treinamento.ipynb` e execute as células.

## Observações

Este projeto possui finalidade educacional e demonstra um fluxo básico de desenvolvimento de modelos de Machine Learning. As previsões são estimativas baseadas nos dados disponíveis e não devem ser interpretadas como avaliações imobiliárias reais.