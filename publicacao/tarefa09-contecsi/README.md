# Tarefa 09 — Publicação no CONTECSI (resumo expandido)

**Projeto de Iniciação Científica:** Arquitetura Orientada a Eventos (*Event-Driven Architecture* — EDA) em nuvem AWS
**Autor:** Pedro Vitor Ribeiro Silva
**Orientador:** Prof. Deivison Shindi Takatu
**Última atualização:** 10/11/2026

> **Objetivo desta atividade:** adaptar o projeto de IC para um trabalho do CONTECSI, usando o template da modalidade escolhida, e registrar o andamento da submissão.

---

## 1. Modalidade

| Campo | Informação |
|-------|------------|
| **Modalidade escolhida** | **REX — Resumo expandido** (trilha de Graduação) |
| **Evento** | 21º CONTECSI — International Conference on Information Systems and Technology Management (TECSI FEA USP), **virtual, 01 a 04 de dezembro de 2026**. Chamada de trabalhos: 28/08/2026 a **10/11/2026** |
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
| **Arquivo** | [`manuscrito/resumo-expandido.docx`](manuscrito/resumo-expandido.docx) (revisão 2, 12 páginas) e [`manuscrito/resumo-expandido.pdf`](manuscrito/resumo-expandido.pdf) |
| **Fontes e trabalhos relacionados** | [`referencias/fontes-e-trabalhos-relacionados.md`](referencias/fontes-e-trabalhos-relacionados.md) |

**Contribuição:** proposta de uma arquitetura orientada a eventos em cinco camadas (apresentação, entrada, mensageria, processamento e persistência/observabilidade) sobre serviços gerenciados da AWS, com análise qualitativa de escalabilidade, resiliência e segurança, e discussão das contrapartidas (consistência eventual, idempotência, observabilidade e *vendor lock-in*).

**Adaptação ao template** (a partir do resumo expandido da Tarefa 07):

- Seções reordenadas conforme o template: Introdução (com objetivos ao final), Metodologia, Referencial teórico, Resultados e discussão, Considerações finais e Referências bibliográficas.
- "Revisão de literatura" passou a "Referencial teórico" e "Conclusão" passou a "Considerações finais".
- Resumo e *abstract* em parágrafo único; palavras-chave em ordem alfabética e com inicial maiúscula.
- Bloco de autores no formato do template (nome, ORCID, CPF, instituição e e-mail) e minicurrículo nas notas de rodapé.

**Revisão 2 (10/11/2026): ajustes conforme os comentários do orientador (05/11/2026)**

| Comentário | Ajuste feito |
|------------|--------------|
| Conferir e atualizar a identificação do evento | Cabeçalho atualizado para "21º CONTECSI – Trilha de Graduação – 01 a 04 de dezembro de 2026 – Resumo Expandido". |
| "Remover" (linha "Fatec Itapetininga - Virtual") | Linha removida do cabeçalho. |
| Na submissão, confirmar se é necessário retirar as informações dos autores | **Pendente** (ver pendências). O texto não foi alterado. |
| Demonstrar a lacuna com trabalhos relacionados | Justificativa reescrita: seis trabalhos comparados em seis critérios no novo **Quadro 1**, com o diferencial da proposta explicitado. |
| Deixar claro que os ganhos são esperados com base na literatura | Hipótese reformulada como "hipótese de trabalho", deixando claro que não é um resultado da pesquisa. |
| Relacionar requisitos, alternativas e justificativas | Requisitos numerados (R1 a R5) na Metodologia e novo **Quadro 2** (requisito, escolha, alternativas, justificativa). |
| Mostrar como cada camada atende aos requisitos e qual é a contribuição | Novo parágrafo em Resultados ligando cada camada aos requisitos, com a contribuição específica da organização. Também troquei "implantada" por "projetada", porque não há protótipo. |
| Aprofundar a discussão: duplicatas, ordem e consistência | Dois parágrafos novos: consumidor idempotente, SNS/SQS FIFO e versionamento, *transactional outbox*, saga e reconciliação. |
| Manter a delimitação nas conclusões | Considerações finais reescritas: os ganhos ficam como hipótese, sem evidência experimental. |
| Adicionar mais referências | Passou de 7 para 16 referências: Dantas, Lima, Prestes *et al.*, Stradolini, Hohpe e Woolf, Jonas *et al.*, Kleppmann, Mell e Grance, Richardson. Também completei os dados de Morais *et al.* e Villaça e Azevedo. |

Correção técnica: o Word não abria o arquivo original ("arquivo corrompido") por causa da caixa de texto do cabeçalho exportada pelo Google Docs. Troquei a caixa por parágrafos centralizados com o mesmo texto. A linha "MODALIDADE ARTIGO (REX) – GRADUAÇÃO", que ficava oculta na caixa, foi retirada.

---

## 4. Situação

| Campo | Informação |
|-------|------------|
| **Status** | Em preparação — **não submetido** |
| **Data de submissão** | — |
| **Código de confirmação** | — |

**Pendências:**

1. **Prazo:** a página de submissões indica a chamada até **10/11/2026**. Confirmar se ainda é possível submeter ou se houve prorrogação.
2. **Identificação dos autores:** a chamada exige arquivo "sem identificação de autores" nas modalidades PSE, COM e consórcio, e diz que o REX segue o próprio template. Confirmar no template do REX ou pelo e-mail contecsiusp@gmail.com se o bloco de autores, as notas de rodapé e os agradecimentos devem sair da versão submetida.
3. Confirmar com o orientador a versão do template e a modalidade (REX).
4. Registrar os links dos dois exemplos aceitos na 20ª edição (trilha 110).
5. Revisão final com os orientadores. A introdução cresceu com a nova Justificativa e o Quadro 1; conferir o limite de 2.500 caracteres e um eventual limite de páginas do REX (hoje são 12 páginas).
6. Submeter no sistema do evento e registrar aqui a data e o código de confirmação.

---

## 5. Dados pessoais

A versão deste repositório **omite os CPFs** exigidos pelo template, que são preenchidos apenas na versão enviada ao evento e mantidos fora do GitHub. Os ORCID dos autores e os e-mails institucionais já são públicos.
