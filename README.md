# Market Basket Analysis com Apriori

## 📖 Descrição

Este projeto tem como objetivo aplicar a técnica de **Market Basket Analysis** utilizando o algoritmo **Apriori** para identificar padrões de compra em um supermercado. A análise permite descobrir quais produtos são frequentemente comprados em conjunto, auxiliando na tomada de decisões estratégicas relacionadas à organização das gôndolas, promoções e vendas.

Este trabalho foi desenvolvido como atividade acadêmica utilizando Python e Google Colab.

---

## 🎯 Objetivos

- Explorar um conjunto de dados de compras de supermercado;
- Aplicar o algoritmo Apriori para encontrar conjuntos frequentes de produtos;
- Gerar regras de associação entre os produtos;
- Interpretar as métricas de suporte, confiança e lift;
- Propor ações estratégicas para melhorar as vendas do supermercado.

---

## 📂 Dataset

O conjunto de dados utilizado contém **1000 transações** de compras realizadas em um supermercado.

Cada linha representa uma compra e cada coluna representa um produto.

Os valores são binários:

- **1** → Produto comprado;
- **0** → Produto não comprado.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Mlxtend (Apriori)

---

## 📊 Etapas da Análise

1. Importação e exploração do dataset;
2. Limpeza e preparação dos dados;
3. Identificação dos produtos mais frequentes;
4. Aplicação do algoritmo Apriori;
5. Geração das regras de associação;
6. Análise das métricas (Suporte, Confiança e Lift);
7. Interpretação dos resultados para tomada de decisão.

---

## 📈 Resultados

A análise permitiu identificar padrões de compra entre diferentes produtos do supermercado.

As regras de associação encontradas podem ser utilizadas para:

- Organizar melhor o layout das gôndolas;
- Criar promoções combinadas;
- Incentivar vendas cruzadas (Cross Selling);
- Aumentar o ticket médio dos clientes;
- Apoiar decisões estratégicas baseadas em dados.

---

## 📁 Estrutura do Projeto

```
market-basket-analysis-supermercado/
│
├── README.md
├── market_basket_analysis.ipynb
├── basket_supermercado_1000.csv
└── requirements.txt
```

---

## ▶️ Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/SEU-USUARIO/market-basket-analysis-supermercado.git
```

2. Abra o notebook no Google Colab ou Jupyter Notebook.

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute todas as células do notebook.

---

## 👨‍💻 Autor

**Adriano Carlos Silva**

Projeto desenvolvido como atividade acadêmica de Ciência de Dados utilizando o algoritmo Apriori para análise de cesta de compras.
