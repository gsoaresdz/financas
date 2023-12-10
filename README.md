# **Python e Finanças**

Este projeto tem como foco a utilização do Python para análise de dados financeiros. Ele demonstra como usar diversas bibliotecas Python para buscar, processar e visualizar dados financeiros, particularmente dados do mercado de ações. O foco principal é na análise do IBOVESPA (IBOV), o principal índice de mercado de ações do Brasil.

## **Bibliotecas e Instalação**

Este projeto utiliza as seguintes bibliotecas principais:

1. **pandas**: Para manipulação e análise de dados.
2. **matplotlib**: Para visualização de dados e plotagem gráfica.
3. **numpy**: Para cálculos numéricos.
4. **pandas_datareader**: Para buscar dados financeiros da web.
5. **yfinance**: Para buscar dados históricos do mercado do Yahoo Finance.
6. **datetime**: Para manipulação de datas e horários.

### **Instalação**

Para instalar essas bibliotecas, use o pip, o gerenciador de pacotes do Python. Execute os seguintes comandos no seu terminal:

```bash
pip install pandas
pip install matplotlib
pip install numpy
pip install pandas_datareader
pip install yfinance
pip install datetime
```

## **Versão do Python e IDE**

- **Versão do Python**: Este projeto foi desenvolvido usando Python 3.8 ou superior.
- **IDE**: Qualquer ambiente de desenvolvimento integrado (IDE) que suporte Python pode ser utilizado. Escolhas populares incluem Jupyter Notebook, PyCharm, Visual Studio Code ou até mesmo um editor de texto simples.

## **Lógica de Negócio e Etapas**

### **Buscando Dados**

1. **Definição do Intervalo de Tempo**: As datas de início e término são definidas para buscar os dados históricos. No exemplo, são usadas 1 de janeiro de 2020 a 10 de novembro de 2020.
2. **Seleção do Índice**: O índice escolhido para a análise é o IBOVESPA, representado pelo símbolo **`^BVSP`**.
3. **Obtenção dos Dados**: Utiliza-se **`pandas_datareader`** juntamente com **`yfinance`** para buscar os dados do índice no intervalo especificado.

### **Análise dos Dados**

1. **Visualização do Gráfico de Fechamento Ajustado**: Utiliza-se **`matplotlib`** para plotar o gráfico do preço de fechamento ajustado do índice ao longo do tempo.
2. **Cálculo do Retorno**: Calcula-se o retorno do investimento comparando o preço de fechamento ajustado no último dia do intervalo com o primeiro dia.
3. **Análise com Médias Móveis**: Implementa-se médias móveis de 21 e 34 dias para análise de tendências no gráfico de preço.

### **Execução do Código**

O código deve ser executado em um ambiente que suporte as bibliotecas mencionadas. Recomenda-se testar cada seção individualmente para verificar a integridade dos dados e a precisão dos cálculos.

## **Conclusão**

Este projeto oferece uma visão introdutória de como o Python pode ser utilizado para análises financeiras, especialmente em relação ao mercado de ações. É um excelente ponto de partida para aqueles interessados em exploração de dados financeiros e análise de mercado.
