## Modeling Techniques

1. Regressão Linear do SKLEARN <https://scikit-learn.org/1.5/modules/generated/sklearn.linear_model.LinearRegression.html>
2. Support Vector Regression do SKLEARN <https://scikit-learn.org/1.5/modules/generated/sklearn.svm.SVR.html>
3. Decision Tree Regression do XGboost <https://machinelearningmastery.com/xgboost-for-regression/>

## Modeling Assumptions

Apenas variáveis numéricas

## Test Design
### Dataset split:

Separação de Train/Test dataset padrão com 20% de massa para teste via método SKLEARN

## Métrica de avaliação do modelo:

R2, R2 ajustado -> Métrica para saber o quão ajustado está nossa curva de regressão aos dados
MSE, RMSE e MAE

MSE -> Você quer penalizar o erro
MAE -> Você quer tratar os erros normalmente

Para esse modelo vou utilizar a validação da métrica MSE e RMSE para penalizar grandes erros de previsão
Utilizando o método do SKLEARN <https://scikit-learn.org/1.5/modules/generated/sklearn.metrics.mean_squared_error.html>
