# 📊 Resultados da Análise – Tempo de Tela e Saúde Mental

## Resumo das Hipóteses

- **Hipótese 1: *Validada** — correlação negativa entre tempo de tela e índice de bem-estar.

- **Hipótese 2: Validada** — o tempo de tela para lazer apresentou efeito mais negativo sobre o bem-estar mental.

- **Hipótese 3: Validada** — trabalhadores remotos exibem maior tempo de tela e maior impacto no estresse e produtividade.

- **Hipótese 4: Validada** — forte correlação positiva entre qualidade do sono e saúde mental.


## Desempenho dos Modelos na escala original da variável alvo
| Modelo             | MAE       | RMSE      | R²        |
|--------------------|-----------|-----------|-----------|
| Regressão Linear   | 12.279430 | 23.207986 | -0.361771 |
| Árvore de Decisão  | 5.946421  | 7.696864  | 0.850219  |
| RandomForest       | 4.819668  | 6.109299  | 0.905635  |
| XGBoost            | 5.273312  | 6.780747  | 0.883752  |
| Ensemble           | 4.927294  | 6.234331  | 0.901733  |

---

## Insights Principais
1. O aumento do tempo de tela total está associado à diminuição do bem-estar mental, validando a hipótese de que o uso excessivo de dispositivos impacta negativamente a saúde emocional.  
2. A qualidade e a quantidade de sono adequadas estão fortemente relacionadas a um maior bem-estar mental e à redução dos níveis de estresse.  
3. O tempo de tela destinado ao lazer apresenta uma correlação negativa mais forte com o bem-estar mental do que o tempo de tela voltado ao trabalho, indicando que o tipo de uso é determinante.  
4. Trabalhadores em regime remoto exibem maior tempo de tela total e para trabalho, o que reforça a importância de estratégias de equilíbrio digital nesse grupo.  


📅 **Data:** Outubro / 2025  
👨‍💻 **Autor:** Leonardo P.  
📚 **Curso:** Ciência de Dados – EBAC / Parceria Semantix