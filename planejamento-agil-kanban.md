# Planejamento Ágil e Quadro Kanban

**Projeto:** Projeto Integrador de IA e Governança
**Metodologia:** Scrum + Kanban
**Ferramenta:** Trello

**Link do quadro:** COLE_AQUI_O_LINK_DO_TRELLO

> Este documento apresenta o planejamento ágil do projeto, a organização da equipe, as User Stories, os critérios de aceitação, as estimativas e as regras utilizadas no quadro Kanban.

---

## 1. Papéis da Equipe Scrum

Como o projeto possui duas integrantes, algumas responsabilidades são acumuladas.

| Integrante             | Papel Scrum         | Principais responsabilidades                                                                                                                                           |
| ---------------------- | ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ruanda N. Oliveira** | Product Owner / Dev | Priorizar o backlog, definir critérios de aceitação, organizar o relatório, acompanhar as entregas e contribuir com o desenvolvimento e versionamento.                 |
| **Giovanna Vitória**   | Scrum Master / Dev  | Organizar o fluxo do Kanban, acompanhar os limites de WIP, auxiliar na organização das tarefas, desenvolver o notebook de dados e contribuir com a revisão do projeto. |

### Responsabilidades compartilhadas

As duas integrantes participam da revisão das entregas, das decisões de planejamento, das estimativas das tarefas e da validação final do projeto.

---

## 2. Colunas do Quadro Kanban e Limites de WIP

| Coluna                     | Limite de WIP | Descrição                                                                                                               |
| -------------------------- | ------------: | ----------------------------------------------------------------------------------------------------------------------- |
| **Backlog**                |    Sem limite | Reúne todas as tarefas identificadas para o projeto.                                                                    |
| **A Fazer — Sprint Atual** |             5 | Tarefas priorizadas para serem realizadas na sprint atual.                                                              |
| **Em Andamento**           |             2 | No máximo duas tarefas podem estar sendo realizadas simultaneamente, considerando que a equipe possui duas integrantes. |
| **Em Revisão**             |             2 | Tarefas concluídas pelo responsável e aguardando revisão da outra integrante.                                           |
| **Concluído**              |    Sem limite | Tarefas revisadas, validadas e finalizadas.                                                                             |

### Regra de WIP

A equipe não deve iniciar uma nova tarefa quando a coluna já estiver no limite definido. Primeiro, deve finalizar ou ajudar a destravar uma tarefa que já esteja em andamento.

O limite reduz o excesso de tarefas simultâneas e ajuda a equipe a manter o foco nas atividades prioritárias.

---

## 3. Backlog de User Stories

As User Stories seguem o formato:

> **Como <papel>, quero <ação>, para <benefício>.**

---

### US-01 — Escolha do caso real

**Como Product Owner, quero escolher e validar um caso real de viés em IA, para ter uma base sólida para o relatório.**

**Responsável:** Ruanda N. Oliveira

**Critérios de aceitação:**

* [ ] O caso é real e documentado.
* [ ] O caso possui pelo menos 3 fontes confiáveis.
* [ ] O caso está relacionado a viés, discriminação ou exclusão em sistemas de IA.

**Estimativa Fibonacci:** 3 pontos

---

### US-02 — Redação do relatório de impacto

**Como integrante responsável pela governança, quero redigir o relatório em Markdown, para cumprir os critérios da Parte 1 do projeto.**

**Responsável:** Ruanda N. Oliveira

**Critérios de aceitação:**

* [ ] O relatório contém introdução.
* [ ] O caso analisado está apresentado.
* [ ] As falhas identificadas estão descritas.
* [ ] Os riscos de exclusão estão apresentados.
* [ ] Existem propostas relacionadas à governança e regulamentação.
* [ ] O relatório possui conclusão.
* [ ] As referências utilizadas estão registradas.
* [ ] O arquivo está salvo em formato `.md`.

**Estimativa Fibonacci:** 5 pontos

