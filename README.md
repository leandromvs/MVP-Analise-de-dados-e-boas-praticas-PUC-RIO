# MVP-Analise-de-Dados-e-Boas-Praticas  
# Trabalho Final - Análise de Dados e Pré-processamento  
**Pós-Graduação em Ciência de Dados e Analytics - PUC-Rio**

---

## 📌 Descrição

Este repositório contém o **MVP de Análise de Dados e Boas Práticas**, desenvolvido no contexto da pós-graduação em Ciência de Dados e Analytics da **PUC-Rio**.

O projeto tem como foco a construção de uma **base analítica integrada do varejo brasileiro**, combinando dados de vendas com variáveis macroeconômicas e socioeconômicas, como taxa de juros, inflação, renda, desigualdade e desemprego.

Além da análise exploratória, o trabalho enfatiza a aplicação de **boas práticas de dados**, incluindo:

- padronização e tratamento de bases públicas  
- integração de múltiplas fontes em uma tabela analítica única  
- validação de consistência e coerência dos dados  
- organização do pipeline analítico para reprodutibilidade  

Este MVP estabelece a base para o próximo estágio do projeto, voltado para **modelagem preditiva e machine learning**.

---

## 🎯 Objetivo

O objetivo principal é investigar e estruturar dados para responder perguntas como:

- É possível prever a variação das vendas do varejo com base em variáveis macroeconômicas?
- Quais fatores mais influenciam o comportamento do consumo?
- Existem diferenças relevantes entre setores do varejo?

---

## 📊 Dados Utilizados

As bases são públicas e provenientes de fontes oficiais:

- **IBGE / SIDRA**
  - Pesquisa Mensal do Comércio (PMC)
  - Renda domiciliar
  - Índice de Gini  

- **Banco Central do Brasil**
  - Taxa Selic  
  - Dólar  

- **IBGE / PNAD Contínua**
  - Taxa de desocupação  

---

## ⚙️ O que foi desenvolvido

- Construção de pipeline de dados (coleta → tratamento → integração)  
- Criação de uma **tabela analítica flat** para análise  
- Padronização de granularidade temporal (mensal)  
- Tratamento de dados faltantes e inconsistentes  
- Análise exploratória (EDA) das variáveis  
- Validação de coerência das séries temporais  

---

## 🧠 Boas Práticas Aplicadas

- Separação entre dados brutos, tratados e finais  
- Padronização de nomenclaturas  
- Código comentado e organizado  
- Validação cruzada com benchmarks econômicos  
- Estrutura preparada para evolução futura (ML)  
- Reprodutibilidade dos resultados  

---

## ✅ Observações Importantes

- Os notebooks possuem **comentários detalhados**, explicando cada etapa do processo.
- A análise prioriza consistência e coerência dos dados antes de qualquer modelagem.
- Foi realizado um esforço relevante na **integração das bases**, que representou uma das etapas mais desafiadoras do projeto.
- Assim como no projeto anterior, o versionamento poderia ter sido mais frequente — parte do desenvolvimento ocorreu em ambiente externo (ex: Colab).
- Este projeto marca uma evolução prática no uso de dados estruturados e integração de fontes públicas.

---

## 📈 Principais Insights Esperados

- Relação entre taxa de juros (Selic) e consumo  
- Impacto da inflação no varejo  
- Diferenças entre setores (ex: essenciais vs discricionários)  
- Influência da renda e desigualdade  
- Efeito do desemprego nas vendas  

---

## 🚀 Próximos Passos

- Evoluir para modelagem preditiva mais apurada  
- Testar modelos de regressão mais aderentes  
- Avaliar importância de variáveis  
- Explorar análises mais granulares por setor, ex: Setor automotivo  

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- APIs públicas (IBGE / Banco Central)  

---

## 👨‍💻 Autor

**Leandro Maldonado Vieira dos Santos**  

Projeto desenvolvido como parte da pós-graduação, com foco em análise de dados, integração de bases públicas e aplicação de boas práticas em ciência de dados.

---
