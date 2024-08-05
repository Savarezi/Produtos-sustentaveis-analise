# Análise de Vendas e Sentimentos de Produtos Sustentáveis vs Convencionais  :heavy_dollar_sign: :chart_with_upwards_trend:
Este projeto realiza uma análise simples de vendas e sentimentos relacionados a produtos sustentáveis e convencionais, utilizando bibliotecas populares de Python como Pandas, Matplotlib, Seaborn e TextBlob. O objetivo é visualizar as vendas e as polaridades de sentimentos de menções em mídias sociais sobre esses produtos.

##
# Funcionalidades:

* Coleta de Dados do Usuário: Interação inicial com o usuário, coletando nome, idade e cidade.

* Criação de um DataFrame: Geração de dados fictícios sobre vendas e menções em mídias sociais de diferentes produtos.

* Análise de Sentimentos: Cálculo da polaridade dos sentimentos das menções em mídias sociais usando a biblioteca TextBlob.

* Visualização de Dados: Criação de gráficos para visualizar vendas e polaridade dos sentimentos para cada produto.

* ##

# Requisitos:

:white_check_mark:Python 3.x

:white_check_mark:Pandas

:white_check_mark:Matplotlib

:white_check_mark:Seaborn

:white_check_mark:TextBlob

##
# Estrutura do Código:
Coleta de Informações do Usuário   :triangular_ruler:

O código começa coletando informações básicas do usuário, como nome, idade e cidade, e exibe uma saudação personalizada.
##
Importação de Bibliotecas
Em seguida, o código importa as bibliotecas necessárias para manipulação de dados, visualização e análise de sentimentos.
##

# Importação de Bibliotecas

Em seguida, o código importa as bibliotecas necessárias para manipulação de dados, visualização e análise de sentimentos.

 :blue_book:import pandas as pd
 
 :blue_book:import matplotlib.pyplot as plt
 
 :blue_book:import seaborn as sns
 
 :blue_book:from textblob import TextBlob
##
# Geração e Exibição de Dados Fictícios

O código gera um DataFrame com dados fictícios de produtos, incluindo vendas e menções em mídias sociais. As menções em mídias sociais contêm comentários que serão analisados
para determinar a polaridade do sentimento.
##
# Análise de Sentimentos :blush: :blush: :blush:

Utilizando a biblioteca TextBlob, o código calcula a polaridade do sentimento das menções em mídias sociais para cada produto, adicionando essa informação ao DataFrame.
##

# Visualização dos Dados  :computer:

 *Dois gráficos são gerados para visualização:* :part_alternation_mark:

:heavy_check_mark:Gráfico de Barras das Vendas: Mostra as vendas de cada produto.

:heavy_check_mark:Gráfico de Barras dos Sentimentos: Exibe a polaridade dos sentimentos relacionados a cada produto.








