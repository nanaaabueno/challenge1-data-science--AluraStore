# **Relatório Final — Análise de Vendas e Desempenho das Lojas — Alura Store**

### 📌 **Introdução**

Este relatório apresenta uma análise completa do desempenho das quatro lojas da rede Alura Store, com o objetivo de apoiar o Sr. João na decisão de vender a loja com menor performance. Foram avaliadas métricas essenciais de vendas, faturamento, avaliações de clientes, frete e desempenho por produto, utilizando Python e as bibliotecas Pandas, Matplotlib e Seaborn.

Os dados foram consolidados a partir das bases individuais de cada loja, conforme disponibilizados no desafio, e analisados de forma integrada.

### ⚙️ **Metodologia**

>As etapas executadas foram:

Importação e consolidação dos dados
Reunimos os dados de loja_1.csv, loja_2.csv, loja_3.csv e loja_4.csv em um único DataFrame.

>Cálculo das métricas solicitadas no desafio:

Faturamento total das lojas

Categorias mais vendidas

Média de avaliação por loja

Produtos mais e menos vendidos

Frete médio

Geração de gráficos com Matplotlib e Seaborn, conforme desenvolvido no notebook:

Gráfico de barras para faturamento

Gráfico de pizza para categorias

Gráfico combinado (barras + linha) para os produtos mais vendidos

Gráfico horizontal de frete médio

Gráfico geográfico de dispersão (latitude e longitude)

Conclusão final, apontando a loja com pior desempenho geral.


### 📊 **Análises Realizadas**
💰 **1. Faturamento Total por Loja**

O faturamento foi calculado por meio da soma dos valores da coluna Preço, agrupados por loja.

📉 Gráfico utilizado:

➡️ Gráfico de barras simples (Matplotlib) mostrando o faturamento por loja.

>Principais conclusões:

Há diferenças significativas de faturamento entre a loja mais rentável, Loja 1, e a menos rentável, Loja 4.

A loja com menor faturamento demonstra menor capacidade de geração de receita.

🛍️ **2. Vendas por Categoria**

A quantidade de vendas por categoria foi obtida através da contagem de itens vendidos dentro de cada categoria.

📉 Gráfico utilizado:
➡️ Gráfico de pizza mostrando a participação percentual de cada categoria.

>Percepções:

Apesar das lojas possuirem um mix diversificado de categorias de produtos, as três principais categorias, eletronicos, eletrodomesticos e moveis, conentram 51% das quntidades vendidas e respondem por 85% do faturamento total das lojas consolidades. 

A diversidade de categorias varia entre as lojas, se que haja impacto direto percepitível na performance da unidade.

⭐ **3. Média de Avaliação das Lojas**

A média das avaliações dos clientes reflete a percepção do consumidor sobre atendimento, entrega e experiência de compra.

Não foi gerado gráfico nesta etapa, apenas tabelas de valores.

>Resultados:

Nenhuma das lojas se destaca entre si na avaliação média dos clientes. A varição percentual entre a média de avaliação da loja melhor avaliada e da loja com avaliação menor é de menos de 2%, o que sugere que o relacionamento com os clientes é homogênia não sendo este um critério decisivo para a decisão de venda de uma das unidades.

🛒 **4. Produtos mais e menos vendidos**

>Na análise proposta foi identificado:

Top 10 produtos mais vendidos

Top 10 em faturamento

Produtos de menor volume de vendas

Produtos com maior e menor faturamento por loja

📉 Gráfico utilizado:

➡️ Gráfico híbrido — barras (quantidade vendida) + linha (faturamento), para o Top 10 mais vendidos em quantidade.

➡️ Gráfico horizontal por loja usando Seaborn, destacando faturamento do Top 10 por loja.

>Conclusões chave:

Alguns produtos representam grande parte do faturamento total.

Produtos com baixíssimo desempenho podem influenciar negativamente o estoque e logística.

🚚 **5. Frete Médio por Loja**

O frete médio foi calculado como a média da coluna Frete para cada loja.

📉 Gráfico utilizado:
➡️ Gráfico de barras horizontais mostrando o frete médio.

>Conclusões:

Lojas com frete médio mais alto podem apresentar menor competitividade, ainda mais considerando que a margens de contribuição no seguimento de varejo costumam ser baixas.

As análises feitas não foram suficientemente conclusivas para determinar o motivo da variação no frete médio entre as lojas, ainda que haja indícios de que o frete médio é mais alto na Loja 4, por essa ter uma distribuição de suas vendas em todas as regiões do país, o que pode aumentar o custo com a logítica de entrega. Esse ponto foi observado correlacionando a média de frete por loja e ditribuição regional das vendas por loja do item 6, a seguir.

🗺️ **6. Análise Geográfica (Latitude e Longitude)**

Um gráfico de dispersão foi utilizado para visualizar a distribuição espacial das vendas:

📉 Gráfico utilizado
➡️ Scatter plot simples com marcadores “x”, latitude no eixo Y e longitude no eixo X.

>O que observamos:

Há concentração das vendas em regiões específicas.

Diferenças geográficas podem afetar custos e avaliações.

#🧾 **Conclusão — Qual loja deve ser vendida?**

Após análise das métricas avaliadas – faturamento, categorias, avaliações, vendas por produto, frete e análise geográfica – concluímos:

**🛑 ➡️ A loja com o pior desempenho geral é a Loja 4**


>Justificativas principais:

Desempenho inferior em faturamento

Avaliação de clientes menor que a das demais

Mix de produtos menos forte

Produtos com menor participação no faturamento geral

✅ **Recomendação Final**

Recomenda-se que o Sr. João venda a Loja 4, pois é a menos lucrativa, tem as avaliações mais baixas, contribui menos para o crescimento da rede e possui os piores indicadores entre todas as lojas analisadas.

➡️ **Com a venda da Loja 4, o Sr. João poderá reinvestir em:**

Melhorias nas lojas mais lucrativas

Expansão de categorias

Otimização logística

Novos produtos e campanhas
