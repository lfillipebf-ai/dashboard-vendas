# Fórmulas úteis

Faturamento por linha:
=quantidade*preco_unitario*(1-desconto)

Total de faturamento:
=SOMA(Vendas[faturamento])

Itens vendidos:
=SOMA(Vendas[quantidade])

Quantidade de pedidos:
=CONT.VALORES(Vendas[id_venda])

Ticket médio:
=TotalFaturamento/QuantidadePedidos

Média de desconto:
=MÉDIA(Vendas[desconto])

Os nomes das funções podem aparecer em inglês conforme a configuração regional do Excel.
