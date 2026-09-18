# Tarefa 07 — Submissão de Trabalho em Evento Científico

**Projeto de Iniciação Científica:** Arquitetura Orientada a Eventos (*Event-Driven Architecture* — EDA) em nuvem AWS
**Autor:** Pedro Vitor Ribeiro Silva
**Orientador:** Prof. Deivison Shindi Takatu
**Última atualização:** 18/09/2026

> **Objetivo desta atividade:** produzir um resumo expandido a partir do projeto de IC e submetê-lo a um evento científico real, vivenciando o ciclo *pesquisar → escrever → revisar → submeter → apresentar*.

---

## 1. Evento

| Campo | Informação |
|-------|------------|
| **Nome** | III Congresso UniSENAI-SP de Educação, Tecnologia e Inovação |
| **Data** | 04 e 05/12/2026 |
| **Local** | SENAI São Caetano do Sul — São Caetano do Sul (SP) |
| **Formato** | Híbrido (presencial com transmissão online) |
| **Tipo de trabalho** | Resumo expandido (3 a 5 páginas, Arial 12, justificado, ABNT) |
| **Formas de apresentação** | Painel/banner ou apresentação oral, a definir pela organização |
| **Página oficial** | https://www.even3.com.br/iiicongressounisenai-sp-721261/ |

---

## 2. Trabalho submetido

| Campo | Informação |
|-------|------------|
| **Título** | Arquitetura Orientada a Eventos em Nuvem: uma proposta baseada em serviços AWS para aplicações escaláveis |
| **Título em inglês** | Event-Driven Architecture in the Cloud: an AWS-based proposal for scalable applications |
| **Palavras-chave** | arquitetura orientada a eventos; computação em nuvem; *serverless*; microsserviços; escalabilidade |
| **Estágio da pesquisa** | Em desenvolvimento — proposta arquitetural com análise qualitativa; validação experimental prevista como trabalho futuro |
| **Arquivo** | [`docs/artigos/resumo-expandido.pdf`](../docs/artigos/resumo-expandido.pdf) |

---

## 3. Cronograma e situação

| Etapa | Prazo | Situação |
|-------|-------|----------|
| Produção do resumo expandido no template do evento | — | Concluído |
| Envio aos orientadores para revisão | 18/09/2026 | Concluído — enviado em 18/09/2026 |
| Ajustes solicitados pelos orientadores | até 25/09/2026 | Pendente |
| Submissão na plataforma do evento (Even3) | 25/09/2026 | Pendente |
| Inscrição como apresentador | 16/10/2026 | Pendente — modalidade escolhida: **Apresentador Online** |
| Resultado da avaliação | a divulgar | Aguardando |
| Apresentação no evento | 04–05/12/2026 | Aguardando |

---

## 4. Como o resumo expandido foi construído

O resumo expandido é uma versão condensada e adaptada do artigo final integrador da Atividade 05 ([`docs/artigos/Atividade05-ArtigoFinal.docx`](../docs/artigos/Atividade05-ArtigoFinal.docx)), reorganizada na estrutura exigida pelo template do congresso:

| Seção do template | Origem do conteúdo |
|-------------------|--------------------|
| Introdução (problema, objetivos, justificativa) | Artigo final (seções 1 e 2) e relatório de escrita científica ([`docs/relatorios/`](../docs/relatorios/)) |
| Revisão de literatura | Levantamento bibliográfico da Tarefa 04 ([`referencias/`](../referencias/)) |
| Metodologia | Etapas efetivamente realizadas na IC: levantamento bibliográfico, definição de requisitos, projeto arquitetural e análise qualitativa |
| Resultados e discussões | Arquitetura consolidada ([`arquitetura/`](../arquitetura/)) e análise de segurança e escalabilidade do artigo final |
| Conclusão | Confronto entre objetivos, hipótese e resultados; limitações e trabalhos futuros |

**Decisões tomadas na adaptação:**

- O texto foi reduzido para caber no limite de 5 páginas, mantendo apenas as referências efetivamente citadas.
- Como a pesquisa está em desenvolvimento, os resultados são apresentados como **parciais**: a contribuição é a proposta arquitetural e sua análise qualitativa. Não foram realizadas implementação nem medições de desempenho, e isso está declarado no resumo, nos resultados e na conclusão.
- Foram incluídas as contrapartidas da arquitetura (consistência eventual, necessidade de consumidores idempotentes, dependência da camada de observabilidade e *vendor lock-in*).

**Correções nas referências** identificadas ao conferir os PDFs de [`referencias/pdfs/`](../referencias/pdfs/):

| Como estava | Correção |
|-------------|----------|
| SILVA, I. P. A. (2013) | PORTO, I. O. *Padrões e diretrizes arquiteturais para escalabilidade de sistemas*. Dissertação — UFU, 2009 |
| CORDEIRO, A. F. R. et al. (2024) | MORAIS, L. Z.; CORDEIRO, A. F. R.; OLIVEIRAJR, E. ERES, 2025 |
| ESCOLA REGIONAL DE INFORMÁTICA DE MATO GROSSO (2024) | COSTA, R. F.; ANTONELLI, H. L. ERI-ES, 2025. DOI: 10.5753/eries.2025.15930 |
| IMPACTOS da computação em nuvem... (2024), sem autoria | RAPÔSO, C. F. L.; COSTA JUNIOR, O. G.; FERREIRA, A. S. Revista Tópicos, 2024 |

---

## 5. Relação com a Tarefa 06

Na [Tarefa 06](tarefa06-publicacao.md) foi traçado um percurso de amadurecimento para a pesquisa: *resumo expandido em evento → workshop de IC (WTICG/SBRC ou NIRE/SBSI) → artigo completo na REIC*. A submissão ao III Congresso UniSENAI-SP corresponde ao **primeiro passo** desse percurso. A principal lição daquela pesquisa — de que trabalhos aceitos costumam trazer alguma forma de avaliação — orienta os próximos passos da IC: implementar um protótipo e medir latência e custo.

---

## 6. Resultado e apresentação

*Seção a preencher após a avaliação do evento.*

- **Resultado da submissão:** aguardando
- **Formato de apresentação definido:** aguardando
- **Observações dos avaliadores:** —

---

## Checklist dos Requisitos Mínimos

| Requisito | Status | Onde está / observação |
|-----------|:------:|------------------------|
| Inscrição em uma das modalidades disponíveis | Pendente | Modalidade: Apresentador Online — prazo: 16/10/2026 |
| Resumo expandido relacionado ao projeto de IC | Sim | `docs/artigos/resumo-expandido.pdf` |
| Orientador adicionado como coautor | Sim | Prof. Deivison Shindi Takatu (autor 2) — conferir nome e ordem dos autores na plataforma |
| Envio do trabalho para revisão até 18/09/2026 | Sim | Enviado aos orientadores em 18/09/2026 |
| Realização dos ajustes solicitados | Pendente | |
| Submissão do trabalho até 25/09/2026 | Pendente | |
| Registro do trabalho no repositório | Sim | Este arquivo + PDF do resumo |
| Acompanhamento do resultado da submissão | Aguardando | Seção 6 |
| Conferência das informações sobre apresentação | Aguardando | Próximo ao evento |
