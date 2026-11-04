# Fluxo 1: LAGEAMB Solicitação Diárias : Ao solicitar Diária

Este fluxo do Power Automate monitora uma lista do SharePoint. Sempre que um novo item é criado, ele atualiza esse item com informações específicas, como local de viagem, nome do colaborador, datas e justificativa, usando os dados fornecidos no momento da criação. O objetivo é garantir que os dados do item estejam completos e atualizados automaticamente.

# Fluxo 2: LAGEAMB Solicitação Ressarcimento: Ao solicitar Ressarcimento
Este fluxo do Power Automate monitora uma lista do SharePoint. Sempre que um novo item é criado, ele atualiza esse item com informações específicas, como o ID do colaborador e o nome completo, usando os dados do item recém-criado. O objetivo é garantir que os campos do item sejam preenchidos ou atualizados automaticamente após a criação.

# Fluxo 3: LAGEAMB Solicitação Prestação de Contas: Ao solicitar Prestação
Este fluxo é acionado quando um novo item é criado em uma lista do SharePoint. Após o acionamento, ele atualiza o item recém-criado com informações específicas, como ID do colaborador, nome completo e destino da viagem, usando os dados do próprio item. Tudo ocorre automaticamente a cada minuto.

# Fluxo 4: Envio de email ajuste - solicitação de diárias
Este fluxo monitora alterações em itens ou arquivos de uma lista do SharePoint. Quando um item é modificado, ele obtém os detalhes desse item e verifica o campo "Verificação". Se o valor não for "Verificado" nem "Não verificado", o fluxo envia um e-mail automático ao autor do item, solicitando ajustes em arquivos específicos, com um link para o aplicativo de diárias.

# Fluxo 5: Envio de email ajuste - Ressarcimento
Este fluxo monitora alterações em itens ou arquivos de uma lista do SharePoint. Quando um item é modificado, ele obtém os detalhes desse item e verifica o valor do campo "Verificação". Se o campo não estiver marcado como "Verificado" ou "Não verificado", o fluxo envia um e-mail automático ao autor do item, solicitando ajustes na solicitação de ressarcimento.

# Fluxo 6: Envio de email ajuste - Prestação de Contas
Este fluxo do Power Automate monitora alterações em itens ou arquivos de uma lista do SharePoint. Quando um item é modificado, ele obtém os detalhes desse item e verifica o campo "Verificação". Se o valor não for "Verificado" nem "Não verificado", o fluxo envia um e-mail automático ao autor do item, solicitando ajustes na prestação de contas, com um link para o aplicativo de pendências.

# Fluxo 7: Gerar arquivo xlsx Prestacao
Este fluxo automatiza a criação de uma planilha de prestação de contas de viagens:

1.Recebe dados do Power Apps. 
2.Analisa o JSON recebido. 
3.Obtém um template de XLSX no SharePoint. 
4.Cria uma cópia desse template. 
5.Adiciona linhas na tabela do arquivo com os dados recebidos. 
6.Aguarda a construção da tabela. 
7.Retorna o caminho do arquivo para o Power Apps. 
8.Dá tempo para o usuário baixar o arquivo. 
9.Exclui o arquivo após o tempo definido.

# Fluxo 8: Gerar arquivo xlsx Ressarcimento
Este fluxo automatiza a criação de uma planilha de ressarcimento a partir de dados enviados pelo Power Apps. Ele:

1.Recebe dados em JSON do Power Apps. 
2.Analisa o JSON e obtém um template de XLSX no SharePoint. 
3.Cria uma cópia do template. 
4.Adiciona linhas na tabela do Excel com os dados recebidos. 
5.Aguarda a construção da tabela. 
6.Retorna o caminho do arquivo ao Power Apps. 
7.Dá tempo para o usuário baixar o arquivo. 
8.Exclui o arquivo após o tempo definido.

# Fluxo 9: Gerar arquivo xlsx
Este fluxo automatiza a criação de uma planilha de solicitações de diárias. Ele recebe dados do Power Apps, analisa o JSON, copia um template de Excel do SharePoint, adiciona linhas com as informações recebidas, aguarda a construção da tabela, responde ao Power Apps com o caminho do arquivo, espera o usuário baixar o arquivo e, por fim, exclui o arquivo do SharePoint após 10 minutos. Tudo é feito de forma automática, facilitando o processo de registro e controle das solicitações.

# Fluxo 10: Cópia de Resposta - Email Diárias
Este fluxo automatiza o envio de um e-mail com um resumo de uma solicitação de diárias. Ele é acionado quando um item é criado em uma lista do SharePoint, coleta informações detalhadas sobre a solicitação, processa dados de reservas, transportes e demandas de campo, compõe um resumo em HTML e envia para o solicitante um e-mail automático com todos os detalhes da viagem e orientações.

# Fluxo 11: Cópia de Resposta - Email Prestação
Este fluxo automatiza o envio de um e-mail quando um item é criado em uma lista do SharePoint. Ele obtém os dados do item, compõe um resumo em HTML com informações relevantes e envia esse resumo por e-mail ao autor do item, informando sobre a solicitação de prestação de contas.





