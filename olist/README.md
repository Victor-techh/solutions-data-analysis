# 🛒 Análise Estratégica Olist

Este projeto faz parte do meu portfólio de **Data Science & Analytics**. Aqui, utilizo o dataset real da Olist (e-commerce brasileiro) para resolver problemas de negócio usando **Python, Pandas e SQL**.

## 🚀 O que já foi feito:

### 1. Prevenção de Churn (Retenção de Clientes)
- Limpeza e tratamento de datas.
- Identificação de clientes ativos e inativos.
- Segmentação baseada em recência de compra.

-    # Análise de Churn e Eficiência Logística - E-commerce Olist
     Este projeto realiza uma investigação profunda sobre os fatores que influenciam a retenção de clientes na Olist, 
     um dos maiores marketplaces do Brasil. Através de Python e SQL, cruzamos dados de vendas, logística e comportamento 
     do consumidor para diagnosticar as causas de uma taxa de churn elevada.

     📌 Contexto de Negócio
     A Olist atua como um facilitador para pequenos lojistas, mas enfrenta um desafio comum ao varejo digital: a recorrência. 
     O objetivo deste estudo foi entender se a logística brasileira e os custos de frete são os principais responsáveis  
     pela perda de clientes.

     Os dados utilizados são públicos e oficiais, extraídos do Kaggle - Brazilian E-Commerce Public Dataset by Olist.
     [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

     🛠️ Tecnologias Utilizadas
     ** Python: Extração e manipulação de dados.
     ** Pandas: Limpeza e tratamento de datas e tipos.
     ** SQLite3: Persistência de dados e consultas relacionais complexas.
 
     Matplotlib & Seaborn: Visualização de dados e gráficos de correlação.

     📊 Principais Insights
     1. O Teto da Recorrência
     Foram Identificamos que 97% da base de clientes realizou apenas uma única compra. A taxa de Churn (clientes inativos
     há mais de 90 dias) atinge 90%, evidenciando que o modelo atual é focado em aquisição pontual e não em fidelização.

     3. O Paradoxo do "Prazo Gordo"
     A análise revelou que a Olist utiliza prazos estimados muito conservadores. Em estados do Norte, a entrega ocorre
     até 20 dias antes do previsto.

     O Insight: Rapidez na entrega não compra lealdade se o custo de entrada for alto.

     3. Correlação Frete vs. Churn
     Foram utilizamos o coeficiente de Pearson (0.47) para provar a correlação moderada/forte entre o custo do frete e a
     perda de clientes. Em estados como RO e RR, o frete chega a representar 60% do valor do produto.

     📈 Conclusão
     O Churn da Olist é impulsionado pelo Custo Brasil. Enquanto a experiência de entrega (tempo) é positiva, a barreira 
     financeira do frete impede que o comprador de oportunidade se torne um cliente recorrente.


### 2. Mix de Produtos (Performance de Faturamento)
- Cruzamento de múltiplas tabelas via SQL (`JOINs`).
- **Curva ABC:** Identificação das categorias que geram 50% do faturamento da empresa (Princípio de Pareto).
- Tradução de categorias para internacionalização do projeto.

## 🛠️ Próximos Passos
- Criação do Gráfico de Pareto interativo.
- Cálculo de Ticket Médio por categoria.

