# Projeto: Copiloto de IA para Comunicação Interna (RH)
## 📋 Sobre o Projeto
Esta é uma solução inteligente de automação de workflow que utiliza IA Generativa para auxiliar o departamento de RH no gerenciamento de comunicações repetitivas. O sistema transforma solicitações informais em respostas estruturadas, garantindo rapidez e padronização.

## 🛠️ Tecnologias Utilizadas
Make.com: Plataforma de integração e automação de workflow.

Google Gemini AI: Modelo de linguagem (LLM) para processamento de linguagem natural e geração de texto.

Gmail: Interface de entrada e saída para comunicação com os colaboradores.

Google Sheets: Banco de dados para log, auditoria e histórico de demandas.

## 🚀 Como Funciona (Instruções de Uso)
Gatilho: Envie um e-mail para a conta de suporte do projeto rh.empresa.adm26@gmail.com com qualquer dúvida ou solicitação (ex: dúvidas sobre benefícios, rascunhos de avisos, solicitações de férias).

Automação: O sistema detecta o novo e-mail automaticamente.

Inteligência: O Gemini analisa o texto, redige a resposta e cria um resumo da demanda.

Finalização: Você receberá a resposta em sua caixa de entrada em até 15 minutos, e o RH terá o registro da sua demanda salvo na planilha de controle.

## ⚙️ Configuração do Sistema
Módulo 1: Gmail (Watch Emails) - Filtra apenas e-mails não lidos.

Módulo 2: Google Gemini (Generate content) - Configurado com System Prompt específico para RH.

Módulo 3: Google Sheets (Add a Row) - Mapeia variáveis da IA e do e-mail.

Módulo 4: Gmail (Reply to an Email) - Responde usando o Message ID original para manter a conversa organizada.
