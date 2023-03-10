# Objetivo.
  Este projeto tem com objetivo principal fazer aplicação do meu primeiro algortimo de machine learning para predição de preço de abacates, com os conhecimentos adquiridos no curso que estou fazendo na coursera: https://www.coursera.org/specializations/machine-learning-introduction.

As habilidades exercitadas:
1. Importar dataset.
2. Tratamento de dados.
3. Visualização de dados.
4. Normalização.
5. Contruir modelo.
6. Avaliar o modelo.


# Fonte.

Os dados foram obtidos do kaggle: (https://www.kaggle.com/datasets/alanluo418/avocado-prices-20152019) 


# Descrição dos dados.


Columns in the dataset:

  Date - The date of the observation

  AveragePrice - The Average Sales Price of Current Year

  Total Volume - Total Bulk and Bags Units

  4046 - Total number of avocados with PLU 4046 sold

  4225 - Total number of avocados with PLU 4225 sold

  4770 - Total number of avocados with PLU 4770 sold

  type - conventional or organic

  year - the current year

  region - the city or region of the observation

  
# Organização do projeto.

``` sh
avocado_price_predicition
 ┣ data
 ┃ ┣ avocado.csv
 ┃ ┗ avocados_tratado.csv
 ┣ notebooks
 ┃ ┣ avocado_tratamento.ipynb
 ┃ ┗ eda_price_prediction.ipynb
 ┗ README.md
 ```

# Descrição dos arquivos.
  
* A pasta data contém dois datasets, o avocado.csv com os dados originais baixados do kaggle e outro avocados_trataos.csv que fiz o tratamento para a construção do modelo.
  
* A pasta notebooks contém dois arquivos, avocado_tratamento.ipynb este contém os códigos que utilizei para tratar os dados do dataset otiginal. A pasta eda_price_predicition.ipynb contém a análise exploratória e o modelo. 
