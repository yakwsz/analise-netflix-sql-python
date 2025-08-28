# 📊 Projeto de Análise de Dados da Netflix com SQL em Python (`pandasql`)

Este repositório contém um projeto completo de análise de dados que utiliza a biblioteca `pandasql` para executar consultas SQL em um dataset da Netflix diretamente em um ambiente Python, simulando o dia a dia de um analista de dados.

O projeto foi desenvolvido inteiramente em um notebook do Google Colab e é estruturado de forma didática para guiar o usuário desde a limpeza dos dados até a execução de consultas SQL avançadas.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SEU_USUARIO/SEU_REPOSITORIO/blob/main/NOME_DO_SEU_NOTEBOOK.ipynb)

---

## 🎯 Objetivo do Projeto

O objetivo principal é demonstrar a aplicação prática de SQL para análise de dados dentro do ecossistema Python, utilizando um dataset real do Kaggle. O notebook serve como um guia de estudo e portfólio, cobrindo uma vasta gama de comandos SQL.

---

## 📚 Dataset

O dataset utilizado é o **"Netflix Movies and TV Shows"**, disponível no Kaggle. Ele contém informações sobre os títulos da Netflix, como:
- Tipo (Filme ou Série)
- Diretor
- Elenco
- País de produção
- Data de adição
- Ano de lançamento
- Duração e classificação indicativa

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Google Colab**
- **Pandas:** Para manipulação e limpeza dos dados.
- **Pandasql:** Para executar queries SQL em DataFrames do Pandas.
- **NumPy:** Para suporte a operações numéricas na fase de limpeza.

---

## 📂 Estrutura do Projeto

O notebook é dividido em 5 fases claras e sequenciais:

1.  **Fase 1: Preparação do Ambiente:** Instalação das bibliotecas e carregamento dos dados.
2.  **Fase 2: Análise Exploratória e Limpeza de Dados:** Tratamento de valores nulos, conversão de tipos de dados e criação de novas colunas para facilitar a análise.
3.  **Fase 3: Guia Completo de SQL com `pandasql`:** Uma exploração detalhada dos comandos SQL, incluindo:
    - `SELECT`, `WHERE`, `DISTINCT`, `LIMIT`
    - `ORDER BY`
    - Operadores lógicos (`AND`, `OR`, `LIKE`, `IN`, `BETWEEN`)
    - `GROUP BY` com funções de agregação (`COUNT`, `AVG`, `MAX`, `MIN`)
    - `HAVING` para filtrar grupos
    - `INNER JOIN` e `LEFT JOIN` para unir dados
    - Subqueries (consultas aninhadas)
    - `CASE WHEN` para lógica condicional
    - Funções de Janela (`RANK()`) para análises avançadas
4.  **Fase 4: Mini-Projeto de Análise:** Aplicação dos conhecimentos de SQL para responder a perguntas de negócio, como:
    - Quais são os 5 países com mais filmes?
    - Qual o diretor com mais títulos no catálogo?
    - Qual a distribuição de filmes por década?
    - E mais...
5.  **Fase 5: Preparação para Entrevistas:** Respostas para perguntas comuns de SQL em processos seletivos, com a query e a explicação detalhada.

---

## 🚀 Como Executar o Projeto

Existem duas maneiras fáceis de rodar este projeto:

**1. Usando o Google Colab (Recomendado):**
   - Clique no botão "Open in Colab" no topo deste README.
   - O notebook será aberto diretamente no ambiente do Google Colab.
   - Execute as células de código em ordem, do início ao fim.

**2. Localmente (via Jupyter Notebook):**
   - Faça o clone ou o download deste repositório.
   - Certifique-se de ter Python e Jupyter Notebook instalados.
   - Instale as bibliotecas necessárias:
     ```sh
     pip install pandas pandasql numpy
     ```
   - Abra o arquivo `.ipynb` no Jupyter Notebook e execute as células.

---

## ✍️ Autor

**Kayky (ou Kay)**

- **LinkedIn:** www.linkedin.com/in/silvakay
- **GitHub:** https://github.com/yakwsz
