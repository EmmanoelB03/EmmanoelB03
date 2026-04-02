# 👋 Olá, eu sou Emmanoel Barbosa!

🎓 Estudante de Engenharia da Computação na Universidade de Pernambuco (UPE)  
💻 Analista de Automação de Processos na DTIC (UPE)  
📍 Recife, Pernambuco, Brasil  

## 🚀 Sobre Mim
Sou apaixonado por Inteligência Artificial, Machine Learning, Data Science e MLOps. Meu foco atual é desenvolver e aplicar IA generativa e automações robustas para resolver problemas reais, otimizando fluxos de trabalho e transformando dados em soluções práticas.

---

## 🔬 Projetos em Destaque

### 🩺 **Sistema de IA para Apoio Diagnóstico - CISAM/UPE** 
*Projeto de Iniciação Científica financiado pela FACEPE*

Desenvolvimento de um sistema de inteligência artificial para apoio ao pré-diagnóstico em teleconsultas no Hospital CISAM, especializado em Saúde da Mulher e Neonatologia.

**Destaques Técnicos:**
- Implementação local de LLM (MedGemma) com Ollama para garantir privacidade (LGPD)
- Interface web customizada baseada em Open WebUI
- Arquitetura containerizada com Docker para deploy seguro
- Anonimização automática de dados clínicos

**Stack:** Python · Docker · Ollama · SvelteKit · TypeScript · Shell Script

🔗 [Repositório da Interface](https://github.com/compet-cisam/interface)

---

### 📄 **WebScraping — Resoluções UPE (CONSUN/CEPE)**

Automação completa para coleta, download, classificação e publicação das resoluções dos conselhos universitários da Universidade de Pernambuco.

**Destaques Técnicos:**
- Scraping automatizado do site da UPE com Selenium para extração de ementas e links
- Download paralelo de PDFs do Google Drive com ThreadPoolExecutor (4 threads simultâneas)
- Classificação automática de ementas por categoria usando Google Gemini e Ollama (LLaMA 3) local
- Cadastro e publicação automática no sistema interno via Selenium, incluindo upload de PDFs
- Pipeline completo de validação: downloads, envios e integridade dos dados

**Stack:** Python · Selenium · Pandas · Google Gemini · Ollama · ThreadPoolExecutor · python-dotenv

---

### 🎮 **IA Abigail - Stardew Valley**

Integração de IA generativa com Stardew Valley, permitindo que a personagem Abigail responda dinamicamente em tempo real durante o gameplay.

**Destaques Técnicos:**
- Monitoramento em tempo real dos logs do SMAPI (Stardew Valley Mod API)
- Integração com Google Gemini (modelo gemma-3-27b-it) via LangChain
- Sistema de envio de comandos ao jogo através de Tmux
- Respostas contextualizadas baseadas na personalidade do personagem

**Stack:** Python · LangChain · Google Generative AI · Tmux

🔗 [Ver Projeto](https://github.com/EmmanoelB03/llmAndStardewValley)

---

### 📝 **Gerador de BPMN com IA**

Aplicação web que transforma descrições de processos em texto para diagramas BPMN 2.0 profissionais usando inteligência artificial.

**Destaques Técnicos:**
- Conversão automática de texto para diagramas BPMN válidos
- Interface interativa desenvolvida com Streamlit
- Integração com Google Gemini via LangChain para geração inteligente
- Exportação em múltiplos formatos (.bpmn, .json, .svg)
- Suporte a elementos complexos: decisões, eventos, tarefas e gateways

**Stack:** Python · REST API · Streamlit · LangChain · Google Gemini · bpmn-js

🔗 [Ver Projeto](https://github.com/EmmanoelB03/text_to_bpmn)

---

### 🚴 **FedCycle - Aprendizado Federado em Redes Heterogêneas**
*Projeto de Pesquisa Científica - Universidade de Pernambuco (UPE)*

Arquitetura cíclica de Federated Learning baseada em destilação de conhecimento bidirecional, inspirada no algoritmo FedBKD. O projeto visa resolver a queda de desempenho em cenários com restrições severas de hardware (TinyML/ESP32) no processamento de dados locais descentralizados (Não-IID).

**Destaques Técnicos:**
- **Analogia Coevolução:** Um servidor de alta capacidade (Professor) extrai características gerais e "ensina" o microcontrolador (Aluno). O ESP32 treina com sua vivência local e "ensina" de volta o servidor, mitigando o esquecimento catastrófico do modelo global.
- **Privacidade com GANs (Data-Free):** Implementação de uma Rede Generativa Adversarial no servidor para sintetizar feature maps (vetores de 2048 atributos), permitindo destilação de conhecimento sem tráfego de dados reais.
- **Destilação Bidirecional (KD):** Transferência de aprendizado Global → Local e Local → Global alinhando distribuições matemáticas através da Divergência Kullback-Leibler (KL).
- **On-Device Training e TinyML:** Separação da arquitetura via ONNX com camada de representação congelada no cliente, permitindo retropropagação manual apenas na camada de classificação otimizada para a SRAM do ESP32 no simulador Wokwi.

**Stack:** Python · PyTorch · C++ · TensorFlow Lite Micro · ONNX · IoT (ESP32/Wokwi)

🔗 [Ver Projeto](https://github.com/EmmanoelB03/FedCycle)

---

## 🌱 Atualmente Focado Em

- 🧠 Aprofundamento em **Deep Learning** e **NLP** (Natural Language Processing)
- ⚙️ Explorando **MLOps** e práticas de deploy de modelos em produção
- 🏥 Aplicações de IA na área da saúde com foco em privacidade de dados
- 🤝 Buscando colaborações em projetos **open-source** e desafios de Data Science

---

## 🛠️ Stack Tecnológica

### Linguagens de Programação
<div>
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
</div>

### Desenvolvimento Web
<div>
  <img src="https://img.shields.io/badge/-SvelteKit-FF3E00?style=flat-square&logo=svelte&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
</div>

### Data Science & Machine Learning
<div>
  <img src="https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Scikit%20Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Matplotlib-11557c?style=flat-square&logo=python&logoColor=white"/>
</div>

### Banco de Dados
<div>
  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</div>

### Automação
<div>
  <img src="https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Apps%20Script-4285F4?style=flat-square&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white"/>
</div>

### DevOps & Ferramentas
<div>
  <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>
</div>

---

## 📫 Vamos Conectar!

Estou sempre aberto a discussões sobre IA, Data Science, projetos colaborativos e novas oportunidades!

[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emmanoel.barbosa03@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanoel-barbosa-599260270/)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EmmanoelB03)

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=EmmanoelB03&color=blueviolet&style=flat-square&label=Visualizações+do+Perfil" alt="Profile views" />
</div>

