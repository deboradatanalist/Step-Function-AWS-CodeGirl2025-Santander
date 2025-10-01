# Projeto AWS Step Function

## Step Function
AWS Step Functions é um serviço que permite coordenar múltiplos serviços da AWS em um workflow serverless. É como um organizador visual para os componentes da sua aplicação. Em vez de escrever código para gerenciar lógicas complexas, é definido uma máquina de estados que orquestra o fluxo da sua aplicação. Pode-se arrastar e soltar etapas, como uma função Lambda, uma tarefa no ECS ou um trabalho no Glue, e o Step Functions vai gerenciar todo o processo, incluindo monitorar o progresso, tratar falhas e fornecer logs detalhados para cada etapa.
Se os serviços que serão utilizados no projeto escolhido não estiverem ativos esse serviço os criam e inicializam eles de forma automatica.

## Projeto
Escolhi este projeto que mostra a construção de um workflow utilizando o Step Function na AWS para transferir registros de dados com Lambda, DynamoDB e Amazon SQS.
onde o Lambda, DynamoDB e o amazon SQS não estavam criados e foram iniciados automaticamente pelo step function.
![Step Funtion] (step function.png)

### Lambda
O AWS Lambda é um serviço de computação serverless que permite rodar código sem precisar se preocupar com servidores. Faz o upload do seu código (como uma função em Python, Node.js ou Java), e a AWS cuida de todo o resto: o provisionamento dos servidores, a execução do código e o escalonamento.

O Lambda é a execução "orientada a eventos" (event-driven), o código só é executado em resposta a um trigger (gatilho).
