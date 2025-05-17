# Projetos Imersão IA 2025
Programa sugestor do que se deve comprar, inclusive a quantidade, a partir de um histórico de compras

#O problema

Sempre que vou fazer compras fico na dúvida do que devo comprar.
Acontece sempre de logo no dia seguinte sentir falta de algum item e muita vezes também percebo que comprei algo que já tinha bastante em casa.

#A solução

Se analisarmos nossas compras é possível identificar o que compramos e a frequência.
Conseguimos principalmente calcular o consumo diário e fazer uma compra mais precisa e 
organizada, evitando itens de mais ou de menos;

#
Esse projeto processa um histórico de compras, identifica a média de consumo de cada item e no fim sugere uma lista de compras, informando a quantidade a ser comprada para suprir a necessidade dos dias de estoque desejado.

#Entradas

Histórico de compras:

 Cada compra deve ser um pdf contendo os itens, informando a quantidade, unidade de medida e preço (no futuro pode ser criado um agente para transformar a nota fiscal em PDF nesse formato);

 O título do pdf deve ser a data da compra;

 Os pdf têm que está na pasta /content/compras;
 
 A título de exemplo, tem alguns pdfs na pasta /content/compras do repositório. Se tiver seu pŕoprio histório, basta substituir o conteúdo.

Quantidade de dias a serem abastecidos:

 Vai ser solicitado para o usuário a quantidade de dias que a compra vai abastercer. Baseado na média de consumo por dia e essa informação, conseguimos calcular a quandidade para próxima compra.
