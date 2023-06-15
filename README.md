### SELEÇÃO DE USINAS PARA GERAÇÃO DISTRIBUÍDA

[Documentação](https://edgarflauzino.notion.site/Sele-o-de-usinas-em-gera-o-distribu-da-de00893434634e249fec143d586ae76c?pvs=4)

Projeto feito como parte de um case. A ideia é entender a [base de dados da ANEEL](https://dadosabertos.aneel.gov.br/dataset/relacao-de-empreendimentos-de-geracao-distribuida) e fazer uma seleção de potenciais usinas e análise com objetivo de aumentar a capacidade de geração da empresa em 7GWh/mês.

Alguns critérios de seleção para essa análise são:

- seleção das distribuidoras parceiras, e eventual necessidade de expansão com outras distribuidoras do país para atingir novas usinas
- seleção de usinas de mini geração (acima de 500kW de capacidade instalada)
- todas fontes de energia, exceto gás natural

No arquivo exploratory_analysis.ipynb é feita a análise exploratória para estudar 3 cenários: usinas atuais dentro da área de atuação, usinas previstas dentro da área de atuação e um terceiro cenário de expansão para novas regiões. Com isso é possível prever se o objetivo definido pode ser alcançado.

