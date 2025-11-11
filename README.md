# Surrogates-and-Prototypes
Surrogates são modelos substitutos, usados para aproximar ou explicar o comportamento de um modelo complexo, permitindo análises interpretáveis ou mais rápidas. Prototypes são exemplos representativos de dados que ajudam a ilustrar decisões ou padrões aprendidos, tornando a IA mais compreensível e auditável.

Goals: Train a surrogate with a CART decision tree as an interpretable model using the original training data to approximate the behavior of the black box
Surrogate para regressão
  - Black-box: Random Forest
  - Surrogate: Decision Tree Regressor
Surrogate para classificação: Usamos as predições do black box como target
  - Black-box: Random Forest
  - Surrogate: Decision Tree Classifier
    
Métricas de fidelidade: F1 Score, AUC-ROC, Correlação
