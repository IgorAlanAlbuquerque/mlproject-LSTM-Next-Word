# mlproject-LSTM-Next-Word
## Descrição do Projeto: Previsão da Próxima Palavra Usando LSTM
#### Visão Geral do Projeto:

Este projeto tem como objetivo desenvolver um modelo de aprendizado profundo para prever a próxima palavra em uma sequência de palavras fornecida. O modelo é construído usando redes LSTM, que são especialmente adequadas para tarefas de predição de sequências. O projeto inclui as seguintes etapas:

1- Coleta de Dados: Utilizei o texto de "Hamlet", de Shakespeare, como meu conjunto de dados. Este texto rico e complexo oferece um bom desafio para o modelo.

2- Pré-processamento de Dados: Os dados textuais são tokenizados, convertidos em sequências e preenchidos (padding) para garantir comprimentos uniformes de entrada. As sequências são então divididas em conjuntos de treino e teste.

3- Construção do Modelo: Um modelo LSTM é construído com uma camada de embedding, duas camadas LSTM e uma camada densa de saída com uma função de ativação softmax para prever a probabilidade da próxima palavra. Uma camada de dropout entre as camadas LSTM.

4- Treinamento do Modelo: O modelo é treinado usando as sequências preparadas.

5- Avaliação do Modelo: O modelo é avaliado usando um conjunto de frases de exemplo para testar sua capacidade de prever a próxima palavra com precisão.

6- Implantação: Uma aplicação web desenvolvida com Streamlit permite que os usuários insiram uma sequência de palavras e obtenham a previsão da próxima palavra em tempo real.