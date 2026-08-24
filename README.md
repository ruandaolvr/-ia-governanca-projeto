# 🤖 Projeto Integrador de IA e Governança

**Disciplina:** Ética em Inteligência Artificial
**Turma:** 3º Ano B — Ensino Médio Técnico
**Bimestre:** 3º Bimestre

Projeto interdisciplinar que investiga um caso real de viés algorítmico, propõe diretrizes de governança e regulamentação, aplica práticas ágeis de trabalho em equipe (Scrum/Kanban) e demonstra, na prática, uma etapa do trabalho de um cientista de dados.

---

## 👥 Equipe

| Integrante | Papel Scrum | GitHub |
|---|---|---|
| _Nome 1_ | Product Owner | [@usuario1](https://github.com/usuario1) |
| _Nome 2_ | Scrum Master | [@usuario2](https://github.com/usuario2) |
| _Nome 3_ | Dev — Governança | [@usuario3](https://github.com/usuario3) |
| _Nome 4_ | Dev — Dados | [@usuario4](https://github.com/usuario4) |
| _Nome 5_ | Dev — Versionamento | [@usuario5](https://github.com/usuario5) |

## 📂 Estrutura do Repositório

```
.
├── README.md                              # Este arquivo
├── relatorio-impacto-governanca.md        # Parte 1 — Relatório de Impacto e Governança
├── planejamento-agil-kanban.md            # Parte 2 — Planejamento Ágil e Quadro Kanban
├── dados/
│   └── dados_creditos_simulados.csv       # Base de dados simulada (Parte 3)
└── notebooks/
    └── laboratorio_dados_credito.ipynb    # Notebook do laboratório de dados (Parte 3)
```

## 📝 Parte 1 — Relatório de Impacto e Governança
Analisa um caso real de viés em reconhecimento facial (estudo *Gender Shades* e o caso Robert Williams, Detroit-EUA), identifica falhas técnicas e institucionais, discute riscos de exclusão digital e propõe diretrizes de regulamentação.
📄 [Acessar relatório](./relatorio-impacto-governanca.md)

## 📋 Parte 2 — Planejamento Ágil e Quadro Kanban
Define papéis Scrum, backlog de user stories com critérios de aceitação, estimativas via Planning Poker (escala Fibonacci) e limites de WIP.
📄 [Acessar planejamento](./planejamento-agil-kanban.md)
🔗 **Quadro Trello/Miro:** _[colar link do board aqui]_

## 💻 Parte 3 — Laboratório de Dados (Google Colab)
Notebook Python com leitura de CSV simulado (`pandas`), estatísticas descritivas e uma auditoria exploratória simples de viés por região.
📄 [Notebook local](./notebooks/laboratorio_dados_credito.ipynb)
🔗 **Abrir no Google Colab:** _[colar link do notebook publicado aqui]_

## 🚀 Parte 4 — Repositório Técnico (este repositório)
Organização e versionamento do projeto, com histórico de commits comprovando a participação técnica de todos os integrantes.

### Como reproduzir a organização do fluxo de trabalho do grupo

```bash
# 1. Clonar o repositório
git clone https://github.com/usuario-organizador/ia-governanca-projeto.git
cd ia-governanca-projeto

# 2. Criar uma branch por entrega/funcionalidade
git checkout -b feature/relatorio-parte1

# 3. Adicionar e commitar mudanças com mensagens descritivas
git add relatorio-impacto-governanca.md
git commit -m "docs: adiciona relatorio de impacto e governanca (Parte 1)"

# 4. Enviar a branch e abrir um Pull Request para a main
git push origin feature/relatorio-parte1
```

### Convenção de commits utilizada
| Prefixo | Uso |
|---|---|
| `docs:` | Alterações em documentação (relatório, README, planejamento) |
| `feat:` | Novo código/funcionalidade (ex.: notebook, scripts) |
| `data:` | Inclusão/alteração de bases de dados |
| `fix:` | Correção de erros |

> Cada Pull Request deve ser aberto pelo integrante responsável pela tarefa (ver Parte 2) e revisado por, no mínimo, outro membro antes do merge — reproduzindo a coluna **"Em Revisão"** do quadro Kanban.

## 🧭 Como abrir o notebook no Google Colab

1. Acesse [colab.research.google.com](https://colab.research.google.com).
2. `Arquivo` → `Abrir notebook` → aba `GitHub`.
3. Cole a URL deste repositório e selecione `notebooks/laboratorio_dados_credito.ipynb`.
4. Faça upload do arquivo `dados/dados_creditos_simulados.csv` na barra lateral do Colab antes de executar as células.
5. `Arquivo` → `Salvar uma cópia no Drive`, ative o compartilhamento por link e cole aqui na Parte 3 acima.

## 📜 Licença
Projeto de uso exclusivamente pedagógico, desenvolvido para a disciplina de Ética em Inteligência Artificial.

---
<p align="center"><i>Feito com 💙 pela equipe — Projeto Integrador de IA e Governança, 3º Bimestre.</i></p>
