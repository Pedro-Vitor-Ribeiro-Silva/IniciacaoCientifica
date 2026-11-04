# Tarefa 09 — Publicação no CONTECSI (resumo expandido)

**Projeto de Iniciação Científica:** Arquitetura Orientada a Eventos (*Event-Driven Architecture* — EDA) em nuvem AWS
**Autor:** Pedro Vitor Ribeiro Silva
**Orientador:** Prof. Deivison Shindi Takatu
**Última atualização:** 03/11/2026

> **Objetivo desta atividade:** adaptar o projeto de IC para um trabalho do CONTECSI, usando o template da modalidade escolhida, e registrar o andamento da submissão.

---

## 1. Modalidade

| Campo | Informação |
|-------|------------|
| **Modalidade escolhida** | **REX — Resumo expandido** (trilha de Graduação) |
| **Evento** | 21º CONTECSI — modalidade, prazo e regras a confirmar na chamada oficial |
| **Diretrizes para autores** | https://contecsi.tecsi.org/index.php/contecsi/21CONTECSI/about/submissions#authorGuidelines |
| **Sistema de submissão** | https://contecsi.tecsi.org/index.php/contecsi/21CONTECSI/author/submit |

**Justificativa da escolha do REX (rascunho, a validar com o orientador):**

- A pesquisa está em estágio de **proposta arquitetural com análise qualitativa**. Não houve implementação de protótipo nem medições de desempenho (ver [`../tarefa07-congresso.md`](../tarefa07-congresso.md)), de modo que os resultados são parciais e cabem em um resumo expandido, e não em um artigo completo.
- O autor é aluno de graduação (Tecnólogo em Análise e Desenvolvimento de Sistemas).
- O texto-base já existia em formato de resumo expandido (Tarefa 07) e foi adaptado ao template.

> A tarefa recomenda priorizar o artigo completo (PSE) e aceita o REX apenas com justificativa acadêmica. Confirmar com o orientador se a justificativa acima é suficiente.

---

## 2. Template e exemplos

| Item | Situação |
|------|----------|
| **Template utilizado** | `template_artigo_2024.docx` (modelo do REX / Graduação fornecido na disciplina). O cabeçalho dele indica *1º CONTECSI — Fatec Itapetininga, 2024*. **Pendente:** confirmar com o orientador se é a versão vigente para o 21º CONTECSI. |
| **Exemplos aceitos (20ª edição, trilha 110)** | **Pendente:** registrar aqui os links de pelo menos dois trabalhos aceitos na modalidade REX. |

---

## 3. Manuscrito

| Campo | Informação |
|-------|------------|
| **Título (provisório)** | Arquitetura Orientada a Eventos em Nuvem: uma proposta baseada em serviços AWS para aplicações escaláveis |
| **Título em inglês** | Event-Driven Architecture in the Cloud: an AWS-based proposal for scalable applications |
| **Palavras-chave** | Arquitetura orientada a eventos; Computação em nuvem; Escalabilidade; Microsserviços; *Serverless* |
| **Estágio da pesquisa** | Em desenvolvimento — proposta arquitetural com análise qualitativa; validação experimental prevista como trabalho futuro |
| **Arquivo** | [`manuscrito/resumo-expandido.docx`](manuscrito/resumo-expandido.docx) |
| **Fontes e trabalhos relacionados** | [`referencias/fontes-e-trabalhos-relacionados.md`](referencias/fontes-e-trabalhos-relacionados.md) |

**Contribuição:** proposta de uma arquitetura orientada a eventos em cinco camadas (apresentação, entrada, mensageria, processamento e persistência/observabilidade) sobre serviços gerenciados da AWS, com análise qualitativa de escalabilidade, resiliência e segurança, e discussão das contrapartidas (consistência eventual, idempotência, observabilidade e *vendor lock-in*).

**Adaptação ao template** (a partir do resumo expandido da Tarefa 07):

- Seções reordenadas conforme o template: Introdução (com objetivos ao final), Metodologia, Referencial teórico, Resultados e discussão, Considerações finais e Referências bibliográficas.
- "Revisão de literatura" passou a "Referencial teórico" e "Conclusão" passou a "Considerações finais".
- Resumo e *abstract* em parágrafo único; palavras-chave em ordem alfabética e com inicial maiúscula.
- Bloco de autores no formato do template (nome, ORCID, CPF, instituição e e-mail) e minicurrículo nas notas de rodapé.

---

## 4. Situação

| Campo | Informação |
|-------|------------|
| **Status** | Em preparação — **não submetido** |
| **Data de submissão** | — |
| **Código de confirmação** | — |

**Pendências:**

1. Confirmar com o orientador a versão do template e a modalidade (REX).
2. Registrar os links dos dois exemplos aceitos na 20ª edição (trilha 110).
3. Revisão final com os orientadores (a introdução está com 2.509 caracteres e o limite do template é 2.500).
4. Conferir na chamada oficial se a modalidade está aberta e qual é o prazo.
5. Submeter no sistema do evento e registrar aqui a data e o código de confirmação.

---

## 5. Dados pessoais

A versão deste repositório **omite os CPFs** exigidos pelo template, que são preenchidos apenas na versão enviada ao evento e mantidos fora do GitHub. Os ORCID dos autores e os e-mails institucionais já são públicos.
