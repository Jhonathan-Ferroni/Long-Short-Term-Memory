# Previsão de Preços de Ações com LSTM

Este repositório contém um modelo de Rede Neural Recorrente (RNN) utilizando Long Short-Term Memory (LSTM) para prever preços de ações com base em séries temporais. O modelo foi treinado e testado com dados das ações do Google.

## Tecnologias Utilizadas
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Keras**
- **scikit-learn**

## Estrutura do Projeto
- 📄 `lstm.py`: Script principal contendo a implementação do modelo.
- 📂 `Google_Stock_Price_Train.csv`: Conjunto de dados de treinamento.
- 📂 `Google_Stock_Price_Test.csv`: Conjunto de dados de teste.

## Como Executar

1. Certifique-se de ter o Python instalado.
2. Instale as dependências necessárias:
   ```bash
   pip install numpy pandas matplotlib keras scikit-learn
   ```
3. Execute o script `lstm.py`:
   ```bash
   python lstm.py
   ```

## Funcionamento do Modelo

1. 📥 **Carregamento** dos dados de treinamento e teste.
2. 🔄 **Normalização** dos dados para melhor desempenho do modelo.
3. 📊 **Criação** de sequências de entrada e saída para treinamento.
4. 🏗 **Construção** da rede LSTM com camadas de dropout para evitar overfitting.
5. 🎯 **Treinamento** do modelo utilizando o otimizador Adam e a função de perda MSE.
6. 📈 **Geração** de previsões e visualização dos resultados.

## Exemplo de Gráfico de Saída
O modelo gera um gráfico comparando os preços reais das ações com os valores previstos.

![Exemplo de Gráfico](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Stock_Price_Graph.svg/800px-Stock_Price_Graph.svg.png)

## 📌 Contribuição
Sinta-se à vontade para abrir **issues** e **pull requests** para melhorias no projeto!

## 📜 Licença
Este projeto é distribuído sob a licença **MIT**.

