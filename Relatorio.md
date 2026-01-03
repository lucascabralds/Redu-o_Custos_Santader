# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 03/01/2026
Empresa: Abstergo Industries
Responsável: Lucas Cabral

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Lucas Cabral. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Amazon EC2 Spot Instances
- **Foco da ferramenta:** Redução de custos em computação (até 90% de desconto em relação ao preço On-Demand).
- **Descrição de caso de uso:** Utilização de instâncias Spot para ambientes de desenvolvimento, testes e processamento de dados em lote (Big Data), onde interrupções ocasionais são toleráveis. Isso permite manter a capacidade de processamento necessária por uma fração do preço original.

### Etapa 2: Amazon S3 Intelligent-Tiering
- **Foco da ferramenta:** Otimização automática de custos de armazenamento.
- **Descrição de caso de uso:** Armazenamento de logs de acesso e backups de longo prazo. O S3 Intelligent-Tiering monitora os padrões de acesso dos objetos e move automaticamente os dados que não foram acessados por 30 dias para uma camada de armazenamento mais barata (Infrequent Access), sem impacto na performance ou sobrecarga operacional de gerenciamento manual.

### Etapa 3: AWS Cost Explorer
- **Foco da ferramenta:** Visualização, entendimento e gerenciamento dos custos e uso da AWS.
- **Descrição de caso de uso:** Implementação de painéis para identificar recursos ociosos (como instâncias EC2 ligadas sem uso ou volumes EBS "órfãos") e analisar tendências de gastos. A ferramenta permite detectar anomalias de custo rapidamente e ajustar o orçamento antes que ele seja excedido.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução dos custos operacionais da infraestrutura em nuvem e o aumento da transparência financeira, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- [Documentação Oficial - Amazon EC2 Spot Instances](https://aws.amazon.com/ec2/spot/)
- [Guia de Preços - Amazon S3](https://aws.amazon.com/s3/pricing/)
- [Manual do Usuário - AWS Cost Explorer](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html)

Assinatura do Responsável pelo Projeto:

Lucas Cabral