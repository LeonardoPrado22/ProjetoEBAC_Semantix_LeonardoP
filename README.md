# 🧠 Projeto EBAC / Semantix – Análise de Dados

Este projeto tem como objetivo realizar uma **análise exploratória e visualização de dados** com base em um conjunto de informações coletadas para solucionar uma problemática da vida real.

---

## 📥 1. Coleta de Dados

Os dados foram obtidos a partir a base de dados obtida no Kaggle (https://www.kaggle.com/datasets/adharshinikumar/screentime-vs-mentalwellness-survey-2025) que possui como foco a relação entre o uso de tela e a saúde mental

Durante a etapa de coleta, foram realizadas as seguintes ações:
- Importação do dataset em formato `.csv` utilizando a biblioteca **pandas**.
- Inspeção inicial dos dados com os métodos `head()`, `info()` e `describe()`.
- Verificação de valores ausentes e inconsistências.
- Padronização dos nomes das colunas e conversão de tipos de dados, quando necessário.

Essa preparação foi essencial para garantir a integridade e qualidade das análises posteriores.

---

## 🔍 2. Exploração dos Dados

A análise exploratória (EDA) teve como objetivo compreender o comportamento das variáveis e identificar padrões relevantes.

### Principais etapas:
- **Análise descritiva**: cálculo de médias, medianas, modas e desvio padrão.  
- **Distribuição das variáveis**: visualizações com **histogramas** e **boxplots** para observar dispersão e outliers.  
- **Correlação entre variáveis**: uso de **heatmap** para identificar relações e redundâncias.  
- **Criação de novas variáveis derivadas**, quando necessário, para enriquecer as análises.  

Essas etapas permitiram compreender as tendências e direcionar a modelagem para os fatores mais relevantes.

---

## ⚙️ 3. Modelagem dos Dados

Após o entendimento da base, iniciou-se o processo de modelagem.

### Etapas seguidas:
1. **Seleção de variáveis relevantes** com base nos resultados da EDA.  
2. **Divisão dos dados** em conjuntos de treino e teste (quando aplicável).  
3. Implementação de modelos utilizando **scikit-learn** (ex: Regressão Linear, Árvore de Decisão ou K-Means).  
4. Avaliação de desempenho com métricas como **MAE**, **R²** ou **RMSE**, dependendo do tipo de problema.  

---

## 🧩 Conclusão

1. A análise indica que o alto nível de estresse e a baixa qualidade do sono são os principais fatores de risco.
2. O tempo de tela também se mostra relevante, embora tenha um papel secundário, especialmente quando está associado a momentos de lazer.
3. De forma geral, o bem-estar mental está diretamente ligado a pequenos cuidados do dia a dia, e qualquer desequilíbrio nessas áreas pode refletir em diferentes aspectos da vida.

📅 **Data:** Outubro / 2025  
👨‍💻 **Autor:** Leonardo P.  
📚 **Curso:** Ciência de Dados – EBAC / Parceria SemantiX