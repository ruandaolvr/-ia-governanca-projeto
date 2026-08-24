# Relatório de Impacto e Governança em Inteligência Artificial

**Disciplina:** Ética em Inteligência Artificial
**Turma:** 3º Ano B — Ensino Médio Técnico
**Bimestre:** 3º Bimestre
**Equipe:** _[Nome dos integrantes]_
**Papéis Scrum:** _[Product Owner / Scrum Master / Devs — ver Parte 2]_

---

## 1. Introdução

Sistemas de Inteligência Artificial (IA) já tomam ou influenciam decisões que afetam diretamente a vida das pessoas: quem é preso, quem recebe crédito, quem é entrevistado para uma vaga. Quando esses sistemas são treinados com dados desbalanceados ou implantados sem supervisão adequada, eles podem reproduzir e até amplificar desigualdades históricas. Este relatório analisa um caso real de viés algorítmico em **sistemas de reconhecimento facial**, identifica falhas técnicas e institucionais, discute riscos de exclusão digital e propõe diretrizes de regulamentação.

## 2. O Caso Escolhido: Reconhecimento Facial e Prisões Injustas nos EUA

### 2.1 O estudo Gender Shades (2018)

Em 2018, as pesquisadoras Joy Buolamwini (MIT Media Lab) e Timnit Gebru publicaram o estudo **"Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification"**, no qual avaliaram três sistemas comerciais de reconhecimento facial amplamente usados (IBM, Microsoft e Face++). Os resultados mostraram uma disparidade gritante de desempenho:

- Erro inferior a **1%** na classificação de homens de pele clara;
- Erro de até **34,7%** na classificação de mulheres de pele escura.

A causa raiz identificada pelas pesquisadoras foi o **desbalanceamento das bases de dados de treinamento**, compostas majoritariamente por rostos de homens brancos, o que fez os modelos aprenderem padrões pouco representativos da diversidade real da população.

### 2.2 Do laboratório para a rua: o caso Robert Williams (Detroit, EUA)

Em janeiro de 2020, Robert Williams, homem negro morador de Farmington Hills (Michigan), foi preso na frente da própria casa, de sua esposa e de suas duas filhas pequenas, sob acusação de furto de relógios em uma loja de Detroit. A prisão foi baseada quase exclusivamente em um resultado de reconhecimento facial aplicado a imagens de câmeras de segurança — resultado que estava **errado**: Williams não era a pessoa do vídeo e não estava perto do local no momento do crime. Ele passou cerca de 30 horas detido em uma cela superlotada.

Em 2021, a ACLU (American Civil Liberties Union) entrou com uma ação judicial contra o Departamento de Polícia de Detroit, alegando violação de direitos constitucionais. O processo revelou falhas sistêmicas no uso da tecnologia e na formação dos investigadores. Em 2024, um acordo histórico obrigou o departamento a adotar as políticas mais restritivas do país para o uso da tecnologia, incluindo a proibição de basear pedidos de prisão exclusivamente em resultados de reconhecimento facial. O caso de Williams foi o primeiro tornado público, mas outras pessoas — todas negras — também foram presas injustamente pelo mesmo tipo de erro.

## 3. Falhas Identificadas

| Categoria | Falha observada |
|---|---|
| **Dados de treinamento** | Bases de imagens desbalanceadas, com sub-representação de pessoas negras e mulheres, gerando taxas de erro muito mais altas para esses grupos. |
| **Validação e testes** | Sistemas foram implantados em contextos de alto risco (policiamento) sem auditoria independente prévia de desempenho por grupo demográfico. |
| **Processo decisório humano** | Policiais trataram o resultado do algoritmo como prova definitiva ("bala de prata"), em vez de uma pista investigativa a ser corroborada por outras evidências. |
| **Transparência** | Pessoas afetadas nem sempre foram informadas, no momento da abordagem, de que a suspeita derivava de reconhecimento facial. |
| **Ausência de regulamentação prévia** | Não havia, à época, legislação federal específica limitando o uso da tecnologia por corporações policiais nos EUA. |

