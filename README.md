##  Modelagem de Dados no Power BI

O desenvolvimento do dashboard focou em aplicar as melhores práticas de business intelligence para transformar os dados brutos em indicadores de negócio confiáveis:

* **Processo de ETL (Power Query):** Consolidação e unificação das tabelas de Receita e Assinantes em uma única tabela Fato (`fFato_Netflix`), otimizando a performance do modelo.
* **Inteligência de Tempo com DAX:** Criação de medidas calculadas dinâmicas para contornar a duplicidade de dados acumulados (como a métrica de assinantes por trimestre).
* **Cálculo de KPIs de Negócio:** Desenvolvimento da métrica **ARPU** (Receita Média por Usuário), dividindo o faturamento pela base de clientes ativos de forma contextualizada.
* **Storytelling e Design:** Painel desenvolvido em *Dark Mode* inspirado na identidade visual da própria Netflix, focado na experiência do usuário e na leitura rápida de dados geográficos.
