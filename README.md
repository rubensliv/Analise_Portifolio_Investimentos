'''
O programa em Jupyter Notebook, realiza uma análise de portfólio de investimentos. Em linhas gerais, ele executa as seguintes etapas:

Obtenção de Dados: Busca dados históricos de preços de fechamento diário de ativos financeiros (neste caso, S&P 500 e um ETF do setor de tecnologia) de uma API externa (Alpha Vantage).

Pré-processamento de Dados: Calcula os retornos diários desses ativos e simula um 'retorno de portfólio' com base nesses retornos e um 'fator inesperado' gerado aleatoriamente. Isso cria um conjunto de dados para a modelagem.

Treinamento de Modelo de Regressão Linear: Divide os dados em conjuntos de treino e teste e treina um modelo de regressão linear para prever o 'retorno de portfólio' com base nos retornos do mercado, do setor e do fator inesperado.

Avaliação do Modelo: Avalia o desempenho do modelo usando métricas como RMSE (Root Mean Squared Error) e R² (coeficiente de determinação), que indicam a precisão das previsões.

Análise de Coeficientes: Exibe os coeficientes da regressão, que representam a influência de cada fator (retorno de mercado, retorno do setor, fator inesperado) no retorno do portfólio. Isso ajuda a identificar os fatores mais influentes.

Visualização: Gera um gráfico comparando os retornos reais do portfólio com os retornos previstos pelo modelo no conjunto de teste, permitindo uma visualização da performance do modelo.

'''