## 4. Riscos de Exclusão Digital e Social

- **Discriminação algorítmica racial e de gênero:** grupos já historicamente marginalizados (pessoas negras, mulheres, pessoas trans) são desproporcionalmente mal identificados, sofrendo mais falsos positivos.
- **Criminalização indevida:** erros de identificação podem levar a prisões, antecedentes criminais indevidos e danos psicológicos e financeiros duradouros.
- **Efeito inibidor (chilling effect):** o medo de vigilância e identificação injusta pode afastar pessoas de espaços públicos, protestos e serviços.
- **Assimetria de poder:** cidadãos comuns não têm acesso aos algoritmos nem meios técnicos para contestar uma decisão automatizada, ampliando a distância entre quem desenvolve/usa a tecnologia e quem é afetado por ela.
- **Naturalização do erro:** decisões tomadas "pelo sistema" tendem a ser vistas como neutras e objetivas, dificultando a responsabilização humana e institucional.

## 5. Propostas de Regulamentação

1. **Auditoria obrigatória e contínua** de sistemas de IA de alto risco, com métricas de erro divulgadas por subgrupo demográfico (raça, gênero, idade) antes e depois da implantação.
2. **Proibição de decisão automatizada isolada** em contextos de alto impacto (prisão, crédito, emprego): resultado de IA deve ser sempre uma pista, nunca prova única, exigindo corroboração humana e outras evidências.
3. **Transparência e explicabilidade:** pessoas afetadas por uma decisão apoiada em IA têm direito de saber que um algoritmo foi usado e de solicitar revisão humana (alinhado ao art. 20 da LGPD, no contexto brasileiro).
4. **Certificação prévia** para uso de reconhecimento facial em segurança pública, com testes de desempenho equitativo como pré-requisito para licenciamento.
5. **Canal de contestação e reparação** rápido e acessível para quem for prejudicado por um erro algorítmico, incluindo responsabilização civil da instituição usuária.
6. **Capacitação de agentes públicos** sobre os limites técnicos da tecnologia, para evitar o uso do resultado da IA como verdade absoluta.
7. **Governança participativa:** inclusão de representantes dos grupos historicamente mais afetados na definição de políticas de uso da tecnologia.

## 6. Conclusão

O caso do reconhecimento facial mostra que viés em IA não é um problema apenas técnico, mas também **institucional e social**: nasce em bases de dados desbalanceadas, é amplificado pela falta de auditoria e se torna dano real quando decisões automatizadas ganham autoridade que não deveriam ter sozinhas. Regulamentação, transparência e supervisão humana qualificada são condições mínimas para que a IA amplie oportunidades em vez de aprofundar desigualdades.

## 7. Referências

- BUOLAMWINI, Joy; GEBRU, Timnit. *Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification*. Conference on Fairness, Accountability and Transparency (FAT), 2018.
- ACLU OF MICHIGAN. *Facial Recognition*. Disponível em: https://www.aclumich.org/cases/facial-recognition/
- ACLU. *Williams v. City of Detroit*. Disponível em: https://www.aclu.org/cases/williams-v-city-of-detroit-face-recognition-false-arrest
- ACLU. *More than a Dozen Wrongful Arrests Due to Police Reliance on Facial Recognition Technology*. Disponível em: https://www.aclu.org/news/privacy-technology/more-than-a-dozen-wrongful-arrests-due-to-police-reliance-on-facial-recognition-technology
- MICHIGAN PUBLIC. *"It didn't make sense at all": Wrongful facial recognition arrest in Detroit leads to landmark settlement*, 2024.
- LEI GERAL DE PROTEÇÃO DE DADOS (LGPD), Lei nº 13.709/2018, art. 20 (revisão de decisões automatizadas).

---
_Documento produzido para fins pedagógicos — Parte 1 do Projeto Integrador de IA e Governança._
