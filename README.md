# AnaliseFIIS
Projeto que visa analisar uma base de dados contendo Fundos de Investimento Imobiliário do Brasil

## Passo a passo
- Selecionar uma variável dependente (target) para ter seu valor previsto a partir do valor das demais variáveis. No caso a variável escolhida foi "Rentabilidade";
- Calcular o coeficiente de correlação entre cada uma das variáveis independentes e a variável dependente e indicar as duas variáveis que têm maior correlação com a variável a ser prevista;
- Apresentar o passo a passo durante a execução para obtenção da equação que representa a Regressão Linear Múltipla. O modelo gerado será usado para determinar o valor da variável dependente em função dos valores das duas variáveis independentes (explicativas);
- Explicar como se poderia avaliar a qualidade das previsões. Uma forma para isso é calcular o "coeficiente de qualidade" e interpretar o valor encontrado.

## Observações de conclusão
- Foi possível notar uma correlação baixa devido ao tamanho pequeno da base e uma ausência de linearidade entre as variáveis, por isso, decidi aplicar outro algoritmo de regressão (Random Forest) e obter resultados diferentes;
- Ao usar o algoritmo de Random Forest foi possível notar um salto levemente positivo nas métricas, mas é exemplo de overfitting. O modelo decorou padrões específicos do conjunto de treino que não se generalizam;
- Foi realizada uma validação cruzada para testar a confiabilidade dos resultados obtidos e é mostrado que a média é menor que o próprio desvio padrão, ou seja, a performance do modelo varia mais entre diferentes amostras dos dados que o próprio "sinal" encontrado, sendo o R² um resultado não confiável.
