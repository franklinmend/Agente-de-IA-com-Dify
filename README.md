📌 **Projeto: Agente de IA para Atendimento Automatizado (n8n + Dify)**

Desenvolvi um **Agente de IA para atendimento automatizado**, utilizando o **n8n** como orquestrador e integração via **API com a plataforma Dify** para processamento inteligente de mensagens.

O objetivo deste projeto foi demonstrar, na prática, **orquestração de agentes de IA**, integração entre sistemas via **Webhooks e APIs REST**, além do uso estratégico de **JavaScript**, sem dependência direta de banco de dados.

O fluxo foi inspirado em um projeto anterior com RAG, porém adaptado para um **cenário stateless**, priorizando simplicidade, performance e controle de custos.

🧠 **Arquitetura do fluxo**
Webhook → Padronização de dados → Chamada à API de IA → Tratamento da resposta (JavaScript) → Retorno ao usuário

🔧 **Tecnologias utilizadas**
- n8n (automação de workflows)
- Dify API (agentes de IA)
- JavaScript (Code Node)
- Webhooks
- APIs REST
- JSON

⚙️ **Destaques técnicos**
- Arquitetura desacoplada e stateless  
- Integração direta com agente de IA via API  
- Uso de JavaScript para:
  - tratamento de respostas  
  - validação de erros  
  - controle do fluxo  
- Redução de custos com IA ao filtrar e organizar respostas  
- Estrutura preparada para escalar com logs, cache e fallback sem IA  

🔐 **Segurança e boas práticas**
- Autenticação via API Token  
- Nenhum dado sensível armazenado localmente  
- Pronto para monitoramento e rate limiting  

📈 Projeto focado em **IA aplicada, automação inteligente e integração de sistemas**, alinhado às exigências do mercado para áreas de **IA, Automação e Engenharia de Software**.

Para mais detalhes sobre o projeto, acesse meu GitHub disponível no perfil.
