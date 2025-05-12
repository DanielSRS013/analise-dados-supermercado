# 🛒 Análise de Vendas com Pandas

Este projeto é uma análise exploratória de dados de vendas de supermercado, usando Python e a biblioteca Pandas. O objetivo é entender o comportamento de vendas por cidade, produto, cliente e período, extraindo insights úteis para o negócio.

## 📊 Objetivos

- Praticar leitura, limpeza e manipulação de dados com Pandas
- Identificar padrões de venda por produto, cidade e tipo de cliente
- Criar colunas derivadas e interpretar dados temporais
- Visualizar informações com gráficos

## 🧪 Técnicas aplicadas

- Leitura e tratamento de dados com `pandas`
- Conversão e manipulação de datas (`pd.to_datetime`)
- Agrupamentos com `groupby()`
- Criação de coluna (`Month`)
- Visualizações com `matplotlib.pyplot`
- Cálculo de totais, médias e contagens

## 📈 Exemplos de análises

- Receita total por cidade e por produto
- Faturamento médio por tipo de cliente
- Linhas Produtos mais vendidas (em quantidade e valor)
- Dias da semana com maior volume de vendas

## 📎 Dataset utilizado

Dataset de vendas disponível publicamente, com informações como:
- Data da venda
- Cidade, gênero e tipo de cliente
- Produto, quantidade e valor total
- Método de pagamento

> *O dataset simula operações de vendas em três filiais de supermercado por 3 meses.*

## 📌 Conclusões

- Produtos da linha Health and Beauty apresentaram maior receita média.
- A cidade de Yangon gerou o maior faturamento total.
- Clientes membros apresentaram um ticket médio ligeiramente superior.

## 🚀 Como executar

1. Faça o clone deste repositório:
```bash
git clone https://github.com/seu-usuario/analise-vendas-pandas.git
```

2. Instale os pacotes necessários (se necessário):
```bash
pip install pandas matplotlib
```

3. Execute o notebook `Análise_de_Vendas_com_Pandas.ipynb` em seu ambiente Jupyter ou Google Colab.

---

**Autor:** Daniel Souza da Rocha Silva
