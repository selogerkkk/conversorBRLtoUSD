# Conversor de Cotação Dólar-BRL usando API do Banco Central

Este projeto consiste em um aplicativo de linha de comando desenvolvido em PHP que consome a API do Banco Central para consultar a cotação diária do dólar e realizar a conversão para reais (BRL). A API fornece informações sobre a cotação do dólar em um período específico, permitindo que o usuário consulte a cotação mais recente e converta valores em dólar para reais.

## Funcionalidades

- Consulta à API do Banco Central para obter a cotação diária do dólar.
- Conversão de valores em dólar (USD) para reais (BRL) com base na cotação obtida.
- Exibição das informações da cotação e do resultado da conversão.

## API Utilizada

A cotação do dólar é obtida por meio da API pública do Banco Central do Brasil. A API oferece informações sobre a cotação do dólar em um período específico, permitindo consultas detalhadas. Você pode acessar a API pelo seguinte link:

[API de Cotação Dólar - Banco Central](https://olinda.bcb.gov.br/olinda/servico/PTAX/versao/v1/odata/CotacaoDolarPeriodo(dataInicial=@dataInicial,dataFinalCotacao=@dataFinalCotacao)?@dataInicial='08-18-2023'&@dataFinalCotacao='08-25-2023'&$top=1&$orderby=dataHoraCotacao%20desc&$format=json&$select=cotacaoCompra,dataHoraCotacao)

Certifique-se de que o link seja válido e esteja acessível para obter as informações mais recentes sobre a cotação do dólar. 
## Contato

Se você tiver alguma dúvida relacionada a este repositório ou quiser bater um papo, não hesite em entrar em contato comigo pelo [email](mailto:ruanhborges@gmail.com).


