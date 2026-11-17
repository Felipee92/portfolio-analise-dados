# 🚚 Dashboard de Logística — Eficiência Operacional, Entregas e Custos de Frete

![Visão Geral do Dashboard de Logística](dashboard.png)

## 🎯 Objetivo do Projeto
Desenvolver um painel gerencial para o monitoramento completo da operação logística, permitindo acompanhar o volume de entregas, cumprimento de prazos (OTIF / entregas no prazo vs. atrasadas), custos com frete e o desempenho por transportadora e região.

## 🛠️ Ferramentas e Técnicas Utilizadas
* **Power BI Desktop:** Criação de layout executivo, navegação intuitiva e storytelling visual para tomada de decisão.
* **Power Query (ETL):** Tratamento, limpeza, padronização de datas e transformação das bases operacionais.
* **Linguagem DAX:** Desenvolvimento de medidas dinâmicas para cálculo de total de entregas, taxa de entregas no prazo (%), custo médio de frete e indicadores comparativos.
* **Modelagem de Dados:** Estruturação em Esquema Estrela (*Star Schema*) conectando tabelas fato de movimentação logística às dimensões de calendário, clientes e transportadoras.

## 💡 Principais Análises e Indicadores
* **Eficiência de Prazo:** Monitoramento percentual das entregas realizadas dentro do prazo acordado vs. ocorrências de atraso.
* **Gestão de Custos:** Acompanhamento da evolução mensal dos gastos com frete e impacto por rota/região.
* **Desempenho de Parceiros:** Comparativo de volume e qualidade de entrega entre transportadoras para apoio na renegociação de contratos.
