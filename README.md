# Super_Store
## 1. Problema de negócio

A SuperStore é uma empresa com décadas de existência e hoje é uma das maiores redes de supermercados do país. Porém, em um ramo de elevada concorrência, desafios relacionados à retenção de clientes e à melhoria das estratégias de vendas são uma realidade. Diante disso, a empresa necessita manter uma posição de destaque. Assim,com base em uma análise detalhada ampla da base de dados sobre seus clientes, pedidos, localizações das lojas e produtos, decisões estratégicas devem ser tomadas para antecipar tendências, reduzir custos operacionais e entender o comportamento do consumidor. Todas essas ações são essenciais para o contínuo sucesso da organização.

O modelo de negócio de um supermercado baseia-se na venda em alto volume de produtos, principalmente, essenciais (alimentação, higiene e limpeza) com margens de lucro unitárias baixas (geralmente entre 3% e 6%). 
Dessa forma, há um modelo comercial tradicional (B2C) no qual existe uma relação direta entre a empresa e o consumidor final.
Para um diagnóstico preciso da situação das vendas da empresa, o time de gestão definiu três áreas (visões) principais com suas respectivas métricas: 

Retenção de Clientes (Análise "Cohort" - Janela de 1 ano) :
      
 1. Qual o mês do ano de 2014 e de 2015 apresentou maior retenção ?
 2. Qual mês apresentou maior retenção média em 2014 e em 2015 ?
 3. Qual mês apresentou pior retenção média em 2014 e em 2015 ?
 4. Qual foi a retenção média de cada ano ?

Segmentação de Clientes (Análise RFM):

 1. Qual a porcentagem de clientes representa cada segmento ?
 2. Em que segmento está a maior faixa de receita ?
 3. Qual faixa de clientes é necessária atenção ?
 4. Quais são as categorias de clientes menos rentáveis ?

Desempenho de Produtos e Regiões:

  1. Quais são os 10 produtos mais e menos vendidos ?
  2. Qual a porcentagem relativa de receita desses produtos em relação aos itens vendidos ?
  3. Qual região vende e tem maior receita ?
  4. Qual região vende menos e tem a pior receita ?


## 2. Premissas assumidas para a análise

1.  A análise foi realizada com dados entre xxx;
2.  Modelo comercial tradicional (B2C) foi o modelo de negócio assumido;
3.  As 3 principais visões do negócio foram: Retenção de Clientes, Segmentação de Clientes e Desempenho de Produtos e Regiões.

## 3. Estratégia da solução

O painel estratégico foi desenvolvido utilizando as métricas que refletem as 3 principais visões do modelo de negócio da empresa:
1.  Retenção de Clientes;
2.  Segmentação de Clientes;
3.  Desempenho de Produtos e Regiões.


Cada visão é representada pelo seguinte conjunto de métricas.

1.  Visão de Retenção de Clientes:

      - Meses de maior retenção nos anos de 2014 e 2015;
      - Maior retenção média mensal em 2014 e 2015;
      - Pior retenção média mensal em 2014 e 2015;
      - Retenção média anual.
     
2.  Visão da Segmentação de Clientes:

      - Porcentagem de clientes por segmento;
      - Segmento com maior receita;
      - Segmento de atenção;
      - Segmentos menos rentáveis.
      
3.  Visão do Desempenho de Produtos e Regiões:

      - "Top 10" produtos mais e menos vendidos;
      - Porcentagem relativa desses produtos em relação aos demais;
      - Região que mais e menos vende;
      - Região que de maior e menor receita.
      
## 4. Top 4 Insights de dados

1. O mês de setembro de 2014 e o mês de junho de 2015 foram os que apresentaram maior retenção média. A média de retenção global de 2014 e 2015 foi de 10%;
2.  A faixa Fiéis corresponde a 27% dos consumidores e a 51,77% da receita total dos clientes;
3.  Os 10  produtos mais vendidos correspondem a 17,53% da receita total;
4.  As regiões Leste e Sul possuem uma receita proporcionalmente menor (25,85% e 13,47%) em relação ao número de pedidos ( 27,97% e 16,41%). Destoando das demais regiões;


## 5. O produto final do projeto
Painel em PDF, hospedado em um Cloud e disponível para acesso em qualquer dispositivo conectado à internet ou offline mediante "download". O painel pode ser acessado através desse link: https://currycompany-01.streamlit.app/

## 6. Conclusão
O objetivo desse projeto é criar um conjunto de gráficos e/ou tabelas que exibam essas métricas da melhor forma possível para os gestores. A partir da visão de Segmentação dos Clientes, verifica-se que caso  metade dos consumidores considerados Perdidos se torne Fiéis em Potencial  pode haver um aumento de cerca de R$ 118.653.157,43 na receita para a empresa.

## 7. Para o futuro

1.   Desenvolver novas métricas;
2.  Criar novos filtros;
3.  Adicionar novas visões de negócio.
