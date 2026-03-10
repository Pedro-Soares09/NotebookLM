

> **Projeto de Lab de Dados IA.**

Este repositório documenta a imersão teórica e prática em Análise de Dados, utilizando o **NotebookLM** como motor de síntese inteligente para o ciclo de vida dos dados.

---

##  Acesso ao Projeto
Clique no botão abaixo para visualizar o caderno interativo com todos os insights e fontes processadas:

[![NotebookLM](https://img.shields.io/badge/Acessar-NotebookLM-blue?style=for-the-badge&logo=google&logoColor=white)](https://notebooklm.google.com/notebook/f5f8461e-e230-41fe-bdd3-c7111f038576)

---

## Contexto e Objetivos
O objetivo central foi explorar o pipeline de dados — da ingestão e limpeza à visualização estratégica. Através deste material, busquei consolidar conceitos de **estatística descritiva** e **manipulação de bases de dados**, transformando dados brutos em insights acionáveis para tomada de decisão.

##  Curadoria de Fontes
Para garantir rigor técnico, o NotebookLM foi alimentado com as seguintes fontes:

*  **Documentação Técnica do Pandas:** O padrão ouro para manipulação de DataFrames.
*  **Fundamentos de Estatística Descritiva:** Base teórica para cálculos de tendência central e dispersão.
* **Guia Storytelling with Data:** Princípios de design e comunicação visual de resultados.
* **Dataset Exemplo (Kaggle):** Base prática para testes de limpeza e identificação de padrões.

---

##  Engenharia de Prompts e "Cicatrizes"
Documentação do raciocínio crítico aplicado na interação com a IA (*Troubleshooting*).

###  Variações de Prompts
* **Prompt de Extração:** *"Atue como um Cientista de Dados Sênior. Analise o documento de estatística e resuma como identificar a distribuição normal em um conjunto de dados."*
* **Prompt de Refinamento:** *"O resumo anterior foi muito teórico. Reformule focando em exemplos práticos de código Python usando a biblioteca Seaborn."*

###  "Cicatrizes" (O que aprendi com os erros)
Identifiquei que a IA tendia a generalizar o tratamento de valores nulos (`NaN`). Em contextos financeiros, o uso direto de `dropna()` causaria perda de dados críticos. Ajustei a estratégia para **Imputação de Dados** (média/mediana), garantindo a integridade da amostra final.

---

##  Miniguia de Estudo 

### Resumos Estruturados
1.  **Exploração:** Identificação de variáveis qualitativas vs. quantitativas.
2.  **Tratamento:** Limpeza de ruídos e normalização de escalas.
3.  **Análise:** Aplicação de correlações e testes de hipóteses.

###  Glossário de Conceitos
* **EDA (Exploratory Data Analysis):** Investigação inicial para descobrir padrões.
* **Outliers:** Valores atípicos que exigem tratamento ou descarte estratégico.
* **Correlation vs. Causation:** O entendimento de que correlação não implica causalidade.

###  Prompts Reutilizáveis para Revisão
> *Dica: Copie e cole os comandos abaixo no seu chat de IA para estudar.*

* `"Crie um checklist de 5 passos para validar a qualidade de um novo dataset de vendas."`
* `"Explique a diferença entre Desvio Padrão e Variância usando uma analogia com esportes."`
* `"Gere um esqueleto de código Python para plotar um gráfico de dispersão com linha de regressão."`



> **Dica de uso:** Este repositório é vivo. Pretendo adicionar novos estudos de caso e datasets desafiadores conforme o progresso nos meus estudos.
