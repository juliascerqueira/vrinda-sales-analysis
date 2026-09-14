# Vrinda Sales Analysis

[English](README_EN_US.md) | **Português**

### Projeto de Análise de Dados e Dashboard Interativo em Excel

Neste projeto, utilizei uma base de dados disponibilizada no Kaggle com informações de vendas de uma loja fictícia chamada **Vrinda**. O objetivo foi analisar o desempenho das vendas ao longo de 2022 e identificar oportunidades a partir do perfil dos clientes, dos produtos vendidos, dos canais de venda e da distribuição geográfica das vendas.

O projeto foi desenvolvido em **Microsoft Excel** e inclui preparação e análise exploratória dos dados, construção de um dashboard interativo e uma apresentação executiva com os principais resultados.

---

## Dashboard

![Dashboard de Vendas Vrinda](images/Vrinda_Dashboard.png)

O dashboard permite acompanhar os principais indicadores de vendas e explorar os resultados por **mês** e **status da venda**.

---

## Principais Resultados

- **92,25%** dos registros de vendas foram classificados como Delivered, enquanto Returned, Cancelled e Refunded representam uma parcela significativamente menor. A participação de devoluções, porém, apresentou crescimento ao longo do ano.

- **Mulheres representam aproximadamente 69,4%** dos registros Delivered, constituindo o principal perfil de gênero observado na base. Adultos representam aproximadamente metade dos registros Delivered e apresentam idade média de **40 anos**.

- **Set, Kurta e Western Dress** concentram aproximadamente **86,6% dos itens vendidos** entre os registros Delivered, mostrando forte concentração em poucas categorias.

- **Amazon, Myntra e Flipkart** concentram aproximadamente **80,4% do valor de vendas** dos registros Delivered.

- **Maharashtra, Karnataka e Uttar Pradesh** apresentam os maiores valores de vendas entre os estados, concentrando aproximadamente **36,5% do valor de vendas** dos registros Delivered.

---

## Ferramentas e Técnicas

- Microsoft Excel
- Limpeza e padronização de dados
- Fórmulas do Excel
- Tabelas e gráficos dinâmicos
- Segmentação de dados e listas personalizadas
- Análise exploratória de dados
- Construção de dashboard interativo
- Visualização de dados e comunicação dos resultados

---

## Preparação dos Dados

Antes da análise, a base foi revisada para identificar possíveis inconsistências, duplicidades, valores nulos e problemas de padronização.

Não foram encontrados registros totalmente duplicados ou valores nulos. Foram padronizados nomes de categorias, cidades e estados, além da criação de uma coluna auxiliar com os meses em inglês para utilização nas análises e no dashboard.

Também foram identificadas inconsistências nos campos `Order ID` e `Cust ID`. Como não havia informações suficientes para determinar os valores corretos, esses campos foram considerados uma limitação da base e não foram corrigidos nem utilizados como identificadores únicos.

---

## Análise

A análise exploratória buscou entender o desempenho das vendas em 2022 a partir de diferentes perspectivas, incluindo:

- Evolução mensal das vendas
- Status das vendas
- Gênero e faixa etária dos clientes
- Categorias e tamanhos dos produtos
- Canais de venda
- Distribuição geográfica

A partir das análises, foram selecionados os principais indicadores e dimensões para a construção do dashboard interativo e da apresentação executiva.

---

## Qualidade dos Dados e Limitações da Análise

Foram identificadas inconsistências entre `Order ID`, `Cust ID` e alguns atributos associados aos clientes. Como não havia informações suficientes sobre a origem e a estrutura dos dados para determinar quais registros estariam corretos, nenhuma linha foi excluída com base nesses identificadores.

Por esse motivo, `Order ID` e `Cust ID` não foram considerados identificadores únicos. As análises foram realizadas no **nível de registro de venda**, evitando métricas que dependessem da identificação única de pedidos ou clientes.

A base também não possui informações sobre estoque ou disponibilidade dos produtos. Por isso, não é possível concluir se um produto vendeu pouco por ter baixa procura ou por estar com pouca disponibilidade.

Além disso, apesar de ser possível acompanhar os registros com status Returned, Cancelled e Refunded, a base não informa o motivo dessas ocorrências. Assim, foi possível identificar o aumento das devoluções no final do ano, mas não determinar suas causas com os dados disponíveis.

---

## Arquivos do Projeto

- **[Análise e Dashboard Interativo em Excel](Vrinda_Sales_Analysis.xlsx)** — arquivo completo com análise exploratória, tabelas dinâmicas, dicionário de dados, base padronizada e dashboard interativo.

- **[Relatório Executivo de Vendas](Vrinda_Sales_Report.pdf)** — apresentação com os principais resultados, áreas a serem exploradas para crescimento das vendas e pontos que demandam investigação adicional.

---

## Base de Dados

A base de dados original está disponível publicamente no Kaggle:

**Vrinda Store Data Analysis**  
Fonte: [Kaggle Dataset](https://www.kaggle.com/datasets/nisshaachoudhary/store-data-analysis-using-ms-excel)

---

## Sobre o Projeto

Este projeto faz parte do meu portfólio de análise de dados e foi desenvolvido com foco na aplicação do Excel ao longo do processo de análise, desde a preparação e exploração dos dados até a construção do dashboard e a comunicação dos principais resultados.

---

**Julia Cerqueira**  
Análise de Dados | Business Intelligence  
[LinkedIn](https://www.linkedin.com/in/juliascerqueira/)
