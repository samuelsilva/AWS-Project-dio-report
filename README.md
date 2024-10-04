# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 04 de Outubro de 2024  
Empresa: Abstergo Industries  
Responsável: Samuel Dario da Silva

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Samuel Dario da Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de reduzir custos com infraestrutura e melhorar a comunicação e integração com outras empresas do setor, uma vez que a Abstergo deseja se tornar um HUB de distribuição.

## Descrição do Projeto
O projeto de implementação foi dividido em 3 etapas, cada uma utilizando um serviço AWS específico para otimizar custos e garantir a escalabilidade e segurança da infraestrutura da Abstergo Industries.

### Etapa 1: Amazon EC2 (Elastic Compute Cloud)
- **Foco da ferramenta:** Otimização de custos com infraestrutura de servidores
- **Descrição de caso de uso:** O Amazon EC2 oferece uma solução escalável para hospedar as aplicações da Abstergo Industries, eliminando a necessidade de servidores físicos. Com essa ferramenta, a empresa pode escolher instâncias adequadas ao perfil de suas cargas de trabalho, ajustando dinamicamente a capacidade computacional conforme a demanda. Isso permite um controle preciso dos custos, já que o pagamento é feito apenas pelos recursos efetivamente consumidos, proporcionando flexibilidade e alta disponibilidade para as operações da empresa.


### Etapa 2: Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de dados seguro, escalável e com alta durabilidade
- **Descrição de caso de uso:** O Amazon S3 é uma solução de armazenamento em nuvem altamente flexível, que permite à Abstergo Industries armazenar volumes massivos de dados de forma segura, escalável e acessível globalmente. Utilizando criptografia integrada e múltiplas camadas de redundância, o S3 assegura que os dados da empresa, como documentos críticos, registros de transações comerciais e catálogos de produtos, sejam protegidos contra perda ou acessos não autorizados. 

Além disso, o Amazon S3 oferece fácil integração com outros serviços da AWS, permitindo a automação de processos de backup e recuperação de desastres, o que é essencial para garantir a continuidade dos negócios. A Abstergo poderá acessar os dados rapidamente de qualquer parte do mundo, facilitando a comunicação com seus parceiros e clientes. O modelo de cobrança é baseado na quantidade de dados armazenados e transferidos, permitindo que a empresa otimize os custos conforme o volume de dados cresce, sem comprometer a segurança ou a performance.


### Etapa 3: AWS Lambda
- **Foco da ferramenta:** Execução de código sob demanda, sem necessidade de provisionamento ou gerenciamento de infraestrutura
- **Descrição de caso de uso:** O AWS Lambda permite que a Abstergo Industries execute código em resposta a eventos específicos de forma altamente eficiente e escalável, sem a necessidade de manter ou gerenciar servidores. Isso é ideal para tarefas que ocorrem de forma intermitente, como o envio de notificações automáticas, geração de relatórios personalizados, ou até mesmo a integração em tempo real com APIs de parceiros comerciais.

Com o Lambda, o código é executado automaticamente quando disparado por eventos pré-definidos, como uma nova transação ou a atualização de um catálogo de produtos. Essa abordagem de "computação serverless" elimina a complexidade de gerenciar infraestrutura de servidores, já que o serviço escala automaticamente conforme a demanda aumenta ou diminui, garantindo que a empresa pague apenas pelo tempo de execução do código. Isso resulta em uma economia significativa, especialmente para processos de curta duração ou pouco frequentes.

Além disso, AWS Lambda integra-se facilmente a outros serviços da AWS, como S3, DynamoDB, e SNS, permitindo a criação de pipelines automatizados e orquestrando fluxos de trabalho complexos sem a necessidade de intervenção manual. Isso simplifica a automação de processos internos da Abstergo, garantindo maior agilidade e eficiência operacional.



## Conclusão

A implementação dos serviços AWS na Abstergo Industries proporcionará uma infraestrutura mais flexível, escalável e otimizada para suas operações como HUB de distribuição no setor farmacêutico. O uso do Amazon EC2 para substituir servidores físicos com instâncias sob demanda garante uma redução significativa nos custos de manutenção e gerenciamento de hardware, além de oferecer alta disponibilidade e flexibilidade para atender picos de demanda.

O Amazon S3, por sua vez, permite que a empresa armazene e gerencie grandes volumes de dados de forma segura e acessível globalmente, facilitando a integração e a comunicação com seus parceiros comerciais, além de assegurar a integridade e proteção dos dados críticos da empresa. Essa solução se destaca pelo modelo de cobrança sob demanda, ajustado ao crescimento do volume de dados, maximizando a eficiência de custos.

Por fim, a adoção do AWS Lambda elimina a necessidade de infraestrutura permanente para tarefas intermitentes, automatizando processos e permitindo a execução de código sob demanda com alta eficiência e baixa latência. Essa abordagem "serverless" reduz ainda mais os custos operacionais e melhora a agilidade na resposta a eventos de negócios, como a integração com APIs e a geração de relatórios.

Com essas três ferramentas, a Abstergo Industries estará preparada para enfrentar os desafios de comunicação e operação como um HUB de distribuição, ao mesmo tempo que reduz significativamente os custos de infraestrutura e garante um ambiente escalável, seguro e eficiente. Recomenda-se a continuidade da utilização desses serviços e a expansão para outras ferramentas da AWS que possam otimizar ainda mais os processos da empresa.



## Anexos
- Documentação técnica de cada serviço implementado
- Planilhas de custos estimados
- Diagramas de arquitetura da solução

Assinatura do Responsável pelo Projeto:

Samuel Dario da Silva
