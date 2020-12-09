# machinelearning-IFPB
Projetos da disciplina Tópicos Especiais

# Mini-Projeto 1 
<b>Objetivo</b>: Comparar os resultados de algoritmos de Machine Learning com problemas de classificação. Escolher dois problemas de classificação (bases) do UCI: https://archive.ics.uci.edu/ml/index.php 
<br>
<b>Algoritmos a serem testados</b>: 

- Treinar 2 árvores de decisão com o criterion = “gini” e “entropy” - Treinar 6 kNN. Usar 2 medidas de distância diferentes e 3 tamanhos de vizinhança. 
- Treinar 3 kNN Improve. Usar 3 tamanhos de vizinhança. 
<br>
<b>Protocolo Experimental</b>: 

- Dividir o conjunto de dados em 80% para treinamento e 20% para testes. Treinar os algoritmos com os mesmos dados. 
<br>
<b>Relatório</b>: 

- Exibir os resultados (Taxas de Acerto) de todos os algoritmos. 

# Mini-Projeto 2 
<b>Objetivo</b>: Comparar os resultados de algoritmos de Machine Learning com problemas de classificação. Escolher três problemas de classificação (bases) do UCI: https://archive.ics.uci.edu/ml/index.php 
<br>
<b>Algoritmos a serem utilizados</b>: 

- Árvore de Busca (gini e entropy)
- kNN (k igual a 5 e 10)
- MLP (escolher duas arquiteturas diferentes e variar o parâmetro
activation = {‘relu’,’tanh’}). “relu” é o valor default para o parâmetro
activation.
- K-Means (K igual ao número de classes existente no problema)
- Cada uma das divisões dos conjuntos deve ser utilizado para treinar cada
algoritmo.
<br>
<b>Protocolo Experimental</b>: 

- Executar um k-fold cross-validation (k = 10), com 90% dos dados para Treinamento e o restante para Testes. 
<br>
<b>Relatório</b>: 

- Para as MLPs, gerar gráfico mostrando a taxa de erro de treinamento em cada época. 
- Tabela com as taxas de erro/acerto, que será a média dos 10 folds de teste, para cada algoritmo treinado. Exibir os valores em percentual.


