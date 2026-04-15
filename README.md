# 📊 Análise de Vendas — Mini Mercado

Projeto completo de ETL e análise exploratória de dados de vendas de um mini mercado, 
cobrindo desde a limpeza dos dados brutos até a geração de insights de negócio.

## 🛠️ Ferramentas Utilizadas
- Microsoft Excel
- Power Query (ETL)
- Tabelas Dinâmicas
- PROCV
- Formatação Condicional

## 📁 Estrutura do Projeto
| Aba | Descrição |
|-----|-----------|
| Dados brutos | Base original com erros preservada |
| Dados limpos | Base tratada via Power Query |
| Categoria | Análise de vendas por categoria |
| Vendedores | Desempenho e ranking de vendedores |
| Venda por vendedor | Cruzamento vendedor × mês |
| Loja | Vendas por unidade |
| Top 20 itens | Produtos com maior faturamento e volume |
| Desconto | Análise de descontos por vendedor |
| Venda x meta | Comparativo mensal vs metas com % atingido |
| Metas_2024 | Base de metas por loja |

## 🧹 Etapa 1 — Limpeza com Power Query
- Remoção de valores nulos em Data e Quantidade
- Tratamento de preços negativos com flag de auditoria
- Padronização de texto (categorias, vendedores, gramagem)
- Remoção de duplicatas e quantidades zeradas
- Recriação da coluna Total com fórmula correta
- Substituição de datas vazias com coluna "Faltou data?"

## 📊 Etapa 2 — Análise Exploratória
- Análise por categoria com frequência absoluta, relativa e acumulada
- Ranking de vendedores por faturamento e volume de transações
- Cruzamento vendedor × mês para identificar sazonalidade
- Top 20 produtos por faturamento e quantidade
- Análise de descontos por vendedor
- Comparativo mensal de vendas vs metas com % de atingimento

## 💡 Principais Insights
- Mercearia é a categoria com maior volume de transações (21,6%)
- Fernanda Dias lidera em faturamento anual mas não em todos os trimestres
- Fralda Pampers é o produto com maior faturamento — alto valor unitário
- Café Pilão lidera em quantidade vendida
- Loja Norte concentra 37,4% do faturamento total
- Metas estipuladas estão 989% acima do realizado — revisão necessária

## 🚀 Próximos Passos
- [ ] Dashboard interativo no Power BI *em andanmento*
- [ ] Análise com SQL

## 👤 Autor
**Caio Cesar Silva e Souza**  
Analista de Dados em formação | Excel • Power Query • SQL • Power BI  
[LinkedIn](https://www.linkedin.com/in/cacesouza/)
