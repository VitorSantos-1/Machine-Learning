<h1 align="center">🤖 Machine Learning — Regressão Linear</h1>

<p align="center">
  <em>Construção de um modelo preditivo do zero: do tratamento dos dados à avaliação do modelo.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" alt="Plotly"/>
</p>

---

## 🎯 Objetivo

Explorar os conceitos fundamentais de **Machine Learning**, aplicando técnicas de preparação de dados, modelagem e avaliação. O projeto usa **Regressão Linear** (scikit-learn) para construir um modelo preditivo e entender, na prática, todo o fluxo de um problema supervisionado.

## 🔬 Fluxo do projeto

| # | Etapa | Descrição |
|---|-------|-----------|
| 1 | **Importação de bibliotecas** | pandas, NumPy, seaborn, Plotly e scikit-learn. |
| 2 | **Carregamento dos dados** | Leitura da base a partir de arquivo. |
| 3 | **Exploração inicial** | Primeiras linhas, estatísticas descritivas e estrutura dos dados. |
| 4 | **Dados faltantes** | Verificação e tratamento de valores ausentes. |
| 5 | **Pré-processamento** | Codificação de variáveis, padronização e limpeza. |
| 6 | **Split treino/teste** | Divisão dos dados com `train_test_split`. |
| 7 | **Modelagem** | Treinamento de um modelo de `LinearRegression`. |
| 8 | **Avaliação** | Medição de desempenho com **R² (`r2_score`)**. |
| 9 | **Predições** | Predições manuais e interpretação dos resultados. |
| 10 | **Visualização** | Gráficos para comunicar os achados. |

## 🛠️ Ferramentas

- **Linguagem:** Python
- **Bibliotecas:** scikit-learn, pandas, NumPy, seaborn, Matplotlib, Plotly

## 🚀 Como executar

```bash
# Instalar dependências
pip install scikit-learn pandas numpy seaborn matplotlib plotly

# Abrir o notebook
jupyter notebook 16_MACHINE_LEARNING.ipynb
```

## 📂 Arquivos

| Arquivo | Descrição |
|---------|-----------|
| [`16_MACHINE_LEARNING.ipynb`](16_MACHINE_LEARNING.ipynb) | Notebook completo, da preparação dos dados à avaliação do modelo. |

## ✅ Conclusão

O projeto percorre todas as etapas de um pipeline de Machine Learning supervisionado, encerrando com reflexões sobre o desempenho do modelo e possíveis melhorias — como ajuste de hiperparâmetros e experimentação com outros algoritmos.

---

<p align="center">
  <sub>Feito por <a href="https://github.com/VitorSantos-1">Vitor Santos</a> · 🤖 Machine Learning</sub>
</p>
