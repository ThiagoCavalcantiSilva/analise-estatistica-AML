# Análise Estatística Inferencial Aplicada à Detecção de Lavagem de Dinheiro com LLMs

## 📌 Informações Gerais

* **Autor:** Thiago Cavalcanti Silva Barros
* **Professor da disciplina e orientador:** Prof. Dr. Luis Filipe Alves Pereira
* **Programa:** Mestrado em Ciência da Computação – UFAPE
* **Disciplina:** Estatística Computacional

---

## 📖 Descrição do Projeto

Este projeto tem como objetivo realizar uma **análise estatística inferencial** sobre uma base de dados de transações financeiras relacionada à **detecção de lavagem de dinheiro**, integrando métodos clássicos de estatística com o uso exploratório de **Modelos de Linguagem de Grande Porte (LLMs)**.

A análise foi conduzida sobre a base de dados **[AML Data](https://github.com/IBM/AML-Data)**, disponibilizada pela IBM, aplicando técnicas de comparação entre grupos, estimação de parâmetros, intervalos de confiança, testes de hipótese e análise de correlação. Adicionalmente, uma LLM executada localmente foi utilizada para atribuição heurística de rótulos e escores de risco, permitindo avaliar sua concordância com os rótulos reais da base.

---

## 🎯 Objetivos

* Caracterizar a população de interesse por meio de **estimadores pontuais e intervalares**
* Comparar grupos de transações legítimas e suspeitas
* Validar padrões estatísticos observados por meio de **testes de hipótese**
* Avaliar associações entre variáveis financeiras relevantes
* Analisar criticamente o uso de LLMs em um contexto sensível de classificação financeira

---

## 📊 Requisitos do Projeto (Disciplina)

### Descrição Geral

* **Tema:** Análise Estatística de Bases de Dados Reais
* **Foco:**

  * Inferência sobre a população
  * Comparação de grupos
  * Validação de padrões

### Objetivo Central

Caracterizar a população de interesse através de **estimadores pontuais e intervalares**, respondendo às perguntas de pesquisa utilizando **Testes de Hipótese**.

---

## 🧪 Roteiro de Execução

### a) Design Experimental (Definição das Perguntas)

Definição explícita de **ao menos três perguntas de pesquisa não óbvias**, envolvendo:

* Padrões
* Regras subjacentes
* Correlações
* Discussão de causalidade

### b) Estimação de Parâmetros e Incerteza

* Intervalos de Confiança (ICs)
* Métodos robustos (ex.: bootstrap)

### c) Execução de Testes de Hipótese

* Comparação de médias/medianas
* Testes paramétricos e não paramétricos
* Avaliação de significância estatística (α = 0,05)

### d) Conclusões Baseadas em Evidências

* Interpretação estatística dos resultados
* Discussão das limitações e implicações

---

## 📝 Artigo Científico

O projeto resultou na elaboração de um artigo acadêmico contendo as seguintes seções:

1. **Introdução e Motivação**
2. **Definição das Perguntas de Pesquisa**
3. **Metodologia Computacional**
4. **Resultados e Evidências Estatísticas**
5. **Análise Crítica dos Resultados**

---

## 🛠️ Tecnologias Utilizadas

* **Python** (pandas, numpy, scipy, seaborn, matplotlib)
* **Jupyter Notebook**
* **Ollama** (execução local de LLMs)
* **Modelo de Linguagem:** Mistral-7B-Instruct (quantizado)
* **Base de Dados:** IBM AML Data

---

## ⚠️ Observações Importantes

* A LLM utilizada **não foi treinada nem ajustada** para a tarefa de detecção de lavagem de dinheiro.
* Sua aplicação tem caráter **exploratório e heurístico**, sendo analisada estatisticamente e criticamente.
* Os dados da IBM são **sintéticos**, projetados para simular cenários reais sem expor informações sensíveis.

---

## 📚 Licença e Uso

Este repositório destina-se exclusivamente a **fins acadêmicos**, no contexto da disciplina de Estatística Computacional do Programa de Mestrado em Ciência da Computação da UFAPE.

---
