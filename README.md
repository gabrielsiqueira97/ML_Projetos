# ML_Projetos

Repositório criado para estudar e implementar algoritmos de Machine Learning aplicados a bases de crédito, risco de crédito e dados do censo. Aqui, explorei diferentes modelos e técnicas para resolver problemas de classificação e análise de dados.

## Algoritmos Implementados

1. **OneR (One Rule)**  
   Algoritmo simples que utiliza uma única regra para classificação, baseado no atributo mais relevante. Útil como baseline para problemas supervisionados.  

2. **Prism**  
   Método indutivo que constrói regras específicas para cada classe, fornecendo modelos interpretáveis e eficazes.  

3. **Árvore de Decisão**  
   Algoritmo hierárquico baseado em perguntas/decisões, ideal para problemas com dados categóricos ou contínuos.  

4. **KNN (K-Nearest Neighbors)**  
   Classificação baseada nos vizinhos mais próximos, avaliando a similaridade dos dados.  

5. **Naive Bayes**  
   Modelo probabilístico baseado no teorema de Bayes, eficiente para dados categóricos e independentes.  

6. **Regressão Logística**  
   Algoritmo estatístico para classificação binária, ótimo para interpretar probabilidades.  

7. **SVM (Support Vector Machine)**  
   Classificador que maximiza a margem entre classes, eficiente para dados de alta dimensionalidade.

## Bibliotecas Utilizadas

Algumas bibliotecas Python utilizadas para este projeto incluem:

- **scikit-learn (sklearn)**: Para implementação de algoritmos de Machine Learning e métricas de avaliação.  
- **pickle**: Para salvar e carregar modelos treinados.  
- **yellowbrick**: Para visualizações de métricas, como matriz de confusão e análise de decisão.  
- **accuracy_score** (do sklearn): Para cálculo de acurácia dos modelos.  
- **KNeighborsClassifier** (do sklearn): Para o algoritmo KNN.  
- **DecisionTreeClassifier** (do sklearn): Para Árvore de Decisão.  
- **metrics** (do sklearn): Para cálculo de precisão, recall, F1-score, entre outros.  
- **Orange**: Ferramenta para análise de dados e aprendizado de máquina, com foco em fluxos de trabalho visuais.  
- **collections**: Biblioteca padrão do Python para manipulação de coleções, como `Counter` e `deque`.  

Certifique-se de instalar todas as dependências antes de executar os códigos:

