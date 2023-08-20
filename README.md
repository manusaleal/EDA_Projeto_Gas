# Análise Exploratória de Dados: Preço dos Combustíveis Comercializados no Brasil 

Este notebook consiste na análise exploratória de dados (EDA) referente ao dataset "Gas Prices in Brazil", extraído do Kaggle. O dataset abrange o período de 2004 até 2021 e tem como base os dados dos relatórios divulgados pela Agência Nacional do Petróleo, Gás Natural e Biocombustíveis (ANP).

Traremos os seguintes insights através dos dados:

Como os preços dos produtos se comportaram ao longo dos anos?
Como diferentes regiões do Brasil viram os preços mudarem?
Qual é a mínima e máxima histórica de preço por produto por estado?
Tipos de Produtos:

Etanol Hidratado
Gás Natural Veicular (GNV)
Gás Liquefeito de Petróleo (GLP) – Gás de Cozinha - Botijão de 13 quilos
Gasolina Comum
Gasolina Aditivada
Óleo Diesel
Óleo Diesel S-10 -> Foi adicionado depois
Observações importantes: Até 30 de outubro de 2004, todos os preços médios eram calculados por média aritmética simples. Após esta data, os preços médios de revenda e de distribuição de combustíveis, em nível estadual, regional e nacional, passaram a ser ponderados com base nas informações de vendas enviadas pelas distribuidoras à ANP. Atualmente, apenas o preço médio em nível municipal é obtido por média aritmética simples. Portanto devemos analisar apenas os dados fornecidos a partir do dia 31/10/2004. Os valores NULL foram substituídos pelo valor -99999 pelo responsável do dataset.

fonte: https://www.kaggle.com/datasets/matheusfreitag/gas-prices-in-brazil

[Acesso ao Projeto](EDA_Projeto_Gas.ipynb) 
