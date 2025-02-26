# analise_recomendacao_de_filmes
Sistema de Recomendação de Filmes

📌 Visão Geral

Este projeto tem como objetivo construir um sistema de recomendação de filmes com base nas avaliações dos usuários. Utilizando técnicas de filtragem colaborativa, ele sugere filmes similares com base na correlação de um filme selecionado com outros do conjunto de dados.

🔍 Metodologia

Preparação dos Dados:

Carregar um conjunto de dados contendo avaliações de usuários para diversos filmes.

Criar uma matriz usuário-item com as avaliações dos filmes.

Lidar com valores ausentes substituindo os NaNs pela média das avaliações do usuário.

Cálculo da Correlação:

Selecionar um filme (exemplo: Star Wars).

Calcular o coeficiente de correlação de Pearson entre esse filme e os demais.

Filtrar os filmes que possuem um número suficiente de avaliações para garantir recomendações significativas.

Geração de Recomendações:

Classificar os filmes com base nos seus escores de correlação.

Exibir os 30 filmes mais similares.

⚙️ Tecnologias Utilizadas

Python

Pandas para manipulação de dados

NumPy para operações numéricas

Jupyter Notebook para execução de código e visualização

📊 Resultados

O sistema identificou com sucesso filmes altamente correlacionados com Star Wars (1977), incluindo:

Return of the Jedi (1983)

Empire Strikes Back (1980)

Indiana Jones and the Last Crusade (1989) (provavelmente influenciado pela presença de Harrison Ford em ambas as franquias)

