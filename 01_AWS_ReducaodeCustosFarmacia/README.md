RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 21/11/2025
Empresa: Abstergo Industries
Responsável: Victor Biscaia

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Victor Biscaia. O objetivo do projeto foi selecionar três serviços da AWS com a finalidade de reduzir custos de forma imediata, além de modernizar a arquitetura de TI para suportar um hub de distribuição de medicamentos.

Descrição do Projeto
O projeto foi dividido em três etapas, cada uma com objetivos específicos:
Etapa 1
- AWS Lambda (Serverless)
- Foco da ferramenta: Execução de código sob demanda, sem necessidade de gerenciar servidores.
- Caso de uso: Automatizar processos de entrada e saída de pedidos, validar dados de estoque e integrar com sensores IoT (como monitoramento de temperatura em medicamentos sensíveis).
Etapa 2
- Amazon SQS (Simple Queue Service)
- Foco da ferramenta: Gerenciamento de filas de mensagens para comunicação assíncrona entre sistemas.
- Caso de uso: Garantir que pedidos de medicamentos sejam processados de forma confiável, evitando sobrecarga e perdas de informação em momentos de alta demanda.
Etapa 3
- Amazon SNS (Simple Notification Service)
- Foco da ferramenta: Distribuição de mensagens em tempo real.
- Caso de uso: Notificar gestores e equipes sobre estoque crítico, enviando alertas para múltiplos canais (e-mail, SMS, aplicativos).

Sugestão de Banco de Dados (Economia)
Para complementar a arquitetura e garantir a persistência dos dados de estoque e histórico de pedidos, recomenda-se o uso do Amazon DynamoDB:
- Motivos da escolha:
- Modelo NoSQL totalmente gerenciado.
- Escalabilidade automática e cobrança apenas pelo uso.
- Ideal para cenários de alta demanda e consultas rápidas.
- Reduz custos operacionais em comparação com bancos relacionais tradicionais.

Linkedin: https://www.linkedin.com/in/victor-biscaia-097603371/
