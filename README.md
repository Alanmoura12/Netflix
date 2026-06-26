Análise de Dados: Faturamento e Assinantes da Netflix
Este projeto consolida e limpa os dados de receita e usuários da Netflix (2018 - Q2 2020) para calcular o faturamento médio por assinante em cada região do mundo.

O que o código faz
Extração: Lê as bases NetflixsRevenue2018toQ2_2020.csv e NetflixSubscribersbyCountryfrom2018toQ2_2020.csv.

Transformação: Normaliza os trimestres de colunas para linhas e cruza (merge) as duas tabelas.

Métrica: Cria a coluna Receita_por_Assinante (Faturamento ÷ Assinantes).
