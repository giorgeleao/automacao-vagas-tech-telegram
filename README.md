# 🤖 Automação de Alerta de Vagas Tech via Telegram

Este repositório contém o blueprint (cenário) do Make.com desenvolvido para buscar, filtrar e formatar oportunidades de trabalho e estágio em TI, IA e Dados, enviando notificações automáticas no Telegram.

## 📌 Funcionalidades
- **Busca Autônoma:** Varredura na web via SerpApi por vagas recentes em plataformas como LinkedIn, Gupy, CIEE, Nube e Indeed.
- **Filtro Inteligente com IA:** Processamento e curadoria via Google Gemini AI para extrair vagas e aplicar filtros de localização (DF, Entorno e Home Office).
- **Notificação Direta:** Envio de relatórios formatados em HTML com links diretos de inscrição via Telegram Bot.

## 🛠️ Tecnologias Utilizadas
- **Make (Integromat)**
- **SerpApi (Google Search Engine)**
- **Google Gemini AI API**
- **Telegram Bot API**

## 🚀 Como Importar o Cenário no Make
1. Baixe o arquivo `.json` deste repositório.
2. No Make.com, crie um novo cenário.
3. No painel inferior de controles, clique em `...` (More) e selecione **Import Blueprint**.
4. Selecione o arquivo `.json` baixado.
5. Reconfigure as conexões do SerpApi, Google Gemini AI e Telegram Bot com as suas chaves de API.
