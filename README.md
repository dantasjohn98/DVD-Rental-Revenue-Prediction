🎬 DVD Rental Revenue Prediction
End-to-End Machine Learning Project

Projeto completo de Machine Learning com foco em previsão de receita de locação, utilizando técnicas de regressão supervisionada e otimização de hiperparâmetros.

🎯 Problema de Negócio

Prever a receita gerada por locação para:

Melhor planejamento financeiro

Estratégia de precificação

Identificação de drivers de receita

🧠 Modelagem
Modelos Testados

Linear Regression

Decision Tree

Random Forest

Random Forest Tunado (GridSearch)

📊 Resultados Finais (Modelo Selecionado)

Random Forest Tunado

MSE: 2.0243

RMSE: 1.4228

Redução de erro vs baseline: ~58%

📈 Feature Importance (Random Forest)

As variáveis mais relevantes para previsão de receita foram:

Rental Duration Real

Rental Rate

Film Length

Release Year

Rating (após encoding)

Interpretação

A duração real da locação é o principal driver de receita.

A taxa de aluguel tem impacto direto (como esperado).

Características do filme influenciam indiretamente a geração de receita.

Relações não-lineares foram capturadas pelo modelo ensemble.

🧩 Insights Técnicos

Modelos lineares não capturam adequadamente interações entre variáveis.

Ensemble models apresentaram melhor generalização.

O tuning trouxe ganho marginal — modelo base já robusto.

Não houve overfitting significativo após ajuste de profundidade.

🔍 Próximo Passo Técnico (Roadmap)

SHAP values para interpretabilidade avançada

Cross-validation K-Fold

Pipeline estruturado com sklearn

Deploy do modelo (API ou App interativo)

▶️ Como Executar

git clone https://github.com/dantasjohn98/DVD-Rental-Revenue-Prediction.git

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

jupyter notebook

🛠 Stack

Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn

👨‍💻 Autor

Jonathan Dantas
Machine Learning | Data Analytics | Python | SQL | Power BI
