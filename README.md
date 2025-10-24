# StepFunction_Dio_Santander_Code-Girls_Desafio-2
Este repositório é dedicado à demonstração prática e simplificada do meu aprendizado sobre AWS Step Functions, adquirido durante o curso Code Girls. O objetivo principal é consolidar o conhecimento e servir como um portfólio de exemplos funcionais. Aqui você encontrará o Segundo Desafio proposto pela Dio, utilizando o GitHub para colaboração.


<img width="400" height="680" alt="Captura de Tela 2025-10-24 às 08 11 58" src="https://github.com/user-attachments/assets/29cc8860-981e-424c-96c9-7816a79e6906" />

Como funciona na prática?
1.	Orquestração visual: Usando uma interface de arrastar e soltar chamada Workflow Studio, você pode criar um diagrama que representa o seu fluxo de trabalho.
2.	Coordenação de serviços: Cada etapa no seu diagrama pode ser uma ação em outro serviço da AWS, como:
1.	Executar uma função AWS Lambda: Para processar dados ou executar lógica de negócios.
2.	Comunicar-se com um banco de dados: Como o DynamoDB.
3.	Armazenar arquivos: Em um bucket S3.
4.	Enviar mensagens: Para uma fila SQS ou um tópico SNS.
3.	Tratamento de erros e lógica: O Step Functions também se encarrega de coisas como:
1.	Tentativas automáticas: Se uma etapa falhar, ele pode tentar novamente automaticamente.
2.	Lógica condicional: Ele pode tomar decisões, como "se o processamento for bem-sucedido, faça isso; se falhar, faça aquilo".
3.	Execução paralela: Ele pode executar várias etapas ao mesmo tempo, se necessário.
4.	Monitoramento: Enquanto o fluxo de trabalho está em execução, você pode ver em tempo real qual etapa está sendo executada e inspecionar o estado dos dados em cada passo, facilitando a depuração. 

