# 📊 Relatório de Implementação de Serviços AWS  

**Data:** 21/11/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Victor Biscaia  

---

## 📌 Introdução  
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Victor Biscaia**.  
O objetivo do projeto foi selecionar **3 serviços AWS** com a finalidade de reduzir custos de forma imediata e modernizar a arquitetura de TI para suportar um hub de distribuição de medicamentos.  

---

## 🚀 Descrição do Projeto  
O projeto foi dividido em **3 etapas**, cada uma com objetivos específicos:  

---

### 🟢 Etapa 1 – AWS Lambda (Serverless)  
- **Foco da ferramenta:** Execução de código sob demanda, sem necessidade de gerenciar servidores.  
- **Caso de uso:**  
  - Automatizar processos de entrada e saída de pedidos.  
  - Validar dados de estoque.  
  - Integrar com sensores IoT (como monitoramento de temperatura em medicamentos sensíveis).  

---

### 🔵 Etapa 2 – Amazon SQS (Simple Queue Service)  
- **Foco da ferramenta:** Gerenciamento de filas de mensagens para comunicação assíncrona entre sistemas.  
- **Caso de uso:**  
  - Garantir que pedidos de medicamentos sejam processados de forma confiável.  
  - Evitar sobrecarga em momentos de alta demanda.  
  - Prevenir perdas de informação.  

---

### 🟣 Etapa 3 – Amazon SNS (Simple Notification Service)  
- **Foco da ferramenta:** Distribuição de mensagens em tempo real.  
- **Caso de uso:**  
  - Notificar gestores e equipes sobre estoque crítico.  
  - Enviar alertas para múltiplos canais (e-mail, SMS, aplicativos).  
  - Integrar com SQS para que diferentes sistemas recebam os mesmos eventos.  

---

## 💾 Sugestão de Banco de Dados (Economia)  
Para complementar a arquitetura e garantir a persistência dos dados de estoque e histórico de pedidos, recomenda-se o uso do **Amazon DynamoDB**:  

- Modelo **NoSQL** totalmente gerenciado.  
- Escalabilidade automática e cobrança apenas pelo uso.  
- Ideal para cenários de alta demanda e consultas rápidas.  
- Reduz custos operacionais em comparação com bancos relacionais tradicionais.  

---

## ✅ Conclusão  
A arquitetura proposta combina **Lambda + SQS + SNS** para processamento e mensageria, com **DynamoDB** como camada de persistência econômica e escalável.  
Essa solução garante **redução de custos**, **alta disponibilidade** e **eficiência operacional** para o hub de distribuição de medicamentos da Abstergo Industries.  

Linkedin: https://www.linkedin.com/in/victor-biscaia-097603371/
