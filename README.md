\# Recommender System - MovieLens



Este projeto é um \*\*sistema de recomendação de filmes\*\* usando os dados do MovieLens. Ele inclui:



\- Análise exploratória dos dados (EDA)

\- Estatísticas descritivas de ratings e filmes

\- Sistema de recomendação baseado em filtragem colaborativa (User-Based)

\- Avaliação do modelo (RMSE)

\- Visualizações dos top filmes



\## Estrutura do Projeto



/data -> Contém os CSVs do MovieLens

/notebooks -> Notebooks Jupyter com análises e modelo

/src -> Código fonte (separar funções e scripts)





\## Como rodar



1\. Abra o notebook `notebooks/01-EDA.ipynb` no Jupyter Notebook ou VS Code.

2\. Execute as células na ordem para gerar análises e recomendações.

3\. Certifique-se de ter as bibliotecas instaladas:

&nbsp;  ```bash

&nbsp;  pip install pandas numpy matplotlib seaborn



Resultados



RMSE do modelo: 3.0732



Top recomendações para usuário exemplo:



Shawshank Redemption, The (1994)



Terminator 2: Judgment Day (1991)



Godfather, The (1972)



Sixth Sense, The (1999)



Lord of the Rings: The Fellowship of the Ring, The (2001)

