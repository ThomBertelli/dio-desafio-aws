# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 12/06/2025
Empresa: Abstergo Industries
Responsável: [Nome do Responsável pelo Projeto]

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por [Nome do Responsável pelo Projeto]. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e a longo prazo, considerando que a empresa atualmente não possui uma solução em nuvem e busca migrar sua infraestrutura para a AWS.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Amazon S3 (Simple Storage Service)

- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de dados escalável, seguro e de baixo custo.
- **Descrição de caso de uso:** Para uma distribuidora farmacêutica, o Amazon S3 pode ser utilizado para armazenar grandes volumes de dados, como registros de inventário, dados de pedidos, documentos regulatórios, dados de pesquisa e desenvolvimento, e backups de sistemas. A migração de soluções de armazenamento on-premise para o S3 elimina a necessidade de comprar e manter hardware de armazenamento, reduzindo custos de capital e operacionais (energia, refrigeração, manutenção).

### Etapa 2: AWS Lambda

- **Nome da ferramenta:** AWS Lambda
- **Foco da ferramenta:** Execução de código sem servidor (serverless), pagando apenas pelo tempo de computação consumido.
- **Descrição de caso de uso:** O AWS Lambda pode ser empregado para automatizar processos críticos da distribuidora, como o processamento de pedidos recebidos, a atualização de inventário em tempo real, a geração de relatórios de vendas ou a integração com sistemas de parceiros. Ao utilizar o Lambda, a empresa elimina a necessidade de provisionar e gerenciar servidores para essas tarefas, resultando em uma significativa redução de custos de infraestrutura e gerenciamento, além de escalar automaticamente para atender à demanda.

### Etapa 3: Amazon EC2 (Elastic Compute Cloud) com Auto Scaling

- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud) com Auto Scaling
- **Foco da ferramenta:** Fornecimento de capacidade computacional escalável sob demanda, ajustando automaticamente os recursos para atender à carga de trabalho.
- **Descrição de caso de uso:** Para a distribuidora farmacêutica, o Amazon EC2 com Auto Scaling pode hospedar aplicações essenciais, como o sistema de gestão de armazém (WMS), o sistema de gerenciamento de relacionamento com o cliente (CRM) ou portais de comunicação com as empresas parceiras. A capacidade de escalar automaticamente para cima ou para baixo garante que a empresa pague apenas pelos recursos computacionais que realmente utiliza, evitando o superprovisionamento e o desperdício de recursos, o que é comum em infraestruturas on-premise. Isso resulta em otimização de custos e alta disponibilidade das aplicações.


