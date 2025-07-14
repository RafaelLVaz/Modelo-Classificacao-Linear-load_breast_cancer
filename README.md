#  Diagnóstico de Câncer de Mama com Regressão Logística

Este projeto utiliza o conjunto de dados **Breast Cancer Wisconsin**, disponível na biblioteca `scikit-learn`, para treinar um modelo de **Regressão Logística**, com o objetivo de prever se um tumor é **maligno (0)** ou **benigno (1)**.

---

##  Sobre o Projeto

O notebook segue os seguintes passos:

- Carregamento do dataset: `load_breast_cancer()` do `sklearn.datasets`
- Criação do DataFrame com os dados e a coluna alvo (`target`)
- Divisão dos dados em treino e teste, com estratificação por classe
- Padronização (normalização) dos dados com `StandardScaler`
- Treinamento do modelo com `LogisticRegression`
- Avaliação do modelo com:
  - Previsões (`predict`)
  - Probabilidades (`predict_proba`)
  - Matriz de confusão (`confusion_matrix`)

---

##  Tecnologias Utilizadas

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

##  Dataset

- **Nome:** Breast Cancer Wisconsin Diagnostic Dataset  
- **Fonte:** `sklearn.datasets.load_breast_cancer()`  
- **Total de amostras:** 569  

### Variável Target:
- `1`: Tumor maligno  
- `0`: Tumor benigno  

### Atributos:
- 30 características relacionadas ao núcleo celular

---

##  Resultados

O modelo de Regressão Logística foi treinado com dados padronizados e obteve boa performance na classificação.  
A **matriz de confusão** foi utilizada para visualizar a quantidade de acertos e erros do modelo.

---

## ▶ Como Executar

1. Clone ou copie o notebook para o [Google Colab](https://colab.research.google.com/).
2. Execute as células sequencialmente.
3. Certifique-se de que as seguintes bibliotecas estejam disponíveis:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
