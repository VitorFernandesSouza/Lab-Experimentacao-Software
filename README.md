# 📊 Laboratórios de Experimentação de Software

Repositório designado às atividades desenvolvidas na disciplina Laboratorio de Experimentação de Software na PUC-Minas no 2° semestre de 2025

---

## 📑 Sumário

1. [Visão Geral](#-visão-geral)
2. [Pré-requisitos](#-pré-requisitos)
3. [Laboratórios](#-laboratórios)
4. [Como Executar](#-como-executar)
5. [Saídas Esperadas](#-saídas-esperadas)
6. [Tecnologias e Ferramentas](#-tecnologias-e-ferramentas)
7. [Estrutura do Repositório](#-estrutura-do-repositório)
8. [Equipe e Contato](#-equipe-e-contato)

---

## 🔍 Visão Geral

Este repositório centraliza todos os laboratórios realizados na disciplina de **Laboratório de Experimentação de Software**, com foco em:

* **Design Experimental:** definição de hipóteses, variáveis e tratamentos.
* **Automação:** coleta e análise de dados via scripts em Python e Java.
* **Análise Estatística:** uso de correlações, testes de hipóteses e visualizações.
* **Visualização:** criação de dashboards interativos e gráficos informativos.

Cada laboratório documenta seu objetivo, passos de execução, saídas esperadas e resultados.

---

## ⚙️ Pré-requisitos

Antes de começar, certifique-se de ter instalado:

* **Python 3.8+** (com `pip`)
* **Git** (para clonar o repositório)
---

## 📌 Laboratórios

| Lab | Tema                                                   | Diretório         |
| :-: | ------------------------------------------------------ | ----------------- |
|  1  | Características de Repositórios Populares (GitHub API) | `Lab1_RepoPop`    |

Cada pasta contém:

* **Enunciado** (`.pdf`)
* **README** específico com instruções detalhadas
* **Scripts** para coleta, análise e geração de relatórios
* **Pastas** de resultados: CSVs, gráficos, dashboards e artefatos finais

---

## 🚀 Como Executar

Para qualquer laboratório, siga estes passos:

---

## 📂 Saídas Esperadas



---

## 🛠️ Tecnologias e Ferramentas

* **Linguagens:** Python (3.8+), Java (Lab 2)
* **API:** GitHub REST & GraphQL
* **Análise Java:** `ck.jar` para métricas de código

## 📚 Bibliotecas Python Utilizadas

A seguir, todas as bibliotecas Python necessárias, agrupadas por laboratório:

**Em todos os laboratórios:**

* `requests`
* `pandas`
* `matplotlib`
* `seaborn`
* `python-dotenv`
* `scipy`
* `statsmodels`
* `GitPython`
* `jupyter`

**Lab 1 – `Lab1_RepoPop`:**

* `PyGithub` (para interagir com GraphQL/REST)
* `tqdm` (barra de progresso opcional)

---

## 🗂️ Estrutura Geral do Repositório

```
Lab_Experimentacao_Software_1.2025
├── Lab1_RepoPop/                       # Lab 1: Repositórios Populares (GraphQL/REST)
├── 📄 README.md                        # Visão geral (este arquivo)
├── 📄 config_token.py                  # Carrega token GitHub (.env) para os scripts
├── 📄 config_token_rotator.py          # Gerencia rotação automática de tokens
└── 📄 env.config                       # Armazena variáveis de ambiente (GITHUB_TOKEN)
```

---

## 👥 Equipe e Contato

* **Izabela Cecilia Silva Barbosa**
* **Lucas Machado de Oliveira Andrade**
* **Mariana Eliza Alves Costa**
* **Vitor Fernandes de Souza**

---

*Disciplina: Laboratório de Experimentação de Software — PUC Minas*

