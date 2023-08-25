# conversorBRLtoUSD

Consumo de API do banco central para consultar a cotação diária do dólar e converter em BRL, usando PHP.

Link API: https://olinda.bcb.gov.br/olinda/servico/PTAX/versao/v1/odata/CotacaoDolarPeriodo(dataInicial=@dataInicial,dataFinalCotacao=@dataFinalCotacao)?@dataInicial='08-18-2023'&@dataFinalCotacao='08-25-2023'&$top=1&$orderby=dataHoraCotacao%20desc&$format=json&$select=cotacaoCompra,dataHoraCotacao
