# 🤖 Chatbot de Análise de Dados com LLM via Groq

Este projeto implementa um **chatbot inteligente** capaz de realizar **análises automáticas de dados** a partir de documentos fornecidos pelo usuário. Ele responde perguntas em **linguagem natural** sobre a base de dados carregada e também **gera gráficos personalizados** com base nas solicitações.

---

## 🎯 Objetivo

A proposta do projeto é **democratizar o acesso à análise de dados**, permitindo que qualquer pessoa – mesmo sem conhecimento técnico – consiga:

- Fazer perguntas sobre uma base de dados estruturada (CSV, Excel etc.).
- Gerar gráficos automaticamente a partir dessas perguntas.
- Obter insights rápidos sem escrever código ou fórmulas.

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia       | Finalidade                                       |
|------------------|--------------------------------------------------|
| **Python 3.10+** | Linguagem base do projeto                        |
| **Groq API**     | Execução de modelos LLM de alta performance      |
| **LlamaIndex**   | Indexação e consulta contextual sobre os dados   |
| **Gradio**       | Interface gráfica acessível via navegador        |
| **Pandas**       | Manipulação e análise de dados                   |
| **Matplotlib / Seaborn / Plotly** | Visualização de dados           |

---

## 🚫 O que não foi utilizado

- **Sem agentes (LangChain, AutoGPT etc.)**: a lógica é direta e controlada.
- **Sem treinamento adicional ou fine-tuning**: apenas inferência em tempo real.
- **Sem envio de dados a terceiros não autorizados**: execução segura e isolada.

---

## 🧠 Funcionalidades

✅ Leitura de arquivos `.csv` e `.xlsx`  
✅ Análise automática da estrutura dos dados  
✅ Perguntas em linguagem natural como:
- "Quantas linhas existem no arquivo?"
- "Qual a média da coluna faturamento por mês?"
- "Me mostre um gráfico de pizza com os clientes por categoria."

✅ Geração dinâmica de gráficos  
✅ Interface amigável via Gradio  

---

## 🖼️ Interface

A interface web permite:

1. Upload do arquivo de dados
2. Entrada de perguntas em linguagem natural
3. Exibição de respostas e gráficos na mesma tela

