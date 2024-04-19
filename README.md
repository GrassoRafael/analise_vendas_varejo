# Case 2 Data Analysis escola DNC

# O dataset de varejo que temos em mãos é composto por informações de vendas de uma loja virtual que atua em todo território nacional, vendendo produtos de diferentes departamentos. Além disso, a loja atua em diferentes canais de venda, como marketplce, loj própria, entre outros.

Premissas de negócio:
Ao analisar os dados, é importante ter em mente que existem algumas premissas de negócio que devem ser consideradas. A primeira delas é que, devio a um erro no sistema, algumas compras não possuem informações de UF (Unidade Federativa). Para solucionar esse problema, foi decidido que essas compras serão considerads como percentes do estado do Mato Grosso do Sul (MS). A segunda premissa é que o preço final do produto não pode ser maior do que o preço com o frete. 

Métricas:
Com base nesse contexto e nas premissas de negócios estabelecidas, podemos avalias as seguintes métricas:

1. Departamos mais vendidos: Analisando os dados de vendas, podemos identificar quais são os departamentos mais populares ente os clientes. Essa informação pode ser útil para entender quais são os produtos mais procurados pelos clientes e ajustar a estratégia de venda da loja em conformidade.
2. Média de preço com frete por nome de departamento: Para entender o comportamento de preço por departamento, podemos calcular a média de preço com frete por nome de departamento. Essa métrica pode ajudr a identificar quais são os departamentos mais rentáveis e ajustar a precificação de produtos de acrodo com a margem desejada.
3. Quantidade de vendas por mês: Analisando a quantidade de vendas realizadas em cada mês, podemos identificar sazonalidade dno comprotamento de compra e será possível planejar campanhar de marketing específicas para cada período.
4. Média de renda para cada tipo de canal de venda: Identificar a média de renda dos clientes em diferentes canais de venda pode ajudar a loja a acompanhar as métricas de marketing e vendas para cada público-alvo.
5. Média de idade de cliente por bandeira: Saber a faixa etária dos clientes por bandeira pode ajudar a identificar perfis de consumidores e ajustar as estratégias de venda para atender melhor cada público.

# Bibliotecas utilizadas
  1. Pandas
  2. Seaborn
  3. Myplotlib
  4. Cufflinks
  5. Chart_studio

# Feito em:
  1. Python
  2. JupyterNotebook
