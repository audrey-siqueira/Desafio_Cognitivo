# Desafio_Cognitivo

a. Como foi a definição da sua estratégia de modelagem?

Explorar o dataset para colocar os tipos de quarto como variável dependente,
a partir dai testar diferentes classificadores para encontrar o mais eficiente.

b. Como foi definida a função de custo utilizada?

Foi levado em conta perdas em AUC, Acuracidade,Recall,Precisão,F1,Kappa e MCC.

c. Qual foi o critério utilizado na seleção do modelo final?

Comparando diversos modelos de classificação o vencedor foi o Light Gradient Boosting Machine,
devido possuir os melhores índices nos parâmetros citados acima.

d. Qual foi o critério utilizado para validação do modelo?

Foram utizados os dados de teste, além dos dados do (Unseen Data) definido pelo Pycaret.

Por que escolheu utilizar este método?

Porque foi o vencedor na comparação de todos os parâmetros.

e. Quais evidências você possui de que seu modelo é
suficientemente bom?

O modelo resultou em bons números da Matriz de confusão, além de curvas de ROC e calibração aceitáveis,
comprovados pelos dados de teste.
