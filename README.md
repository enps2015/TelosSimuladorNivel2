# TelosSimuladorNivel2

## Análise do Desempenho Escolar com PySpark e Pandas

**Descrição do Projeto:**

Este projeto utiliza o poder do PySpark para analisar um conjunto de dados de notas de alunos, buscando insights sobre a relação entre renda familiar, horas de estudo e desempenho nas disciplinas de Matemática, Português e Ciências. O projeto abrange desde a carga e tratamento dos dados até a criação de visualizações interativas com a biblioteca Plotly, proporcionando uma análise completa e visualmente atraente.

**Funcionalidades:**

* **Carga e Limpeza de Dados:**  Importação, tratamento de valores nulos e normalização de dados utilizando PySpark.
* **Análise Exploratória:**  Cálculo de estatísticas descritivas e análise de correlação entre variáveis.
* **Visualização de Dados:**  Criação de histogramas, violin plots e heatmaps com Seaborn e Plotly para ilustrar os insights encontrados.
* **Interpretação dos Resultados:**  Análise e interpretação das visualizações para compreender a relação entre as variáveis e o desempenho escolar.

**Como Executar o Projeto:**

**Requisitos:**

* Python 3.x
* Jupyter Notebook ou Google Colab

**Bibliotecas:**

* pyspark
* pandas
* matplotlib
* seaborn
* plotly

**Datasets:**

* `notas_alunos.csv` (ajuste o nome do arquivo se necessário)

**Execute o código:**

1. Abra o notebook `projeto_analise_notas.ipynb` (ajuste o nome do arquivo se necessário) no Jupyter Notebook ou Google Colab.
2. Execute as células em ordem.

**Desafios Encontrados:**

* **Tratamento de dados ausentes:** O dataset continha valores ausentes em algumas colunas, que foram tratados utilizando a mediana para variáveis numéricas e a moda para variáveis categóricas.
* **Variáveis categóricas:** A análise de correlação exigiu a transformação de variáveis categóricas em numéricas, utilizando técnicas como Ordinal Encoding.
* **Visualização de dados:** A criação de gráficos de dispersão para visualizar a relação entre renda familiar e notas apresentou desafios devido à natureza discreta da variável "RendaFamiliarNum".

**Soluções Adotadas:**

* **Imputação de valores ausentes:**  Utilização da mediana e da moda para preencher valores ausentes.
* **Ordinal Encoding:**  Conversão de variáveis categóricas ordinais para numéricas.
* **Violin Plots:**  Utilização de violin plots para visualizar a distribuição das notas em cada grupo de renda familiar.
* **Plotly:**  Criação de violin plots interativos e visualmente atraentes com a biblioteca Plotly.

**Lições Aprendidas e Próximos Passos:**

* O projeto proporcionou um aprendizado valioso sobre a utilização do PySpark para análise de dados em larga escala.
* As técnicas de visualização de dados com Seaborn e Plotly foram aprimoradas, permitindo a criação de gráficos informativos e esteticamente agradáveis.
* Próximos passos incluem a exploração de outras variáveis e técnicas de análise, como testes de hipóteses e modelos de machine learning, para aprofundar a compreensão dos fatores que influenciam o desempenho escolar.

**Desenvolvido por:**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eric-np-santos/) Eric Pimentel 

**Que a Força dos Dados esteja com você!** 🚀 ✨ 
