# Projeto AWS Step Function

Este projeto mostra a construção de um workflow utilizando o Step Function na AWS para transferir registros de dados com Lambda, DynamoDB e Amazon SQS.

## Step Function
AWS Step Functions é um serviço que permite coordenar múltiplos serviços da AWS em um workflow serverless. É como um organizador visual para os componentes da sua aplicação. Em vez de escrever código para gerenciar lógicas complexas, é definido uma máquina de estados que orquestra o fluxo da sua aplicação. Pode-se arrastar e soltar etapas, como uma função Lambda, uma tarefa no ECS ou um trabalho no Glue, e o Step Functions vai gerenciar todo o processo, incluindo monitorar o progresso, tratar falhas e fornecer logs detalhados para cada etapa.
Se os serviços que serão utilizados no projeto escolhido não estiverem ativos esse serviço os criam e inicializam eles de forma automatica.

