# ProjetoBootcampDWE
Projeto em que desenvolvi um pipeline de dados no Notebook do Azure Data Studio utilizando as linguagens SQL e T-SQL através dos comandos DML.

1ª Parte – Desenvolvimento Pipeline/Notebook Azure Data Studio

ANÁLISE REALIZADA:
A execução de despesas do Governo, arquivo fonte de dados do Portal da transparência, referente aos dados de Jan/22 a Mar/22, 1º Trimestre.
Dados:
• Órgão Superior
• Órgão Subordinado
• Unidade Gestora
• Gestão
• Grupo de Despesa
• Tempo
MÉTRICAS:
• Valor Empenhado (R$)
• Valor Liquidado (R$)
• Valor Pago (R$)
REQUISITOS TÉCNICOS
• Modelagem Star Schema, desnormalização dos dados e a carga de dados no banco de dados DW_36.
• As dimensões do projeto devem controlar alterações ao longo do tempo (SCD tipo 2).
• Logs de execuções do pipeline.
• Scripts com possibilidade de reprocessamentos.
• Use Linguagem SQL e T-SQL

2ª Parte – Aplicação dos conhecimentos de SQL e T-SQL através dos comandos DML para responder 10 perguntas.

PERGUNTAS:
• Qual o total em Jan/2022 Valor Pago (R$) para cada Órgão Superior?
• Quais os top 10 Órgãos Superiores referente a Jan/2022 em Valor Pago (R$)?
• Qual o total no Trimestre de Valor Empenhado (R$) para cada Gestão?
• Quais as Top 10 Gestão no Trimestre referente a valor empenhado?
• Qual o total mês a mês de Valor Liquidado (R$) para cada Grupo de Despesa?
• Quais os TOP 10 Grupo de Despesas referente a valor Liquidado (R$) em Fev/2022?
• Qual a variação %(MoM) de Valor Empenhado (R$) de Mar/2022 para Fev/2022 por Unidade Gestora?
• Retorno o maior Valor Empenhado (R$) de Grupo de despesas em Fev/2022 para cada Órgão Superior.
• Retorne o % de Valor Pago (R$) sobre o total, por Gestão Fev/2022.
• Retorne o valor média de Valor Pago (R$) por despesa agrupado por Gestão.
