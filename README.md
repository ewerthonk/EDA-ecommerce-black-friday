# 🔬 Análise de vendas de um E-commerce na Black Friday
---
**Projeto do Módulo 04 do Degree de Data Science da Let's Code**

## 👨‍💻 Autores
-🕵🏻‍♂️[Ewerthon José Kutz.](https://github.com/ewerthonk/)
-🕵🏻‍♂️[Vitor Jacques.](https://github.com/VitorJacques)
-🕵🏻‍♂️[Cyro Rocha.](https://github.com/mytrael/)

## 👨🏻‍🏫 Descrição
O desafio entrega uma base de dados contendo as informações sobre a última Black Friday de um E-Commerce. A base de dados está quebrada em diferentes arquivos e deve-se entender como cada um se relaciona com o outro.

Com a base preparada, ela será utilizada para praticar exploração analítica e a biblioteca Pandas.

Dataset final: 

| Coluna                 | Descrição                                                 |
|:-----------------------|:----------------------------------------------------------|
| User_ID                | ID do usuário                                             |
| Product_ID             | ID do produto                                             |
| Gender                 | Sexo do usuário                                           |
| Age                    | Ano em intervalos                                         |
| Occupation             | Ocupação (mascarada)                                      |
| City_Category          | Categoria da cidade (A, B, C)                             |
| StayInCurrentCityYears | Número de anos de permanência na cidade atual             |
| Marital_Status         | Estado civil                                              |
| Product_Category_1     | Categoria do produto (Mascarada)                          |
| Product_Category_2     | Categoria que o produto pode pertencer também (Mascarada) |
| Product_Category_3     | Categoria que o produto pode pertencer também (Mascarada) |
| Purchase               | Valor da compra                                           |

## 💡 Conceitos utilizados

### 📕 No notebook "questions-ecommerce":

- Leitura, união, tratamento e exportação de bases de dados com Pandas.
- Manipulação e Extração de dados de um pd.Dataframe:
    - Limpeza.
    - Normalização.
    - Uso de Atributos.
    - Uso de Filtros.
    - Uso de Métodos.
    - Uso de "melting".
    - Uso de Pivot_Table.

### 📕 No notebook "exploratory-analysis-ecommerce":

- Análise exploratória da base de dados:
    - Correlação de variáveis com Seaborn e Matplotlib.
    - Apresentação de dados com pandas.groupby.