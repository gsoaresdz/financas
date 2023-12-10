# **Python e Finanças**

Este projeto demonstra a aplicação do Python no campo das finanças, usando bibliotecas populares como Pandas, Matplotlib e NumPy. O objetivo é analisar a performance do índice IBOV (Ibovespa) usando dados históricos coletados diretamente do Yahoo Finance.

## **Bibliotecas Utilizadas**

- pandas
- matplotlib
- numpy
- pandas_datareader
- yfinance
- datetime

## **Instalação**

Para instalar as dependências necessárias, execute o seguinte comando:

```
pip install pandas matplotlib numpy pandas_datareader yfinance
```

## **Uso**

O script realiza as seguintes análises:

1. Importa os dados históricos do índice IBOV.
2. Exibe um gráfico com o preço de fechamento ajustado ao longo do tempo.
3. Calcula o retorno do índice IBOV no período analisado.
4. Exibe um gráfico com médias móveis de 21 e 34 dias.

Para executar o script, basta rodar o arquivo **`main.ipynb`** (que deve conter o código mostrado acima) no terminal ou em seu ambiente de desenvolvimento Python preferido:

```
python main.ipynb
```

## **Resultados**

Os resultados incluem gráficos e cálculos relacionados ao índice IBOV, como o retorno acumulado no período e a análise de médias móveis. Os gráficos gerados podem ser usados para identificar tendências e possíveis pontos de entrada e saída no mercado financeiro.
