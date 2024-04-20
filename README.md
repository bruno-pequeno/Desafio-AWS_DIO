# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 18/04/2024

Empresa: Abstergo Industries 

Responsável: Bruno Pequeno

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries , realizado por Bruno Pequeno. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

AWS Lambda
Foco da ferramenta: Computação sem servidor
Descrição de caso de uso: A AWS Lambda pode ser usada para automatizar tarefas repetitivas e processos manuais na distribuidora de remédios. Por exemplo, sempre que um novo pedido de remédios é recebido, o AWS Lambda pode ser acionado para processar automaticamente o pedido, atualizar o inventário, gerar faturas e enviar confirmações por e-mail para clientes. Isso ajuda a acelerar o processamento de pedidos, reduzindo a necessidade de intervenção manual e potencialmente reduzindo erros.
Etapa 2:

Amazon S3 (Simple Storage Service)
Foco da ferramenta: Armazenamento de dados na nuvem
Descrição de caso de uso: O Amazon S3 pode ser utilizado para armazenar de forma segura e escalável todos os dados da distribuidora, incluindo informações de produtos, registros de pedidos, documentos de clientes, entre outros. Isso elimina a necessidade de manter servidores locais e fornece acesso fácil aos dados de qualquer lugar e a qualquer momento. Além disso, o S3 oferece recursos de segurança avançados, como criptografia de dados em repouso e em trânsito, garantindo a integridade e confidencialidade das informações.
Etapa 3:

Amazon SQS (Simple Queue Service)
Foco da ferramenta: Filas de mensagens na nuvem
Descrição de caso de uso: O Amazon SQS pode ser utilizado para gerenciar a comunicação assíncrona entre diferentes partes do sistema da distribuidora de remédios. Por exemplo, sempre que um novo pedido é recebido, uma mensagem pode ser enviada para uma fila do SQS, indicando que um novo pedido precisa ser processado. Em seguida, outros componentes do sistema, como sistemas de gerenciamento de inventário ou sistemas de faturamento, podem ler essas mensagens da fila e executar suas tarefas correspondentes. Isso ajuda a desacoplar e escalonar os diferentes componentes do sistema, garantindo um processamento eficiente e confiável dos pedidos.

## Conclusão
A implementação das ferramentas na empresa Abstergo Industries tem como esperado benefícios significativos que aumentarão a eficiência e a produtividade da empresa. A utilização do AWS Lambda permitirá a automação de tarefas, o Amazon S3 trará melhorias no armazenamento e gerenciamento de dados, enquanto o Amazon SQS melhorará a comunicação entre sistemas. Essas melhorias resultarão em uma redução do tempo gasto em tarefas administrativas, acesso rápido e seguro aos dados, e maior flexibilidade no processamento de tarefas, contribuindo para uma operação mais eficiente e eficaz da empresa.

Assinatura do Responsável pelo Projeto:
    Bruno Pequeno
