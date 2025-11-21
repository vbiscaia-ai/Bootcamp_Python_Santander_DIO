# RELATÓRIO DE IMPLEMENTAÃ‡ÃƒO DE SERVIÇOS AWS

Data: [21/11/2025]
Empresa: Abstergo Industries 
ResponsÃ¡vel: [Victor Biscaia]

## Introdução
Este relatÃ³rio apresenta o processo de implementaÃ§Ã£o de ferramentas na empresa [Abstergo Industries], realizado por [Victor Biscaia]. O objetivo do projeto foi elencar 3 serviÃ§os AWS, com a finalidade de realizar diminuiÃ§Ã£o de custos imediatos.

## Descrição do Projeto
O projeto de implementaÃ§Ã£o de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especÃ­ficos. A seguir, serÃ£o descritas as etapas do projeto:

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos.


Etapa 1
- AWS Lambda (Serverless)
- Foco da ferramenta: Execução de código sob demanda, sem necessidade de gerenciar servidores.
- Descrição de caso de uso: Automatizar processos de entrada e saída de pedidos, validar dados de estoque e integrar com sensores IoT (como monitoramento de temperatura em medicamentos sensíveis).

Etapa 2
- Amazon SQS (Simple Queue Service)
- Foco da ferramenta: Gerenciamento de filas de mensagens para comunicação assíncrona entre sistemas.
- Descrição de caso de uso: Garantir que pedidos de medicamentos sejam processados de forma confiável, evitando sobrecarga e perdas de informação em momentos de alta demanda.


Etapa 3
- Amazon SNS (Simple Notification Service)
- Foco da ferramenta: Distribuição de mensagens em tempo real.
- Descrição de caso de uso: Notificar gestores e equipes sobre estoque crítico, enviar alertas para múltiplos canais (e-mail, SMS, aplicativos).

Sugestão de Banco de Dados (Economia)
Para complementar a arquitetura e garantir persistência dos dados de estoque e histórico de pedidos, recomenda-se o uso do Amazon DynamoDB:
- Motivo da escolha:
- Modelo NoSQL totalmente gerenciado.
- Escalabilidade automática e cobrança apenas pelo uso.
- Ideal para cenários de alta demanda e consultas rápidas.
- Reduz custos operacionais em comparação com bancos relacionais tradicionais