# Experimento-ML-AI900
Criando um modelo de machine learning para prever o número de alugueis de bicicletas utilizando dados históricos, tudo através da plataforma Azure Machine Learning:

- Primeiro, um espaço de trabalho do Azure Machine Learning foi criado.
  
- Em seguida, foi usado o aprendizado de máquina automatizado para treinar um modelo. Isso envolveu o uso de um conjunto de dados de aluguel de bicicletas para prever o número de alugueis em um dia específico.
- Um novo conjunto de dados foi criado com os dados de aluguel de bicicletas.
- O trabalho de aprendizado de máquina automatizado foi configurado com um tipo de tarefa de regressão, um conjunto de dados de aluguel de bicicletas e a coluna de destino como "rentals".
- O trabalho foi limitado para usar os modelos RandomForest e LightGBM, com limites de tentativas, nós e tempo.
- Após o término do trabalho, o melhor modelo foi revisado em termos de métricas e desempenho.
- O modelo foi então implementado como um endpoint em tempo real.
- O endpoint foi testado com dados de entrada para obter uma previsão do número de alugueis.
- Por fim, para poupar recursos, a tarefa foi excluída. O espaço de trabalho também poderia ser excluído.
