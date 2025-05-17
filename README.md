# Projetos Imersão IA 2025
Programa sugestor do que se deve comprar, inclusive a quantidade, a partir de um histórico de compras

#O problema

Sempre que vou fazer compras fico na dúvida do que devo compra.
Acontece sempre de logo no dia seguinte sentir falta de algum item
Muita vezes também percebo que comprei algo que já tinha em casa

#A solução

Se analisarmos nossas compras é possível identificar o que compramos e a frequência
Conseguimos principalmente calcular o consumo diário e fazer uma compra mais precisa e 
organizada, evitando itens de mais e de menos

#
Esse projeto processa um histórico de compras e defini o que dever ser comprado
e a quantidade de cada item a depender do seu consumo

#Entradas
Histórico de compras:
 PDFs com a lista de compras contendo o item, quantidade e preço (no futuro pode ser criado um agente para transformar a nota fiscal em PDF nesse formato)
 A título de exemplo, tem alguns pdfs na pasta /content/compras do repositório. Se tiver seu histório, basta substituir o conteúdo

quatidade_dias_proxima_compra
 Vai ser solicitado para o usuário a quantidade de dias que a compra vai abastercer. Baseado na média de consumo por dia e essa informação, vai ser sugerida uma quandidade para próxima compra
