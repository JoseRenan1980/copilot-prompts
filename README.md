# IA Mentor de Carreira — Projeto do Bootcamp DIO

Este repositório contém a implementação completa do desafio **“IA Mentor de Carreira: Descubra Seu Futuro em Tech”**, realizado no Bootcamp da DIO.  
O projeto utiliza dois agentes (Agent 1 e Agent 2) para conduzir uma entrevista estruturada e gerar um plano de carreira personalizado.

---

## 📌 Estrutura do Projeto

O repositório contém:

- **AGENT_1_RESULTADO.md** → Registro completo da entrevista com o Agent 1  
- **AGENT_2_PLANO.md** → Plano de carreira gerado pelo Agent 2  
- **ENTREGA.md** → Documento final de entrega para a DIO  
- **Este README.md** → Explicação geral do projeto  

---

## 🤖 Como funciona o sistema de agentes

O projeto utiliza **dois agentes independentes**, cada um com uma função específica:

---

### 🟦 Agent 1 — Entrevistador de Carreira

Responsável por:

- Fazer **7 perguntas obrigatórias**, uma por vez  
- Coletar informações sobre perfil, interesses e objetivos  
- Gerar **3 carreiras ranqueadas** com justificativas  
- Perguntar qual carreira o usuário escolhe  
- Gerar o **bloco de handoff** para o Agent 2  

O resultado completo está em:  
📄 `AGENT_1_RESULTADO.md`

---

### 🟩 Agent 2 — Planejador de Carreira

Responsável por:

- Receber o handoff do Agent 1  
- Criar um **plano de carreira completo**, incluindo:  
  - Visão do dia a dia  
  - Mapa de skills  
  - Roadmap de 90 dias  
  - Projeto de portfólio  
  - Roteiro de entrevistas  
  - Trilha DIO recomendada  

O plano completo está em:  
📄 `AGENT_2_PLANO.md`

---

## 🧪 Como reproduzir o fluxo

### 1️⃣ Passo 1 — Criar um chat com o Agent 1
- Abra um novo chat no Copilot  
- Cole o conteúdo do arquivo **AGENT 1 - Entrevistador de Carreira** do repositório da DIO  
- Responda às 7 perguntas  
- Escolha uma das 3 carreiras sugeridas  
- Copie o **bloco de handoff** gerado ao final  

---

### 2️⃣ Passo 2 — Criar um chat com o Agent 2
- Abra outro chat no Copilot  
- Cole o conteúdo do arquivo **AGENT 2 - Planejador de Carreiras**  
- Em seguida, cole o **bloco de handoff** do Agent 1  
- O Agent 2 irá gerar automaticamente o plano completo  

---

### 3️⃣ Passo 3 — Registrar os resultados
- Copie o conteúdo final do Agent 1 → salve em `AGENT_1_RESULTADO.md`  
- Copie o conteúdo final do Agent 2 → salve em `AGENT_2_PLANO.md`  
- Preencha o arquivo `ENTREGA.md` com prints e links dos chats  

---

## 📂 Estrutura de pastas sugerida

