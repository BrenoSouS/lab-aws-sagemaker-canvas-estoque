# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)



## 🚀 Conclusâo
O modelo escolhido foi de previsão para estoque , o foco foi em ver a relação dos itens em estoque .
Foi visivel que:
-a quantidade de produto em estoque esta altamente ligada ao preço , sugerindo que produtos mais caros tem menos demanda;

-varios produtos apresentaram uma 

-Em relação as metricas do modelo de previsão:

-O modelo de previsão tem um MAPE bastante alto (97.1%), sugerindo baixa precisão na previsão dos valores.

-O WAPE é um pouco melhor, mas ainda indica uma quantidade significativa de erro.

-O RMSE confirma que os erros têm uma magnitude considerável.

-O MASE, no entanto, sugere que, apesar dos erros absolutos, o modelo ainda é melhor do que um simples modelo de referência (naïve).

-O Avg. wQL indica que o sistema de processamento associado ao modelo não está enfrentando gargalos significativos.