---

### US-03 — Montagem do quadro Kanban

**Como Scrum Master, quero montar o quadro no Trello com colunas e limites de WIP, para organizar visualmente o fluxo de trabalho da equipe.**

**Responsável:** Giovanna Vitória

**Critérios de aceitação:**

* [ ] As cinco colunas do Kanban foram criadas.
* [ ] Os limites de WIP foram definidos.
* [ ] Os sete cards das User Stories foram criados.
* [ ] O quadro possui link compartilhável.
* [ ] A organização do quadro corresponde ao planejamento deste documento.

**Estimativa Fibonacci:** 2 pontos

---

### US-04 — Planning Poker das tarefas

**Como equipe, queremos estimar o esforço de cada tarefa utilizando a sequência de Fibonacci, para planejar as atividades de forma realista.**

**Responsáveis:** Ruanda N. Oliveira e Giovanna Vitória

**Critérios de aceitação:**

* [ ] Cada User Story possui uma estimativa.
* [ ] As estimativas utilizam a sequência Fibonacci.
* [ ] As estimativas são discutidas e validadas pelas duas integrantes.
* [ ] Os valores finais são registrados nos cards do Trello.

**Estimativa Fibonacci:** 1 ponto

---

### US-05 — Notebook de análise de dados

**Como integrante responsável pelos dados, quero criar e executar um notebook no Google Colab utilizando um CSV simulado, para demonstrar uma etapa de exploração e auditoria de dados.**

**Responsável:** Giovanna Vitória

**Critérios de aceitação:**

* [ ] O notebook importa o arquivo CSV utilizando `pandas`.
* [ ] O notebook apresenta uma inspeção geral da base.
* [ ] São apresentadas estatísticas descritivas.
* [ ] É realizada uma análise de aprovação por região.
* [ ] É realizada uma comparação da renda média por decisão.
* [ ] O código possui comentários explicativos.
* [ ] O notebook possui link público para visualização.

**Estimativa Fibonacci:** 5 pontos

---

### US-06 — Estrutura e versionamento no GitHub

**Como responsável pelo versionamento, quero organizar o repositório no GitHub com README e histórico de alterações, para documentar o desenvolvimento do projeto.**

**Responsável:** Ruanda N. Oliveira

**Critérios de aceitação:**

* [ ] O repositório é público.
* [ ] O `README.md` apresenta o projeto e sua estrutura.
* [ ] Os principais arquivos do projeto estão organizados em pastas.
* [ ] Existe histórico de commits descritivos.
* [ ] As duas integrantes participam do desenvolvimento e/ou documentação do projeto.
* [ ] Caso exigido pelo professor, é criada uma branch adicional à `main` e realizado um Pull Request.

**Estimativa Fibonacci:** 8 pontos

---

### US-07 — Revisão final e entrega

**Como equipe, queremos revisar todas as partes antes da entrega, para garantir que os critérios do projeto estejam atendidos.**

**Responsáveis:** Ruanda N. Oliveira e Giovanna Vitória

**Critérios de aceitação:**

* [ ] As partes do projeto foram revisadas.
* [ ] Os arquivos estão organizados no GitHub.
* [ ] O notebook está funcionando.
* [ ] O link do Google Colab foi testado.
* [ ] O link do Trello foi testado.
* [ ] O link do GitHub foi testado.
* [ ] Os documentos não possuem campos de modelo ou informações de exemplo.
* [ ] O projeto está pronto para entrega.

**Estimativa Fibonacci:** 3 pontos

---

## 4. Planning Poker — Registro das Estimativas

A equipe utiliza a sequência de Fibonacci para estimar o esforço relativo das User Stories:

**1, 2, 3, 5, 8, 13...**

