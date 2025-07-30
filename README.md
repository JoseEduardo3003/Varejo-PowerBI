# 🛒 Painel Executivo de Vendas em Varejo - Power BI
Este dashboard apresenta uma visão abrangente sobre vendas de uma rede de varejo registradas entre 2016 e 2021. A análise inclui produtos, perfomance de lojas, perfil de cliente e uma visão geral das vendas tanto na moeda local quanto num contexto geral, padronizadas em dólar. 

---

## 🧩 Sobre os Dados

Disponível em: [www.mavenanalytics.io/data-playground](https://www.mavenanalytics.io/data-playground)
O dataset contém cinco planilhas com dados referentes à:
- Vendas Realizadas (produto, loja, cliente)
- Clientes 
- Lojas
- Produtos
- Conversão das moedas locais para Dólar (USD)

---

## 🎯 Objetivos da Análise

- Monitorar o desempenho de vendas.
- Identificar lojas com os maiores rendimentos.
- Identificar produtos com maior volume de vendas e sua lucratividade.
- Observar as principais características do perfil do cliente.
- Analisar o desempenho geral ao longo do tempo.

---

## 📌 Principais KPIs
- 💰 Receita Total no período
- ✅ Número de pedidos e produtos
- 💰 Ticket Médio e Receita Média para cliente, produto e loja
- ✅ Número total e média de pedidos por cliente.

---

## 📈 Visões Criadas

- **Painel Geral interativo de Vendas entre 2016 e 2021**
- **Análise por Loja**
- **Análise por Produto**
- **Análise por Cliente**
- **Análise Geral levando em consideração a Moeda Local**

---

## 🛠️ Ferramentas Utilizadas

- **MySQL**
- Leitura dos arquivos CSV
- ETL para cada arquivo
- Exportação para formato CSV novamente, já com os dados tratados.

- **Power BI Desktop**
- Power Query para colunas extras (Linguagem M)
- Medidas DAX
- Visualizações interativas

---

## 📚 Dicionário de Dados
Este projeto usa 5 tabelas principais:

- **fVendas**: dados de pedidos, produtos, datas e moeda.
- **dClientes**: dados demográficos dos clientes.
- **dProdutos**: especificações de produtos e categorias.
- **dLojas**: localização e tamanho das lojas.
- **dConversaoMoeda**: taxa de câmbio em relação ao USD.

Para o dicionário completo, veja [aqui](./data_dictionary.md).

---

## 📷 Preview do Dashboard
![Dashboard PowerBI](imagens_dashboardpbi/paginainicial_pbi.PNG)
![Dashboard PowerBI](imagens_dashboardpbi/visaogeral_pbi.PNG)
![Dashboard PowerBI](imagens_dashboardpbi/vendedores_pbi.PNG)
![Dashboard PowerBI](imagens_dashboardpbi/produtos_pbi.PNG)
![Dashboard PowerBI](imagens_dashboardpbi/clientes_pbi.PNG)

---

## 🗂️ Arquivo
[`projeto_CRM.pbix`](./projeto_CRM.pbix)

---

## 🎯 Insights Obtidos
- Ciclo de Fechamento é de **45 dias**, porém existe uma grande parcela (43%) abrangendo um período de até 15 dias.
- **Junho** foi o mês com mais vendas no ano.
- Dentre os vendedores, para grandes faturamentos destaca-se **Darcel Schlecht** e para menores **Lajuana Vencill**.
- Os produtos mais vendidos são da categoria **GTX**, se destacando tanto em volume de vendas quando em receita.
- O país que mais comprou foi disparadamente os **Estados Unidos**.
- Empresas de **médio porte** representaram a maior parte das vendas.
