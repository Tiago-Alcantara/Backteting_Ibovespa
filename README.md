# Fazendo um modelo de investimento com Python - Factor Invest no Ibovespa
## Desafio:
- Contruir um codigo que faça um backtesting dos últimos 6 anos, escolhendo as 10 melhores ações do índice ibovespa e utlizando como criterio o fator momento 6 meses

## Passo a passo da estratégia:
* **Passo 1** - Definir um universo investível.
* **Passo 2** - Escolher o fator que servirá como criterio para criação dos rankings.
* **Passo 3** - Escolher o período de teste.
* **Passo 4** - Escolher o número de ações na carteira
* **Passo 5** - Definir o período de balanceamento. De quanto em quanto tempo a carteira muda?

## Passo a passo do codigo?
* **Passo 1** - Ler a composição hsitorica do Ibovespa e os tickers que ja passaram pelo índice.
* **Passo 2** - Puxar as cotações de todas as empresas que farão parte do backtest.
* **Passo 3** - Transformar o índice em data e ordenar a serie de tempo.
* **Passo 4** - Calcular o retorno 6 meses de ajustar a tabela com o fator.
* **Passo 5** - Classificar e retirar empreas que não participam do Ibovespa no período de tempo selecionado. 
* **Passo 6** - Criar as carteiras de investimento em uma matriz de 0 ou 1.
* **Passo 7** - Calcular o retorno mensal das empreas no período de backtest
* **Passo 8** - Cruzar a matriz de retorno mensal com a matriz das carteiras para chegar na rentabilidade do modelo
* **Passo 9** - Puxar e calcular a rentabilidade do Ibovespa no período.
* **Passo 10** - Calcular e visualizar as rentabilidades do modelo contra o Ibovespa
