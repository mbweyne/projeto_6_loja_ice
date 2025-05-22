![Banner do Projeto](banner_p6_ice.png)

🎮 Projeto: Análise de Vendas de Jogos para a Loja Ice (2016)

Este projeto tem como objetivo analisar dados de vendas globais de videogames, identificando padrões que determinam o sucesso de um jogo. A análise serve de base para o planejamento de campanhas publicitárias para o ano de 2017 da loja online **Ice**.

## 📊 Objetivo

Analisar avaliações de usuários e especialistas, plataformas, gêneros, classificações ESRB e dados históricos de vendas para entender o comportamento do mercado e prever tendências lucrativas.

## 🗂️ Conjunto de Dados

- Fonte: `/datasets/games.csv`
- Período: até 2016
- Variáveis principais:
  - `name`: Nome do jogo
  - `platform`: Plataforma (ex: Xbox, PlayStation)
  - `year_of_release`: Ano de lançamento
  - `genre`: Gênero
  - `na_sales`, `eu_sales`, `jp_sales`, `other_sales`: Vendas por região
  - `critic_score`, `user_score`: Avaliações
  - `rating`: Classificação ESRB

## 🧠 Etapas do Projeto

1. **Revisão Inicial dos Dados**  
   Carregamento, inspeção geral e limpeza.

2. **Preparação dos Dados**  
   - Padronização de colunas e tipos
   - Tratamento de valores ausentes
   - Criação da coluna `total_sales`

3. **Análise Exploratória**  
   - Vendas por ano e plataforma
   - Tendências e popularidade
   - Efeito de notas de usuários e críticos
   - Análise por gênero

4. **Análise Regional (NA, EU, JP)**  
   - Plataformas e gêneros mais vendidos
   - Impacto das classificações ESRB

5. **Testes de Hipóteses**  
   - Comparação entre médias de avaliações por plataforma e gênero

6. **Conclusão**  
   - Principais insights para decisões estratégicas em 2017

## 📌 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat)
![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white&style=flat)
![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white&style=flat)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?logo=matplotlib&logoColor=white&style=flat)
![Seaborn](https://img.shields.io/badge/-Seaborn-44A8B3?logo=seaborn&logoColor=white&style=flat)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?logo=scipy&logoColor=white&style=flat)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white&style=flat)

## 👩‍💻 Autora

**Márcia Bayardino Weyne**  
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white&style=flat)](https://www.linkedin.com/in/marcia-bayardino-weyne)  
[![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=flat)](https://github.com/mbweyne)

## 📁 Estrutura do Repositório

P6_Loja_Ice/
│
├── data/
│ └── games.csv
├── images/
│ └── banner.png
├── notebook/
│ └── ice_games_analysis.ipynb
├── README.md
└── requirements.txt