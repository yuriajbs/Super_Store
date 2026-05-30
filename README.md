# Super_Store
## 1. Problema de negócio

A SuperStore é uma empresa com décadas de existência e hoje é uma das maiores redes de supermercados do país. Porém, em um ramo de elevada concorrência, desafios relacionados à retenção de clientes e à melhoria das estratégias de vendas são uma realidade. Diante disso, a empresa necessita se manter uma posição de destaque. Assim,com base em uma análise detalhada ampla da base de dados sobre seus clientes, pedidos, localizações das lojas e produtos, decisões estratégicas devem ser tomadas para antecipar tendências, reduzir custos operacionais e entender o comportamento do consumidor. Todas essas ações são essenciais para o contínuo sucesso da organização.

O modelo de negócio de um supermercado baseia-se na venda em alto volume de produtos, principalmente, essenciais (alimentação, higiene e limpeza) com margens de lucro unitárias baixas (geralmente entre 3% e 6%). 
Dessa forma, há um modelo comercial tradional (B2C) no qual existe uma relação direta entre a empresa e o consumidor final.
Para um diagnóstico preciso da situação das vendas da empresa, o time de gestão definiu três aréas (visões) principais com suas respectivas métricas: 

Retenção de Clientes (Análise "Cohort" - Janela de 1 ano) :
      
 1. Qual o mês do ano de 2014 e de 2015 apresentou maior retenção;
 2. Qual mês apresentou maior retenção média em 2014 e em 2015;
 3. Qual mês apresentou pior retenção média em 2014 e em 2015;
 4. Qual foi a retenção média de cada ano.

Segmentação de Clientes (Análise RFM):

 1. Qual a porcentagem de clientes representa cada segmento;
 2. Em que segmento está a maior faixa de receita;
 3. Qual faixa de clientes é necessária atenção;
 4. Quais são as categorias de clientes menos rentáveis.

Desempenho de Produtos e Regiões:

  1. Quais são os 10 produtos mais e menos vendidos;
  2. Qual a porcentagem relativa de receita desses produtos em relação aos itens vendidos;
  3. Qual região vende e tem maior receita;
  4. Qual região vende menos e tem a pior receita.


## 2. Premissas assumidas para a análise

1.  A análise foi realizada com dados entre 11/02/2022 e 06/04/2022;
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
      - Região que maior e menor receita.
      
## 4. Top 3 Insights de dados

1.  A sazonalidade da quantidade de pedidos é diária. Há uma variação de aproximadamente 10% do número de pedidos em dias sequenciais.
2.  As cidades do tipo Semi-Urban não possuem condições baixas de trânsito.
3.  As maiores variações no tempo de entrega, acontecem durante o clima ensolarado.

## 5. O produto final do projeto
Painel online, hospedado em um Cloud e disponível para acesso em qualquer dispositivo conectado à internet. O painel pode ser acessado através desse link: https://currycompany-01.streamlit.app/

## 6. Conclusão
O objetivo desse projeto é criar um conjunto de gráficos e/ou tabelas que exibam essas métricas da melhor forma possível para
o CEO.
Da visão da Empresa, podemos concluir que o número de pedidos cresceu entre a semana 06 e a semana 13 do ano de 2022

## 7. Para o futuro

1.  Reduzir o número de métricas.
2.  Criar novos filtros.
3.  Adicionar novas visões de negócio.
