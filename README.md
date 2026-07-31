# 🧠 AI Competitive Intelligence Agent

Automação desenvolvida em n8n que monitora concorrentes do mercado de IA conversacional, utiliza IA generativa para gerar briefings executivos e entrega insights diretamente no Telegram com priorização por **Score Estratégico**.

---

## 🎯 Problema
Times de Product Marketing e Go-To-Market (GTM) gastam tempo valioso monitorando manualmente notícias da concorrência, sintetizando informações e transformando fatos soltos em ações estratégicas.

## 🚀 Solução
O workflow automatiza todo o processo em tempo real:
`Google News RSS` ➔ `n8n` ➔ `Google Gemini / OpenAI` ➔ `Classificação & Score GTM` ➔ `Telegram`

---

## 🛠️ Tecnologias Utilizadas
- **n8n Cloud** (Orquestração de workflow)
- **Google Gemini API / OpenAI** (Inteligência Artificial Generativa)
- **Telegram Bot API** (Notificações em tempo real)
- **RSS / Google News** (Monitoramento de fontes)
- **JavaScript** (Tratamento de dados JSON e regras de priorização)

---

## ✨ Funcionalidades
- **Monitoramento automático:** Coleta de notícias e lançamentos de concorrentes.
- **Resumo executivo por IA:** Síntese em poucas frases dos principais acontecimentos.
- **Score Estratégico (1 a 10):** Cálculo do grau de ameaça/relevância competitiva.
- **Alertas visuais:** Badges automáticas no Telegram (🔴 Alta, 🟡 Média, 🟢 Baixa Ameaça).
- **Ações acionáveis:** Recomendações diretas para os times de Produto e Vendas.

---

## 📊 Resultado & Impacto
- **Economia de Tempo:** Redução do trabalho manual de ~30 min/dia para ~1 min.
- **Padronização:** Briefings em formato estruturado prontos para compartilhamento com executivos.
- **Priorização Ativa:** Notificação imediata sobre ameaças de alta severidade ($\ge 8/10$).

---

## 🖼️ Demonstração do Workflow

### Fluxo no n8n:
<img width="1440" height="900" alt="workflow" src="https://github.com/user-attachments/assets/0883627e-b412-4242-942a-8970ed5afc48" />


### Resultado Entregue no Telegram:
<img width="592" height="1280" alt="telegram-result png" src="https://github.com/user-attachments/assets/293078f3-b585-419a-9985-c378b17992db" />



---

## 📹 Vídeo de Demonstração
Confira a demonstração em vídeo no Loom: [Link da Demonstração](demo/loom-link.txt)

---

## 👤 Contexto
Projeto desenvolvido com foco em rotinas reais de **Product Marketing**, **Inteligência de Mercado** e **Go-To-Market (GTM)** para produtos de tecnologia e IA conversacional.
