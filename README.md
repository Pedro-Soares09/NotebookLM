Projeto de Curadoria e Engenharia de Prompts aplicado à Ciência de Dados via NotebookLM.

Contexto e Objetivos
Este projeto é o resultado de uma imersão teórica e prática em Análise de Dados. O objetivo central foi utilizar o NotebookLM como uma ferramenta de síntese inteligente para explorar o ciclo de vida dos dados — desde a ingestão e limpeza até a visualização estratégica. Busquei consolidar conceitos de estatística descritiva e manipulação de bases de dados, focando na transformação de dados brutos em insights acionáveis.

Curadoria de Fontes
Para garantir a precisão das análises e o suporte teórico, selecionei e processei as seguintes fontes abertas:

Documentação Técnica do Pandas: Guia oficial para manipulação de DataFrames e séries temporais.

Fundamentos de Estatística Descritiva (Artigo Acadêmico): Base teórica para cálculos de média, mediana, desvio padrão e variância.

Guia de Visualização de Dados (Storytelling with Data): Melhores práticas para a escolha de gráficos e comunicação visual de resultados.

Dataset Exemplo (Kaggle/Open Source): Base de dados em CSV utilizada para testar os prompts de limpeza e extração de padrões.

Engenharia de Prompts e "Cicatrizes"
Nesta seção, documento o raciocínio por trás da interação com a IA, demonstrando que o resultado é fruto de um refinamento técnico (Troubleshooting).

Variações de Prompts Testadas
Prompt de Extração: "Atue como um Cientista de Dados Sênior. Analise o documento de estatística e resuma como identificar a distribuição normal em um conjunto de dados."

Prompt de Refinamento: "O resumo anterior foi muito teórico. Reformule focando em exemplos práticos de código Python usando a biblioteca Seaborn."

"Cicatrizes" (Troubleshooting)
Durante o processo, identifiquei que a IA tendia a generalizar o tratamento de valores nulos (NaN). Documentei que, para dados financeiros, o comando simples dropna() poderia causar perda de dados críticos. Ajustei a estratégia solicitando prompts que considerassem a imputação de dados (preenchimento baseado na média ou mediana), garantindo a integridade da amostra final.

Miniguia de Estudo (Entrega Final)
Resumos Estruturados
O material consolidado abrange o pipeline fundamental:

Exploração: Identificação de tipos de variáveis (qualitativas vs. quantitativas).

Tratamento: Limpeza de ruídos e normalização de escalas.

Análise: Aplicação de correlações e testes de hipóteses.

Glossário de Conceitos Aprendidos
EDA (Exploratory Data Analysis): Investigação inicial para descobrir padrões e anomalias.

Outliers: Valores que fogem drasticamente do padrão e exigem tratamento especial.

Correlation vs. Causation: A distinção crítica de que dois eventos relacionados não necessariamente causam um ao outro.

Prompts Reutilizáveis para Revisão
"Crie um checklist de 5 passos para validar a qualidade de um novo dataset de vendas."

"Explique de forma simplificada a diferença entre Desvio Padrão e Variância, usando uma analogia com esportes."

"Gere um esqueleto de código Python para plotar um gráfico de dispersão com linha de regressão."

Dica de uso: Para manter este repositório atualizado, pretendo adicionar novos estudos de caso sempre que encontrar um dataset desafiador.
