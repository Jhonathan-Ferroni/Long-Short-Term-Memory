#Previsão de Preços de Ações com Long-Short-Term Memory

###Este repositório contém um modelo de Rede Neural Recorrente (RNN) utilizando Long Short-Term Memory (LSTM) para prever preços de ações com base em séries temporais. O modelo foi treinado e testado com dados das ações do Google.

Tecnologias Utilizadas

Python

NumPy

Pandas

Matplotlib

Keras

scikit-learn

Estrutura do Projeto

lstm.py: Script principal contendo a implementação do modelo.

Google_Stock_Price_Train.csv: Conjunto de dados de treinamento.

Google_Stock_Price_Test.csv: Conjunto de dados de teste.

Como Executar

Certifique-se de ter o Python instalado.

Instale as dependências necessárias:

pip install numpy pandas matplotlib keras scikit-learn

Execute o script lstm.py:

python lstm.py

Funcionamento do Modelo

Carregamento dos dados de treinamento e teste.

Normalização dos dados para melhor desempenho do modelo.

Criação de sequências de entrada e saída para treinamento.

Construção da rede LSTM com camadas de dropout para evitar overfitting.

Treinamento do modelo utilizando o otimizador Adam e a função de perda MSE.

Geração de previsões e visualização dos resultados.

Exemplo de Gráfico de Saída

O modelo gera um gráfico comparando os preços reais das ações com os valores previstos.



Contribuição

Sinta-se à vontade para abrir issues e pull requests para melhorias no projeto!
