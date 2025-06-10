# Web Scraping Project – FIIs Analysis & Data Science

## Contextualização
A Ciência de Dados está presente em todos os lugares. No cenário atual, vivemos em um mundo orientado por dados, em que informações podem ser extraídas da internet, tratadas, analisadas e transformadas em insights valiosos. Essa realidade impacta diversos setores, inclusive o mercado de fundos imobiliários, onde o acesso a informações relevantes pode representar uma importante vantagem estratégica. Com a evolução tecnológica e o aumento exponencial da geração de dados, torna-se essencial compreender como essas informações podem ser utilizadas para tomada de decisão e criação de valor.

## Objetivo
O objetivo deste projeto é utilizar a técnica de Web Scraping para extrair dados de sites especializados, realizar a limpeza e o tratamento desses dados, e conduzir uma análise conforme uma regra de negócio definida. As fontes de dados utilizadas são:
- [Fundsexplorer - Ranking](https://www.fundsexplorer.com.br/ranking)
- [Status Invest - Fundos Imobiliários](https://statusinvest.com.br/fundos-imobiliarios)

## Regras de Negócio
A análise dos FIIs (Fundos Imobiliários) segue os seguintes critérios:
- **Preço Atual:** menor ou igual a R$ 200.
- **Dividendos:** valor maior que 0,75.
- **P/VP (Preço/Valor Patrimonial):** inferior a 1.

## Metodologia e Análise
O projeto foi conduzido em etapas:
1. **Coleta de Dados:** Utilização de web scraping para extrair informações relevantes dos sites indicados.
2. **Tratamento e Limpeza de Dados:** Processamento dos dados para correção de formatos, tratamento de valores nulos e conversões necessárias.
3. **Análise Exploratória:** Identificação de padrões, tendências e a distribuição dos dados, com destaque para a verificação dos setores e desempenho dos fundos.
4. **Aplicação das Regras de Negócio:** Filtragem dos fundos que atendem aos critérios especificados.
5. **Visualização dos Resultados:** Geração de gráficos para correlacionar o preço atual dos fundos e o acumulado de dividendos em 12 meses.

## Resultados
Como resultado da aplicação da metodologia proposta e das regras de negócio definidas — preço atual igual ou inferior a R$ 200, dividendos superiores a 0,75 e indicador P/VP inferior a 1 — foram identificados os fundos imobiliários que se destacam no acumulado de 12 meses.
O fundo BRLA11, do setor híbrido e com preço atual de R$ 147,00, apresentou o maior pagamento de dividendos no período, sendo o mais atrativo entre os analisados. Além disso, os fundos RNDP11 e TRXF11 demonstraram desempenho acima da média dentro dos mesmos critérios, representando boas oportunidades para análise e acompanhamento por investidores.
Esses resultados comprovam o potencial da análise automatizada como ferramenta de suporte à tomada de decisão no mercado de FIIs.

## Como Executar
1. **Dependências:** Certifique-se de que todas as bibliotecas utilizadas (pandas, numpy, yfinance, requests, BeautifulSoup, matplotlib, etc.) estejam instaladas.
2. **Execução do Notebook:** Abra e execute o arquivo `Web-Scraping-Projeto01.ipynb` que contém o fluxo completo de extração, tratamento e análise dos dados.
3. **Visualização:** Analise os gráficos e resultados gerados para compreender a performance dos fundos segundo os critérios definidos.

## Observações
- **Acessibilidade dos Dados:** Verifique se os sites de origem estão disponíveis para evitar falhas na coleta dos dados.
- **Customização:** As regras de negócio e os parâmetros da análise podem ser ajustados conforme novas necessidades ou insights.
