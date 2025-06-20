# 📊 Análise de Vendas da Amazon

Este projeto realiza uma análise exploratória em um conjunto de dados de vendas da Amazon, com o objetivo de **extrair insights relevantes** para apoiar a área de **vendas** e definir melhores **estratégias de produto**.

---

## 🎯 Objetivo

O projeto visa:

- Compreender o comportamento de vendas por categoria.
- Avaliar o impacto dos descontos nos preços e nas avaliações dos produtos.
- Investigar padrões de compra e preferências dos usuários.
- Identificar produtos com maior volume de vendas e melhor avaliação.
- Gerar visualizações que ajudem a comunicar esses insights de forma clara.

---

## 🗃 Dados Utilizados

O dataset contém informações detalhadas sobre produtos vendidos na Amazon, incluindo:

- `product_id` — ID do produto  
- `product_name` — Nome do produto  
- `category` — Categoria do produto  
- `actual_price` — Preço original  
- `discounted_price` — Preço com desconto  
- `discount_percentage` — Percentual de desconto  
- `rating` — Avaliação média  
- `rating_count` — Número de avaliações  
- `user_id` — ID do usuário  
- `user_name` — Nome do usuário  

---

## 🧹 Etapas da Análise

1. **Carregamento dos dados**
2. **Limpeza e tratamento**:
   - Remoção de valores nulos
   - Correção de tipos de dados
3. **Análise exploratória (EDA)**:
   - Distribuições por categoria e preço
   - Relação entre desconto e avaliação
   - Produtos mais vendidos e melhor avaliados
4. **Geração de gráficos e dashboards**:
   - Gráficos de barras, pizza, dispersão e heatmaps
   - Visualização das métricas-chave

---

## 📊 Exemplos de Insights

- Produtos com **descontos acima de 40%** têm avaliações ligeiramente maiores.
- A **categoria mais vendida** apresenta também a maior concentração de avaliações negativas.
- Produtos com **preços originais mais altos** tendem a receber mais avaliações quando o desconto é expressivo.

---

## 🛠 Tecnologias e Bibliotecas Utilizadas

- **Python 3**
- `pandas` — manipulação de dados  
- `numpy` — operações numéricas  
- `matplotlib` / `seaborn` — visualizações  
- `plotly` — gráficos interativos (opcional)
- (Opcional: Power BI ou Excel para dashboards visuais)

---

