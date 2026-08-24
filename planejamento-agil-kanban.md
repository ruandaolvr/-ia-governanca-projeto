# Planejamento Ágil e Quadro Kanban

**Projeto:** Projeto Integrador de IA e Governança
**Metodologia:** Scrum + Kanban (fluxo visual com limites de WIP)
**Ferramenta sugerida:** Trello ou Miro (link do quadro: _[colar aqui o link público do board]_)

> ⚠️ Este documento é o roteiro para montar o quadro no Trello/Miro. Copie as colunas e os cards descritos abaixo diretamente para a ferramenta escolhida e cole o link do board nesta seção.

---

## 1. Papéis da Equipe Scrum

| Papel | Integrante | Principais responsabilidades |
|---|---|---|
| **Product Owner (PO)** | _[nome]_ | Prioriza o backlog, define critérios de aceitação, garante que as entregas atendam ao enunciado do trabalho. |
| **Scrum Master** | _[nome]_ | Remove impedimentos, garante que o time respeita os limites de WIP e os prazos, conduz as reuniões rápidas (dailies). |
| **Dev 1 — Governança/Redação** | _[nome]_ | Responsável técnico pela Parte 1 (relatório). |
| **Dev 2 — Dados/Python** | _[nome]_ | Responsável técnico pela Parte 3 (Colab). |
| **Dev 3 — Versionamento/GitHub** | _[nome]_ | Responsável técnico pela Parte 4 (repositório). |

*(Em grupos de 4, uma pessoa acumula dois papéis, ex.: Scrum Master também atua como Dev.)*

## 2. Colunas do Quadro Kanban e Limites de WIP

| Coluna | Limite de WIP | Descrição |
|---|---|---|
| **Backlog** | sem limite | Todas as tarefas identificadas, ainda não priorizadas. |
| **A Fazer (Sprint atual)** | 5 | Tarefas priorizadas pelo PO para o período atual. |
| **Em Andamento** | **3** | Máximo de 3 cards sendo trabalhados ao mesmo tempo — evita que o time comece muita coisa e termine pouco. |
| **Em Revisão** | 2 | Card revisado por outro integrante antes de ser considerado pronto (peer review). |
| **Concluído** | sem limite | Entregue e validado pelo PO. |

**Regra de WIP:** nenhum integrante pode puxar um novo card para "Em Andamento" se a coluna já estiver no limite — o time deve primeiro ajudar a destravar/finalizar o que já está em progresso. Isso evita desperdício (trabalho parcial acumulado, retrabalho, perda de contexto).

## 3. Backlog de User Stories (com critérios de aceitação)

Formato: `Como <papel>, quero <ação>, para <benefício>`

### US-01 — Escolha do caso real
**Como** Product Owner, **quero** que o time escolha e valide um caso real de viés em IA, **para** ter uma base sólida para o relatório.
- **Critérios de aceitação:**
  - [ ] Caso é real, documentado e possui fontes confiáveis (mín. 3 fontes).
  - [ ] Caso está relacionado a viés/exclusão (reconhecimento facial, crédito, etc.).
- **Estimativa (Fibonacci):** 3

### US-02 — Redação do relatório de impacto
**Como** Dev de Governança, **quero** redigir o relatório em Markdown, **para** cumprir os critérios da Parte 1.
- **Critérios de aceitação:**
  - [ ] Contém: introdução, caso, falhas identificadas, riscos de exclusão, propostas de regulamentação, conclusão e referências.
  - [ ] Arquivo salvo em formato `.md`.
- **Estimativa (Fibonacci):** 5

### US-03 — Montagem do quadro Kanban
**Como** Scrum Master, **quero** montar o quadro no Trello/Miro com colunas e WIP, **para** organizar visualmente o fluxo do time.
- **Critérios de aceitação:**
  - [ ] Colunas criadas conforme a seção 2 deste documento.
  - [ ] Limites de WIP configurados na ferramenta.
  - [ ] Board com link de acesso compartilhável.
- **Estimativa (Fibonacci):** 2

### US-04 — Planning Poker das tarefas
**Como** time, **quero** estimar o esforço de cada card usando a escala Fibonacci, **para** planejar a sprint com realismo.
- **Critérios de aceitação:**
  - [ ] Cada card do backlog tem uma estimativa (1, 2, 3, 5, 8, 13...) registrada.
  - [ ] Estimativas foram discutidas e acordadas por todo o time (não definidas por uma única pessoa).
- **Estimativa (Fibonacci):** 1

### US-05 — Notebook de análise de dados
**Como** Dev de Dados, **quero** criar um notebook no Google Colab que leia um CSV simulado, **para** demonstrar a etapa de exploração de dados de um cientista de dados.
- **Critérios de aceitação:**
  - [ ] Notebook importa o CSV com `pandas`.
  - [ ] Código comentado explicando cada etapa.
  - [ ] Notebook compartilhado com link de visualização pública.
- **Estimativa (Fibonacci):** 5

### US-06 — Estrutura e versionamento no GitHub
**Como** Dev de Versionamento, **quero** criar o repositório com README formal e histórico de commits de todos os membros, **para** comprovar a colaboração técnica do grupo.
- **Critérios de aceitação:**
  - [ ] Repositório público com README.md completo.
  - [ ] Pelo menos 1 branch além da `main` (ex.: `feature/relatorio`) com merge via Pull Request.
  - [ ] Commits de todos os integrantes, com mensagens descritivas.
- **Estimativa (Fibonacci):** 8

### US-07 — Revisão final e entrega
**Como** Product Owner, **quero** revisar todas as partes antes da entrega, **para** garantir que os critérios do professor estão atendidos.
- **Critérios de aceitação:**
  - [ ] Todos os 4 itens do enunciado revisados e completos.
  - [ ] Links (Colab, Trello/Miro, GitHub) testados em aba anônima.
- **Estimativa (Fibonacci):** 3

## 4. Planning Poker — Registro de Estimativas

| Card | PO | Scrum Master | Dev 1 | Dev 2 | Dev 3 | Estimativa final |
|---|---|---|---|---|---|---|
| US-01 | 3 | 3 | 2 | 3 | 3 | **3** |
| US-02 | 5 | 5 | 5 | 3 | 5 | **5** |
| US-03 | 2 | 2 | 1 | 2 | 2 | **2** |
| US-04 | 1 | 1 | 1 | 1 | 1 | **1** |
| US-05 | 5 | 5 | 3 | 5 | 5 | **5** |
| US-06 | 8 | 8 | 5 | 8 | 8 | **8** |
| US-07 | 3 | 3 | 3 | 2 | 3 | **3** |

*(Preencham com os números que o grupo realmente combinar na dinâmica de Planning Poker — os valores acima são um exemplo de referência.)*

## 5. Passo a passo para montar no Trello

1. Criar um quadro novo → nomear "IA e Governança — Projeto Integrador".
2. Criar as 5 listas (colunas) da seção 2.
3. Ativar o **Power-Up "Card Limits"** em cada lista para aplicar o WIP (no Trello: clique nos "..." da lista → *Definir limite do WIP*).
4. Criar um card para cada User Story (US-01 a US-07), com descrição = critérios de aceitação (usar checklist do Trello) e etiqueta = estimativa Fibonacci.
5. Adicionar todos os integrantes como membros do quadro, atribuindo responsáveis a cada card.
6. Mover os cards entre colunas ao longo do bimestre e tirar um print do quadro final para anexar à entrega.

---
_Documento produzido para fins pedagógicos — Parte 2 do Projeto Integrador de IA e Governança._
