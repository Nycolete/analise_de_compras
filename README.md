# 🛍️ Análise de Tendências de Compra

## 📌 Sobre o projeto

Este projeto tem como objetivo realizar uma **Análise Exploratória de Dados (EDA)** sobre o comportamento de compra de clientes, buscando identificar padrões relacionados a características dos consumidores e aos seus hábitos de compra.

A partir da análise, busco transformar os dados em **insights que possam apoiar decisões de negócio**, como estratégias de relacionamento, promoções, cupons e entendimento do comportamento dos clientes.

O projeto foi desenvolvido utilizando Python e bibliotecas voltadas para análise e visualização de dados.

---

## 🎯 Objetivos

A análise busca responder algumas perguntas sobre o comportamento dos clientes:

* Qual a frequência de compra mais comum?
* Quais características aparecem com maior frequência entre os clientes que compram semanalmente?
* Qual é o método de pagamento mais utilizado?
* Como o uso de cupons se distribui entre diferentes faixas etárias?
* Existe alguma diferença relevante no comportamento de compra entre as estações do ano?
* Quais padrões podem ser observados a partir do cruzamento dessas características?

---

## 🔎 Etapas da análise

### 1. Conhecendo os dados

Inicialmente, foi realizada uma análise exploratória da base para entender:

* Estrutura do dataset;
* Tipos das variáveis;
* Quantidade de registros;
* Variáveis numéricas e categóricas;
* Distribuição inicial dos dados.

Foram utilizadas funções como:

```python
df.info()
df.describe(include='all')
```

---

### 2. Análise da frequência de compras

Foi analisada a distribuição das diferentes frequências de compra dos clientes.

A frequência **trimestral** aparece como uma das categorias mais frequentes, representando aproximadamente 15% dos registros. Apesar disso, as categorias apresentam uma distribuição relativamente equilibrada.

Essa análise ajuda a entender que o comportamento de compra não está concentrado em apenas uma frequência.

---

### 3. Análise dos métodos de pagamento

Também foi investigada a utilização dos diferentes métodos de pagamento.

O **PayPal** aparece como o método mais utilizado, representando aproximadamente **17,35% dos registros**.

Apesar de ser o método com maior participação, as diferenças entre os métodos são relativamente pequenas, indicando uma distribuição diversificada.

**Insight de negócio:** manter diferentes opções de pagamento pode contribuir para atender perfis variados de consumidores.

---

### 4. Clientes que realizam compras semanalmente

Para aprofundar a análise, foi criado um recorte considerando os clientes com **frequência de compra semanal**.

A análise considera medidas como:

* Média;
* Mediana;
* Moda;
* Distribuição das idades;
* Comparação entre gêneros.

Um dos pontos observados foi a diferença entre as idades mais frequentes dos grupos analisados.

Essa etapa também demonstra a importância de escolher corretamente a medida estatística utilizada. A **moda** foi utilizada para identificar a idade que aparece com maior frequência, enquanto a **média** representa a idade média do grupo.

**Possível aplicação de negócio:** a identificação dos perfis mais frequentes entre compradores semanais pode ajudar a explorar estratégias de relacionamento e fidelização.

---

### 5. Análise por estação do ano

Também foi analisada a distribuição dos registros de compra entre as estações do ano.

A **primavera** apresenta a maior quantidade de registros, porém as diferenças entre as estações são pequenas.

Dessa forma, os dados analisados não indicam uma concentração muito forte das compras em uma única estação.

---

## 🛠️ Tecnologias utilizadas

* **Python**
* **Pandas**
* **Matplotlib**
* **Jupyter Notebook**

### Principais recursos utilizados

* `value_counts()`
* `groupby()`
* `agg()`
* `mode()`
* `mean()`
* `median()`
* `crosstab()`
* `describe()`
* Filtragem e criação de subconjuntos
* Visualização de dados

---

## 📈 Principais aprendizados

Além dos insights encontrados na base, o projeto foi importante para praticar conceitos fundamentais de análise de dados, como:

* Exploração e entendimento de uma base;
* Análise de variáveis categóricas e numéricas;
* Uso de medidas estatísticas;
* Comparação entre grupos;
* Análise proporcional;
* Criação de visualizações;
* Interpretação dos resultados;
* Transformação de resultados técnicos em possíveis insights de negócio.

Um dos principais aprendizados foi entender que **encontrar o maior valor em uma análise não significa necessariamente encontrar um padrão relevante**. É importante observar a distribuição dos dados, o tamanho dos grupos e o contexto antes de tirar conclusões.

---

## 💡 Próximos passos

Como evolução do projeto, algumas análises que podem ser exploradas são:

* Relação entre uso de cupons e frequência de compra;
* Comparação do valor de compra entre clientes que utilizam e não utilizam descontos;
* Análise de categorias de produtos por faixa etária;
* Relação entre idade e valor gasto;
* Análise de comportamento de compra por estação;
* Identificação de segmentos de clientes com comportamentos semelhantes;
* Criação de um dashboard para apresentação dos principais indicadores.

---

## 👩‍💻 Sobre

Projeto desenvolvido como parte da minha jornada de estudos em **Análise de Dados e Ciência de Dados**, com foco no desenvolvimento de habilidades em Python, análise exploratória, estatística e interpretação de dados.

A proposta é praticar não apenas a parte técnica, mas também a capacidade de transformar dados em informações que possam contribuir para a tomada de decisão.

