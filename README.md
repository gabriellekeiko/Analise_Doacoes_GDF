# Análise Histórica de Doações Recebidas pelo GDF (2020 - 2026)

Este repositório contém o projeto final da disciplina de **Introdução à Ciência de Dados**. O objetivo principal é analisar a evolução temporal, o volume financeiro e o perfil das doações externas incorporadas ao patrimônio público do Governo do Distrito Federal.

## Sobre o Conjunto de Dados

Os dados são públicos e foram extraídos do **Sistema Integrado de Gestão Governamental (SIGGO)**, sendo disponibilizados pela **Secretaria de Estado de Economia do Distrito Federal**. O *dataset* consolidado compreende o período de 2020 a 2026, possuindo um volume total aproximado de **3.400 registros** estruturados em **23 colunas**.

A base de dados detalha a natureza das doações (bens móveis, imóveis ou de consumo) destinadas aos órgãos locais através de variáveis-chave:
* **Variáveis Categóricas:** `DS_UNIDADE_GESTORA` (entidade beneficiada) e `DS_CONTA_CONTABIL` (tipo de bem).
* **Variáveis Temporais:** `NR_ANO_STATUS` (ano) e `NR_MES` (mês da transação).
* **Variáveis Numéricas:** `VL_CREDITO` e `VL_DEBITO` (valores financeiros associados).

## Pergunta Orientatória

1. > **"Como o volume financeiro e a quantidade de doações recebidas pelo Governo do Distrito Federal evoluíram entre os anos de 2020 e 2026?"**

2. > *Houve uma concentração atípica de doações destinadas às áreas de Saúde e Assistência Social durante os anos críticos da pandemia (2020-2022) em comparação aos anos seguintes?*

3. > *Como a distribuição mensal das doações nos anos de 2020 e 2021 reflete os períodos de pico das ondas de contágio no Distrito Federal?*

## Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python
* **Manipulação e Limpeza de Dados:** `pandas`, `numpy`
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Ambiente de Desenvolvimento:** Jupyter Notebook / Google Colab

## Etapas do Projeto

1.  **Data Wrangling:** Importação, limpeza e empilhamento dos arquivos anuais (2020-2026).
2.  **Análise Exploratória (EDA):** Investigação de estatísticas descritivas básicas e comportamento das doações.
3.  **Análise Temporal:** Mapeamento de picos de doações e sazonalidade ao longo dos meses e anos.
4.  **Visualização de Dados:** Geração de gráficos de linha, barras e distribuições para responder à pergunta central.

---
## Autoria
Este projeto foi desenvolvido por:
* *Gabrielle Keiko*
  * Aluna de Ciência de Dados e Machine Learning no *CEUB*
  * Introdução a Ciência de Dados 2026
  * E-mail institucional: gabrielle.keiko@sempreceub.com | E-mail pessoal: gkeiko.05@gmail.com
  * Meu Perfil no LinkedIn: https://www.linkedin.com/in/gabrielle-keiko-9baa6a2b3/
