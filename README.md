# 🛒 Instacart — Análise de Padrões de Compra

## 📌 Contexto
O Instacart é uma plataforma de entrega de supermercado onde os clientes realizam pedidos recorrentes.
Este projeto tem como objetivo analisar padrões de compra dos usuários, comportamento de recompra e características dos pedidos, a partir de dados reais da plataforma.

O trabalho foi desenvolvido em Jupyter Notebook, com foco em análise exploratória de dados (EDA) e geração de insights de negócio.

---

## 🎯 Objetivos
- Entender o comportamento de compra dos clientes
- Identificar padrões de pedidos ao longo do tempo
- Analisar frequência de recompra de produtos
- Explorar distribuições de pedidos, dias da semana e horários

---

## 🧰 Ferramentas e Tecnologias
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 🔎 Etapas da Análise
- Carregamento e inspeção dos datasets
- Limpeza e validação dos dados
- Análise de valores ausentes e duplicados
- Exploração de variáveis temporais (dias da semana e horários)
- Análise de frequência de pedidos e recompra
- Visualização dos principais padrões de consumo

---

## 📊 Principais Insights
- A maioria dos pedidos ocorre em horários específicos do dia
- Existem dias da semana com maior concentração de compras
- Produtos reaparecem com frequência nos pedidos dos usuários, indicando comportamento recorrente
- O volume de pedidos varia significativamente entre usuários

---

## ▶️ Como Executar o Projeto
1. Clone este repositório:

git clone https://github.com/seu-usuario/instacart-project.git
Instale as dependências:


pip install -r requirements.txt
Abra o notebook:

jupyter notebook instacart_project.ipynb

📌 Observações
Este projeto tem fins educacionais e de portfólio, com foco em análise de dados e interpretação de resultados.

Conclusões a partir da análise:

Neste projeto, conseguimos informações importantíssimas sobre as vendas do Instacart.

Começando pela que acredito ser a mais relevante, descobrimos que os usuários do app tem grande preferência por:
- Produtos orgânicos
- Produtos naturais
- Frutas e verduras no geral

O que indica preferências por alimentos e um estilo de vida mais saudável. 

Também concluímos que os pedidos são mais frequentes nos primeiros dias da semana (domingo e segunda) e aos sábados, especialmente em horários comerciais, e que se observa uma queda nas vendas nos dias de "meio de semana".  Outro dado relevante é que a fidelização de clientes não parece ser alta, com a grande maioria dos clientes não passando dos 10 pedidos.

Todas estas informações podem facilitar decisões do negócio. Por exemplo, se a fidelização está baixa e os pedidos mais populares são de produtos orgânicos, talvez valha a pena direcionar a comunicação da marca para atrair o público que consome este tipo de produto. Com base nas informações que reunimos, também é possível pensar em outras estratégias, como enviar notificações push preferencialmente durante os horários comerciais e fins de semana ou oferecer cupons de desontos nas terças, quartas e quintas que são dias com menor movimento.
