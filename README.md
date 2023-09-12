# Análise com regressão logística de uma base de dados de doenças cardíacas
Este é um notebook Jupyter que contém uma análise de regressão logística utilizando a linguagem Python. O notebook aborda várias etapas da análise de dados e modelagem, incluindo:

## Objetivo
O objetivo principal deste notebook é realizar uma análise de regressão logística usando um conjunto de dados que descreve informações médicas e diagnósticos de doenças cardíacas. Vamos explorar o processo de construção, avaliação e interpretação de um modelo de regressão logística.

## Conteúdo do Notebook

### Carregamento dos Dados e Pré-processamento

* Os dados são carregados de uma URL e pré-processados para criar uma variável de resposta binária (flag_doente) a partir da variável "num".

### Análise Bivariada de Variáveis Qualitativas

* É solicitada a criação de uma função que realiza uma análise bivariada entre a variável de resposta e variáveis qualitativas. A função retorna um DataFrame com os resultados.

### Análise Bivariada de Variáveis Quantitativas Contínuas

* É solicitada a criação de uma função que categoriza variáveis quantitativas contínuas, como a idade (age), em grupos. O número de grupos é um parâmetro personalizável.

### Construção de um Modelo de Regressão Logística

* Um modelo de regressão logística é construído com base em várias variáveis explicativas, incluindo variáveis qualitativas (sex, cp, trestbps) e a variável quantitativa categorizada (age). Os parâmetros do modelo são interpretados.

### Avaliação da Calibração do Modelo

* A calibração do modelo é avaliada calculando as probabilidades de evento previstas, categorizando-as em grupos e comparando as taxas de eventos observadas e esperadas por grupo.

### Avaliação da Discriminação do Modelo

* A acurácia, GINI e KS do modelo são calculados para avaliar sua capacidade de discriminação.

### Melhoria do Modelo

* Uma tentativa de melhoria do modelo é feita inserindo ou removendo variáveis, e as características do novo modelo são avaliadas.
