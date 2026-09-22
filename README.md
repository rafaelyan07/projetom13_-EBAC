# 🛒 Análise Exploratória de Preços de Supermercado

Projeto do módulo 13 (**Fundamentos da Descoberta de Dados**) da formação **Profissão Cientista de Dados (EBAC)**.

Análise de uma base de produtos de um supermercado do Chile, aplicando estatística descritiva e visualização de dados para entender a distribuição de preços e descontos por categoria.

## 🎯 Perguntas respondidas
1. Média e mediana do preço por categoria: onde a média fica acima ou abaixo da mediana?
2. Desvio padrão por categoria e o comportamento de média e mediana nas categorias mais dispersas
3. Boxplot da categoria com maior desvio padrão e identificação de outliers
4. Média de descontos por categoria (gráfico de barras)

## 🔍 Principais achados
- Em quase todas as categorias a **média fica acima da mediana**, sinal de distribuição assimétrica à direita, puxada por produtos mais caros.
- **Laticínios** tem a maior dispersão (desvio padrão ≈ 3.926, maior que a própria média) e a maior diferença entre média (2.385) e mediana (989).
- Pelo critério de 1,5 × IQR, **43 de 447 produtos de laticínios (~10%) são outliers**, principalmente packs com 12 unidades.
- **Comidas preparadas** é a única categoria com média abaixo da mediana.

## 🛠️ Stack
Python · pandas · Matplotlib · Plotly · Jupyter Notebook

## ▶️ Como executar
1. Instale as dependências: `pip install pandas matplotlib plotly jupyter`
2. Coloque o CSV da base na mesma pasta do notebook
3. Abra `Profissao Cientista de Dados M13 Projeto.ipynb` no Jupyter

---
Feito por [Rafael Yan](https://linkedin.com/in/rafaelycn)
