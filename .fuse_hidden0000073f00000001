# Análise de dados no PowerBI
Alguns dos projetos foram inspirados pelo curso gratuito de PowerBI da 
[DSA] (https://www.datascienceacademy.com.br/pages/cursos-gratuitos-1)

## Projeto 1 - Análise de dados de Vendas para uma loja de Eletrodomésticos
### Fonte de dados: Planilha do Excel com dados extraídos do ERP/CRM da empresa
### Problema de negócio: O tomador de decisões da organização quer as respostas para as seguintes perguntas:
1. Qual o total de vendas por fabricante?
2.  Quais os principais influenciadores?
3. Quais os totais de vendas por Estado e Categoria?
4.  Qual o total de vendas por segmento?

## Projeto 2 - Análise de dados do Google Analytics
### Fonte de dados: Arquivo CSV com dados extraídos de uma loja virtual
### Problema de negócio: Responder as seguintes perguntas:
1. Como os clientes mais acessam nosso portal, por busca orgânica ou paga?
2. Quanto tempo em média um visitante permanece em nosso portal por dia do mês?
3. Qual a principal fonte de acesso ao nosso portal?
4. Qual o sistema operacional mais usado para acessar nosso portal?
5. Qual o dispositivo mais usado para acesso ao nosso portal?
6. Qual o total de faturamento por dia?

## Projeto 3 - Análise de dados OTIF (Prazos de entrega de um Ecommerce)
### Fonte de dados: Arquivo CSV do site Kaggle:[brazilian-ecommerce](https://www.kaggle.com/olistbr/brazilian-ecommerce?select=olist_orders_dataset.csv)
### Problema de negócio: Tomador de decisões quer saber:
* Qual o percentual de entregas no prazo e fora do prazo?
* Qual o desempenho da logística e transporte ao longo do tempo?
* Qual o tempo médio de uma entrega?
* A quantidade total de pedidos, entregas, devoluções.
### Atividades
* Importar os dados com codificação utf-8
* Analisar as variaveis, localizar e tratar colunas desnecessárias, dados inconsistentes, dados faltantes, dados ruidosos etc.
* Separar as datas das horas
* Calcular o total de dias de cada entrega baseado na data de pedido, data estimada para entrega e data da entrega.
* Calcular a média de dias para usar como parâmetro
* Criar nova coluna com dados da entrega (dentro e fora do prazo)

tempo_entrega = DATEDIFF(pedidos[data_pedido].[Date], pedidos[data_entrega].[Date], DAY)
entregas = if (pedidos[tempo_entrega] > 25, "No prazo", "Fora do prazo")

## Projeto 4 - Dados a partir de SGBD
* Modelagem lógica e física
* Tabelas
* ETL dos dados no PowerBI
* Análise e construção do Dashboard


