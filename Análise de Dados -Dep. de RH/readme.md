# Análise de Dados de Vendas

Este projeto tem como objetivo realizar uma análise de dados históricos de vendas, aplicando técnicas de visualização e previsão de séries temporais com o uso do algoritmo `Prophet`. Através deste projeto, buscamos identificar padrões de vendas, sazonalidades, e gerar previsões para melhorar a tomada de decisão estratégica.

## 📑 Descrição do Projeto

Este projeto busca analisar e prever o comportamento de vendas ao longo do tempo, permitindo decisões mais precisas para otimizar o desempenho do departamento comercial. As principais etapas incluem:

- **Importação e Pré-processamento dos dados:** Tratamento de dados ausentes ou inconsistentes, conversão de colunas para formatos apropriados (como datas e valores numéricas).
- **Análise Exploratória de Dados:** Visualização de tendências históricas, identificação de sazonalidades e padrões específicos por período, analise de distribuições e correlações entre variáveis.
- **Aplicação do Algoritmo Prophet** Treinamento do modelo `Prophet` com dados históricos, geração de previsões para períodos futuros e ajuste de hiperparâmetros para melhorar a precisão do modelo.
- **Visualização de Resultados** Criação de gráficos de tendências e sazonalidades com `Matplotlib` e `Seaborn`, Comparação entre as previsões e dados históricos, análise de intervalos de confiança para previsões futuras.

## 📂 Estrutura do Projeto

- `Departamento_de_Vendas.ipynb`: Notebook com o código completo e as análises realizadas. 

## 📊 Exemplos de Análises Realizadas

- **Forecasting com Prophet:** Previsão de vendas para os próximos 3, 6 ou 12 meses e Gráfico de previsão com intervalos de confiança, ajudando a visualizar a incerteza nas estimativas.
- **Comparação entre Previsões e Vendas Reais:** Avaliação da precisão das previsões geradas pelo modelo Prophet em relação aos dados reais e Cálculo de métricas como MAE (Mean Absolute Error) ou RMSE (Root Mean Squared Error).
- **Análise de Picos Inesperados e Anomalias:** Identificação de vendas fora do padrão e análise de possíveis causas (como promoções não planejadas).

## 🔧 Tecnologias Utilizadas

- Python
- **Prophet**
- Pandas
- Numpy
- Seaborn
- Matplotlib

## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para entrar em contato para conversarmos e discutirmos possibilidades.
