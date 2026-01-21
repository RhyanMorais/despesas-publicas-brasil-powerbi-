# Estados do Brasil e suas Despesas Públicas

Dashboard interativo desenvolvido em Power BI para análise das despesas públicas federais e estaduais do Brasil, com foco no ano de 2023.

## Objetivo do Projeto

Analisar a execução orçamentária no Brasil a partir dos valores empenhados, liquidados e pagos, permitindo comparações por estado, órgão público, função orçamentária e período.

O projeto busca apoiar a compreensão de como os recursos públicos são distribuídos e executados ao longo do ano.

## Fonte dos Dados

Os dados utilizados são públicos e provenientes de bases oficiais do governo brasileiro.

Devido ao grande volume de informações, o conjunto de dados não foi versionado neste repositório.  
O arquivo `.pbix` contém os dados já tratados, modelados e prontos para análise.

## Principais Métricas

- Valor Empenhado  
- Valor Liquidado  
- Valor Pago  
- Percentual do Valor Pago em relação ao Empenhado  
- Comparação entre despesas federais e estaduais  

## Estrutura do Dashboard

O dashboard está organizado nas seguintes análises:

- Visão geral das despesas por estado
- Distribuição dos valores empenhados entre os estados
- Análise por funções orçamentárias
- Comparação entre despesas federais e estaduais
- Evolução mensal das despesas por órgão público
- Ranking dos órgãos superiores com maior volume de gastos

## Modelo de Dados

O modelo segue uma abordagem em estrela, composto por:

- Tabela fato de despesas públicas
- Dimensão geográfica de estados
- Dimensões administrativas e orçamentárias
- Medidas calculadas em DAX para análise financeira

## Tecnologias Utilizadas

- Power BI
- Power Query para tratamento de dados
- DAX para criação de medidas
- Modelagem de dados relacional

## Principais Insights

- Forte concentração das despesas federais em encargos especiais e previdência social
- Diferença significativa entre valores empenhados e pagos em determinados períodos
- Participação proporcionalmente menor das despesas estaduais no total analisado
- Variação mensal relevante nos pagamentos ao longo do exercício

## Observações

Este projeto tem caráter analítico e educacional, com foco em Business Intelligence e visualização de dados.  
As análises refletem exclusivamente os dados disponíveis nas bases públicas utilizadas.
