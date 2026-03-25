# 📊 Análise de Vendas — Superstore

Projeto de limpeza e análise exploratória de dados (EDA) sobre vendas de uma loja fictícia americana, utilizando Python e bibliotecas de visualização.

---

## 🎯 Objetivo

Explorar o dataset Superstore para identificar padrões de receita, comportamento regional, sazonalidade e o impacto de descontos sobre o lucro — gerando insights acionáveis para o negócio.

---

## 🗂️ Dataset

- **Fonte:** [Kaggle — Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Volume:** 9.994 registros, 21 colunas
- **Período:** 2014 a 2017
- **Variáveis principais:** categoria de produto, região, data do pedido, valor de venda, desconto e lucro

---

## 🔍 Perguntas Analisadas

### 1. Quais categorias de produto geram mais receita?

Office Supplies lidera em volume de pedidos, mas **Technology** gera a maior receita total — indicando um ticket médio significativamente mais alto nessa categoria.

### 2. Qual região tem mais pedidos?

A região **West** concentra o maior número de pedidos, seguida de East, Central e South. Estratégias de expansão e retenção devem priorizar essa região.

### 3. Existe sazonalidade nas vendas por mês?

Sim. O período de **setembro a dezembro** concentra os maiores volumes de vendas, sugerindo forte influência de datas comemorativas (Black Friday, Natal). Lançamentos e campanhas promocionais devem ser direcionados a esse período.

### 4. Descontos altos estão associados a prejuízo?

A correlação entre desconto e lucro é de **-0.22** — fraca, mas negativa. Produtos da categoria **Furniture** concentram a maior parte dos casos com desconto ≥ 20% e lucro negativo, indicando necessidade de revisão na política de precificação dessa categoria.

---

## 📈 Visualizações

| Gráfico | Descrição |
|---|---|
| Bar chart | Receita total por categoria de produto |
| Bar chart | Quantidade de pedidos por região |
| Bar chart | Volume de vendas por mês |
| Scatter plot | Relação entre desconto e lucro |

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 💡 Principais Insights

- **Technology** gera mais receita com menos pedidos — alto ticket médio
- **West** é a região mais ativa em volume de pedidos
- As vendas têm pico entre **setembro e dezembro**
- Descontos acima de 20% em **Furniture** frequentemente resultam em prejuízo — revisar precificação dessa categoria pode melhorar a margem

---

## 👤 Autor

Feito por **[Lucas Americano]**  
[LinkedIn](https://linkedin.com/in/americanlucas) • [GitHub](https://github.com/americanlucas)
