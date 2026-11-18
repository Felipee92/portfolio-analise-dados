# 👥 Dashboard de Recursos Humanos — Análise de Horas Extras e Apontamentos Críticos

![Visão Geral do Dashboard de RH](dashboard.png)

## 🎯 Objetivo do Projeto
Desenvolver um painel gerencial para o monitoramento de banco de horas e horas extras da operação, permitindo identificar gargalos por cargo e setor, acompanhar a evolução diária dos apontamentos e sinalizar colaboradores em nível crítico para apoiar a gestão de pessoas e o controle de custos trabalhistas.

## 🛠️ Ferramentas e Técnicas Utilizadas
* **Power BI Desktop:** Construção de layout executivo com navegação lateral, cartões de KPIs com ícones personalizados e formatação condicional de alertas.
* **Power Query (ETL):** Tratamento, limpeza, padronização de registros de ponto e classificação de regras de negócio (Normal vs. Crítico).
* **Linguagem DAX:** Criação de medidas dinâmicas para cálculo de Saldo de Horas, Média de Horas Extras por colaborador, contagem de apontamentos e análise temporal.
* **Modelagem de Dados:** Estruturação relacional conectando a tabela fato de registros de ponto às dimensões de colaboradores, cargos, setores e calendário.

## 💡 Principais Análises e Indicadores
* **Indicadores Executivos:** Visão rápida do Saldo Total de Horas, Média de Horas Extras e total de colaboradores impactados com filtro dinâmico por período.
* **Mapeamento por Cargo e Setor:** Identificação imediata das funções com maior acúmulo de horas extras (como Motoristas e Separadores de Estoque) e setores críticos.
* **Detalhamento por Colaborador:** Matriz analítica com drill-down entre apontamentos Críticos e Normais, permitindo à liderança agir preventivamente sobre casos individuais com excesso de jornada.
