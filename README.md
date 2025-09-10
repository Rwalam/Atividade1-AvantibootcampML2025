# Atividade1-AvantibootcampML2025
Atividade 1
1. Explique, com suas palavras, o que é machine learning?
   -São algoritmos capazes de prever algo ou dividir em grupos.
3. Explique o conceito de conjunto de treinamento, conjunto de validação e
conjunto de teste em machine learning.
   -No treinamento temos acesso ao valor da variável target pois precisamos que o modelo aprenda os padões e o target que representa aqueles padrões.
   Na validação queremos verificar se a disposição dos dados não interferiu no resultado do modelo.
   No teste usamos dados que os rotulos foram retirados para que o modelo treinado tente acertar qual é o target.  
5. Explique como você lidaria com dados ausentes em um conjunto de dados
de treinamento.
   -Se forem poucas samples em percentual do dataset, excluiria elas, se for uma coluna com uma grande quantidade de dados ausentes excluiria a coluna, caso não, faria o preenchimento com a média ou mediana, e se fosse uma feature com de classe, não numerica, poderia ser preenchido com a moda, mas depende muito do caso.
7. O que é uma matriz de confusão e como ela é usada para avaliar o
desempenho de um modelo preditivo?
   -É uma matriz que resume o resultado do modelo, temos , falso, verdadeiro no X e positivo e negativo no Y. A partir de algumas operações basicas entre as celulas da matriz, temos indicadores como acuracia, que servem de informação para o desempenho do modelo.
9. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura,
entre outras) você acha mais interessante aplicar algoritmos de machine
learning?
    -Acho que pode ajudar muito na saúde, com reconhecimento de imagens de testes e raio X, pode auxiliar o trabalho do medico.
