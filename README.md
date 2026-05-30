# Super_Store
## 1. Problema de negócio

A SuperStore é uma empresa com décadas de existência e hoje é uma das maiores redes de supermercados do país. Porém, em um ramo de elevada concorrência, desafios
relacionados à retenção de clientes e à melhoria das estratégias de vendas são uma realidade. Diante disso, a empresa necessita se manter uma posição de destaque. Assim,
com base em uma análise detalhada ampla da base de dados sobre seus clientes, pedidos, localizações das lojas e produtos, decisões estratégicas devem ser tomadas para antecipar
tendências, reduzir custos operacionais e entender o comportamento do consumidor. Todas essas ações são essenciais para o contínuo sucesso da empresa.

O modelo de negócio de um supermercado baseia-se na venda em alto volume de produtos, principalmente, essenciais (alimentação, higiene e limpeza) com margens de lucro unitárias baixas (geralmente entre 3% e 6%). 
Dessa forma, há um modelo comercial tradional (B2C) no qual existe uma relação direta entre a empresa e o consumidor final.
Para um diagnóstico preciso da situação das vendas da empresa, o time de gestão definiu três aréas principais com suas respectivas métricas: 

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

Desempenho de Produtos e Localizações:

  1. Quais são os 10 produtos mais e menos vendidos;
  2. Qual a porcentagem relativa de receita desses produtos em relação aos itens vendidos;
  3. Qual região vende e tem maior receita;
  4. Qual região vende menos e tem a pior receita.


## 2. Premissas assumidas para a análise

1.  A análise foi realizada com dados entre 11/02/2022 e 06/04/2022.
2.  Marketplace foi o modelo de negócio assumido.
3.  Os 3 principais visões do negócio foram: Visão transação de pedidos, visão restaurante e visão entregadores.

## 3. Estratégia da solução

O painel estratégico foi desenvolvido utilizando as métricas que refletem as 3 principais visões do modelo de negócio da empresa:
1.  Visão do crescimento da empresa.
2.  Visão do crescimento dos restaurantes.
3.  Visão do crescimento dos entregadores.

Cada visão é representada pelo seguinte conjunto de métricas.

1.  Visão do crescimento da empresa:

      - Pedidos por dia.
      - Porcentagem de pedidos por condições de trânsito.
      - Quantidade de pedidos por tipo e por cidade.
      - Pedidos por semana.
      - Quantidade de pedidos por tipo de entrega.
      - Quantidade de pedidos por condições de trânsito e tipo de cidade.

2.  Visão do crescimento dos restaurantes:

      - Quantidade de pedidos únicos.
      - Distância média percorrida.
      - Tempo médio de entrega durante festival e dias normais.
      - Desvio padrão do tempo de entrega durante festivais e dias normais.
      - Tempo de entrega médio por cidade.
      - Distribuição do tempo médio de entrega por cidade.
      - Tempo médio de entrega por tipo de pedido.

3.  Visão do crescimento dos entregadores:

      - Idade do entregador mais velho e do mais novo.
      - Avaliação do melhor e do pior veículo.
      - Avaliação média por entregador.
      - Avaliação média por condições de trânsito.
      - Avaliação média por condições climáticas.
      - Tempo médido do entregador mais rápido.
      - Tempo médio do entregador mais rápido por cidade.

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