| Card  | Ruanda | Giovanna | Estimativa final |
| ----- | -----: | -------: | ---------------: |
| US-01 |      3 |        3 |                3 |
| US-02 |      5 |        5 |                5 |
| US-03 |      2 |        2 |                2 |
| US-04 |      1 |        1 |                1 |
| US-05 |      5 |        5 |                5 |
| US-06 |      8 |        8 |                8 |
| US-07 |      3 |        3 |                3 |

### Observação

Os valores acima representam as estimativas finais utilizadas para organizar os cards do Trello. As duas integrantes devem revisar e confirmar os valores durante a atividade de Planning Poker.

---

## 5. Organização dos Cards no Trello

Os cards devem ser distribuídos inicialmente na coluna **Backlog**.

### Backlog

* US-01 — Escolha do caso real
* US-02 — Redação do relatório de impacto
* US-03 — Montagem do quadro Kanban
* US-04 — Planning Poker das tarefas
* US-05 — Notebook de análise de dados
* US-06 — Estrutura e versionamento no GitHub
* US-07 — Revisão final e entrega

Conforme as atividades forem realizadas, os cards devem avançar pelo fluxo:

**Backlog → A Fazer — Sprint Atual → Em Andamento → Em Revisão → Concluído**

---

## 6. Passo a passo para utilização do Trello

1. Criar o quadro **"IA e Governança — Projeto Integrador"**.
2. Criar as cinco listas:

   * Backlog
   * A Fazer — Sprint Atual
   * Em Andamento — Máx. 2
   * Em Revisão — Máx. 2
   * Concluído
3. Definir o limite de cinco cards para a lista **A Fazer — Sprint Atual**, quando a ferramenta permitir.
4. Manter no máximo dois cards em **Em Andamento**.
5. Manter no máximo dois cards em **Em Revisão**.
6. Criar os sete cards correspondentes às User Stories.
7. Adicionar os critérios de aceitação como checklists.
8. Registrar a estimativa Fibonacci em cada card.
9. Adicionar Ruanda e Giovanna como integrantes do quadro.
10. Atribuir cada card à responsável indicada neste documento.
11. Mover os cards entre as colunas conforme o andamento das atividades.
12. Ao finalizar o projeto, revisar os cards e mover para **Concluído** somente as tarefas realmente finalizadas.

---

## 7. Integração com o GitHub e Google Colab

O projeto utiliza o GitHub como repositório principal para armazenamento e versionamento dos arquivos.

A estrutura do projeto inclui:

```text
-ia-governanca-projeto/
│
├── README.md
├── relatorio-impacto-governanca.md
├── planejamento-agil-kanban.md
│
├── dados/
│   └── dados_creditos_simulados.csv
│
└── notebooks/
    └── laboratorio_dados_credito.ipynb
```

O notebook de análise de dados também deve estar disponível no Google Colab por meio de um link público.

**Link do Google Colab:** COLE_AQUI_O_LINK_DO_COLAB

**Link do Trello:** COLE_AQUI_O_LINK_DO_TRELLO

---

## 8. Definition of Done — Definição de Pronto

Uma tarefa será considerada concluída quando:

* [ ] A atividade descrita no card tiver sido realizada.
* [ ] Os critérios de aceitação tiverem sido atendidos.
* [ ] O material produzido estiver salvo no local correto.
* [ ] A outra integrante tiver realizado a revisão quando aplicável.
* [ ] Não houver pendências relacionadas à tarefa.
* [ ] O card puder ser movido para a coluna **Concluído**.

---

## 9. Objetivo do Planejamento

O planejamento utiliza Scrum e Kanban para organizar o desenvolvimento do Projeto Integrador de IA e Governança.

A combinação das duas abordagens permite visualizar as tarefas, distribuir responsabilidades, limitar o trabalho simultâneo, acompanhar o progresso e revisar as entregas antes da conclusão.

O quadro Kanban e o histórico do GitHub também servem como registros do processo de desenvolvimento realizado pela equipe.

---

**Documento produzido para fins pedagógicos — Parte 2 do Projeto Integrador de IA e Governança.**
