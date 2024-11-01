# Web Scraping e Análise Estatística
Este repositório contém uma análise de dados de uma corrida de 10 km realizada em Hillsboro, Oregon, EUA, em junho de 2017. O projeto foi desenvolvido inteiramente em um Jupyter Notebook e inclui o processo de web scraping, seguido pela limpeza, padronização e análise dos dados extraídos.

## 🛠️ Stacks Utilizadas

- **Requests e Urllib:** Utilizados para a requisição e coleta de dados através de scraping da web. 
- **BeaultifulSoup (bs4):** Para parsing de HTML e localização de informações específicas na página. 
- **re (Expressõe Regulares):** Para extração de dados específicos das tags HTML durante o scraping. 
- **Pandas:** Para manipulação e análise de dados, especialmente na criação e tratamento de DataFrames. 
- **Numpy:** Para operações numéricas e cálculos estatísticos. 
- **Matplotlib:** Para visualizações gráficas, ajudando a ilustrar distribuições e comparações entre os dados. 
- **Scipy e Pingouin:** Para análise estatística, incluindo testes de normalidade e comparações entre grupos. 

## 📂 Estrutura do Projeto

1. Web Scraping e Coleta de Dados:
    - Extração de dados diretamente da página web dos resultados da corrida.
    - Expressões Regulares (Regex) em Python foram utilizadas para localizar e extrair informações específicas de tags HTML, permitindo a captura eficiente dos tempos de corrida e dos dados dos participantes.

2. Limpeza e Padronização dos Dados:
    - Conversão dos dados extraídos em listas e DataFrames usando pandas para estruturação e manipulação.
    - Remoção de valores inconsistentes e tratamento de dados ausentes, garantindo precisão nos resultados.
    - Conversão e formatação das colunas para padronizar tipos de dados (como datas e horas), permitindo cálculos e comparações consistentes durante a análise.

3. Análise Exploratória:
    - Cálculo de estatísticas descritivas, como o tempo médio de conclusão.
    - Visualização da distribuição dos tempos de corrida.

4. Análise Estatística:
    - Verificação de distribuição normal dos tempos de corrida.
    - Comparação de desempenho entre homens e mulheres em diferentes faixas etárias.

5. Conclusões:
    - Resumo dos principais achados da análise.

## 📊 Resultados encontrados
A análise deste projeto fornece insights sobre:

- O tempo médio de conclusão para os participantes.
- A distribuição dos tempos de chegada.
- Diferenças de desempenho entre homens e mulheres, bem como entre diferentes faixas etárias.

## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para entrar em contato para conversarmos e discutirmos possibilidades.
