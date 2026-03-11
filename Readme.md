# Chatbot 24h 

## 🎯Objetivo

Responder automaticamente perguntas de clientes como:
  - Horário de funcionamento;
  - Preços e valores;
  - Localização;
  - Formas de pagamento;
  - Status do pedido;
  - Dúvidas comuns e recorrentes.   
  
 ## ⚙ Requisitos Funcionais

 ### 👤 Painel administrativo
 A empresa ou PJ deve poder: 
 - Cadastrar perguntas;
 - Editar respostas;
 - Ver histórico de conversas (pergunta do cliente | resposta do bot | data e hora).

### 🔁 Encaminhamento para humano
Se o bot não conseguir resolver o problema do cliente, o atendimento deve ser encaminhado para um atendente. 

## 👣 Requisitos Não-Funcionais

### 🛡️ Segurança e Privacidade
Proteção de Dados (LGPD): O histórico de conversas deve ser armazenado de forma segura, e dados sensíveis de clientes (como CPFs ou telefones) devem ser tratados com protocolos de privacidade.

### 📈 Escalabilidade e Manutenibilidade
Modularidade: O código deve ser separado entre a lógica do chatbot (Cérebro), a interface (Frontend) e a gestão de dados (Banco de Dados); 

## 🚧 Arquitetura e estrutura do código 
**Backend**: Python; 
**Fronted**: Html e Css; 
**Banco de dados**: MySQL; 

### 🚦 Estrutura do projeto 
_Sujeita a alterações_ 

chatbot-24h/
├── app.py              
├── database.db         
├── static/             
│   └── style.css       
└── templates/         
    ├── chat.html       
    └── admin.html      


