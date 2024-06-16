## Descrição do Projeto

Este projeto tem como objetivo automatizar o cálculo de operações de compra e venda de cotas do fundo imobiliário LFTS11. Utilizando dados históricos e cálculos de preço médio ponderado no tempo (TWAP), o script gera uma planilha pronta para uso em mesas de operação.

## Funcionalidades

- **Download de Dados Históricos:** Utiliza a biblioteca `yfinance` para obter dados históricos de preços do LFTS11.
- **Cálculo do TWAP:** Calcula o preço médio ponderado no tempo para o período especificado.
- **Automação de Planilha:** Lê uma planilha de saldo e gera automaticamente as operações de compra e venda necessárias.
- **Exportação para Modelo de Mesa:** Gera uma planilha final formatada conforme o modelo de exemplo fornecido.

## Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas Python:

- `yfinance`
- `pandas`
- `matplotlib`
- `openpyxl`

Você pode instalá-las utilizando o comando:

```bash
pip install yfinance pandas matplotlib openpyxl
