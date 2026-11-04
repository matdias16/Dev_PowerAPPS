# Fluxo 1: LAGEAMB Reserva Carros - IDS: Deletar Placas

1. É acionado quando um item é criado ou modificado em uma lista do SharePoint. 
2. Verifica se os campos DtHoraDevEfetiva e Placas não estão vazios. 
3. Se a condição for verdadeira, obtém o item, atualiza alguns campos e busca itens relacionados em outra lista. 
4. Para cada item relacionado, verifica se o campo ReservaIDNum corresponde ao ID do item principal e, se sim, exclui esse item. 
5. Se a condição inicial for falsa, o fluxo é encerrado como cancelado.
Tudo automatizado para gerenciar reservas e devoluções.

# Fluxo 2: LAGEAMB Reserva Carros - IDS: Ao inserir Carro
1. Dispara quando um item é criado em uma lista do SharePoint. 
2. Atualiza esse item com informações de reserva e carro. 
3. Busca itens relacionados pela ReservaIDNum. 
4. Inicializa uma variável para armazenar placas. 
5. Para cada item encontrado, obtém detalhes do carro e acrescenta a placa à variável. 
6. Inicializa outra variável com o nome da tabela. 
7. Atualiza o item principal com as placas coletadas.

Ou seja, ele consolida placas de carros relacionadas a uma reserva e atualiza o item principal com essas informações.

# Fluxo 3: LAGEAMB Reserva Carros : Ao solicitar reserva
Esse fluxo está monitorando uma lista do SharePoint chamada "Reserva Carros". Sempre que um novo item é criado nessa lista, o fluxo é acionado (a cada minuto). Em seguida, ele atualiza esse mesmo item com alguns campos específicos, como ID do colaborador, datas, quantidade de carros, finalidade, cidade e assentamento.

O fluxo detecta novos itens na lista do SharePoint e atualiza esses itens automaticamente com informações selecionadas.


