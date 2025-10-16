# 📊 Desafio Power BI Analyst - DIO

Este projeto faz parte do desafio **"Power BI Analyst"** da [Digital Innovation One (DIO)](https://www.dio.me/).  
O objetivo foi **reproduzir e aprimorar visuais interativos** utilizando o Power BI, explorando conceitos de modelagem, medidas DAX e design de dashboards.

---

## 🚀 Objetivo do Projeto

Criar um relatório no **Power BI** com base na amostra de dados disponibilizada no repositório oficial da DIO, desenvolvendo habilidades de:
- Construção e formatação de visuais;
- Aplicação de medidas DAX;
- Criação de mapas e gráficos de pizza;
- Organização e disposição dos elementos no layout.

---

## 🧠 Descrição do Desafio

A proposta consistiu em replicar e criar uma **terceira página de relatório** com os seguintes visuais:

1. **Mapa 1:** Soma de *Sales* (vendas) e *Units Sold* (unidades vendidas) por país  
2. **Mapa 2:** Soma de *Profit* (lucro) por país  
3. **Gráfico de Pizza:** Lucro por segmento  

Esses elementos foram montados utilizando a base de dados `financials.xlsx` disponibilizada pela instrutora no repositório:

🔗 [Repositório de dados](https://github.com/julianazanelatto/power_bi_analyst)

---

## 🛠️ Tecnologias e Ferramentas

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Excel / Dataset financials.xlsx**
- **GitHub** (para versionamento e portfólio)

---

## 📐 Medidas Criadas (DAX)

```DAX
Total Sales = SUM(financials[Sales])
Total Units = SUM(financials[Units Sold])
Total Profit = SUM(financials[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
