# Tarefa 08 — Preparação do Banner Científico (versão preliminar)

**Projeto de Iniciação Científica:** Arquitetura Orientada a Eventos (*Event-Driven Architecture* — EDA) em nuvem AWS
**Autor:** Pedro Vitor Ribeiro Silva
**Orientador:** Prof. Deivison Shindi Takatu
**Última atualização:** 06/11/2026

> **Objetivo desta atividade:** transformar o resumo expandido da [Tarefa 07](../tarefa07-congresso.md) em uma apresentação visual (banner/pôster), clara e objetiva, para o III Congresso UniSENAI-SP. Como o evento **ainda não divulgou um modelo oficial de banner**, esta é uma **versão preliminar** feita sobre um modelo provisório, a ser adaptada quando saírem as orientações oficiais.

---

## 1. Arquivos entregues

| Arquivo | Descrição |
|---------|-----------|
| [`banner-v1.pdf`](banner-v1.pdf) | Versão em PDF do banner (para visualização; **não imprimir** antes das regras oficiais). |
| [`banner-v1.pptx`](banner-v1.pptx) | **Arquivo editável** (PowerPoint). Formato, textos, cores e diagrama podem ser ajustados. |
| [`banner-v1-preview.png`](banner-v1-preview.png) | Imagem de pré-visualização do banner, para consulta rápida. |

---

## 2. Template escolhido (provisório)

| Item | Informação |
|------|------------|
| **Tipo de modelo** | Pôster/banner acadêmico-científico — **A0 retrato (841 × 1189 mm)**, layout de duas colunas com cabeçalho e rodapé, padrão comum em congressos. |
| **Como foi montado** | Construído do zero em formato PowerPoint editável, seguindo a estrutura convencional de pôster científico (título de leitura à distância, seções curtas, destaque para a figura). O arquivo `.pptx` passa a ser o **próprio template editável** do trabalho. |
| **Fontes/galerias de referência consultadas** | Canva — Pôsteres acadêmicos: <https://www.canva.com/pt_br/posteres/modelos/academico/> · Microsoft Create (templates do PowerPoint): <https://create.microsoft.com/pt-br/templates/p%C3%B4steres> |
| **Identidade visual** | Paleta petróleo/âmbar escolhida para harmonizar com o diagrama da arquitetura (cores dos serviços AWS). **Logotipos oficiais do SENAI/UniSENAI ainda não foram inseridos** — serão adicionados conforme as regras do evento. |

> **Importante:** as dimensões, cores e organização visual acima são **provisórias**. Não devem ser tratadas como exigências oficiais do III Congresso UniSENAI-SP.

---

## 3. Ferramenta utilizada

- **Edição:** Microsoft PowerPoint (arquivo `.pptx`). O banner foi gerado por script (`pptxgenjs`) e pode ser aberto e editado normalmente no PowerPoint.
- **Exportação para PDF:** feita a partir do próprio PowerPoint.
- **Figura 1 (arquitetura):** redesenhada de forma **nativa** dentro do slide (caixas e setas editáveis), em vez de imagem fixa, para facilitar ajustes de cor, texto e tamanho. A versão original em imagem continua em [`../../arquitetura/diagrama.png`](../../arquitetura/diagrama.png).

---

## 4. Justificativa da organização visual

- **Cabeçalho** com título grande (legível à distância), autores e orientadores, instituição e dados do evento; selo indicando que é **pesquisa de IC em andamento**.
- **Duas colunas** separando a lógica da pesquisa:
  - **Esquerda:** Introdução e contexto → Problema → Objetivos → Metodologia → Referências.
  - **Direita:** Resultados parciais → Figura 1 (arquitetura) → Considerações preliminares → Agradecimentos.
- **Frases curtas e tópicos** em vez de parágrafos longos; cada seção em um cartão com título claro.
- **Destaque para a Figura 1**, que comunica a proposta (fluxo de eventos nas cinco camadas) mais rápido que o texto.
- **Resultados apresentados como parciais**, com a limitação (ausência de validação experimental) declarada de forma explícita, coerente com o resumo expandido.
- Conteúdo é uma **síntese** do resumo expandido — não reproduz o texto inteiro.

---

## 5. Conferência das informações (Parte 4 da atividade)

| Verificação | Situação |
|-------------|:--------:|
| Título idêntico ao trabalho submetido na Tarefa 07 | ✔ |
| Autores e orientadores conforme o resumo expandido (Pedro Vitor; Deivison Takatu; Glauco Todesco) | ✔ |
| Problema e objetivos claros | ✔ |
| Metodologia compreensível (4 etapas) | ✔ |
| Resultados verdadeiros e coerentes (análise qualitativa; sem medições) | ✔ |
| Conclusões não afirmam mais do que os dados permitem | ✔ |
| Referências do banner identificadas (subconjunto das do resumo) | ✔ |
| Ortografia, nomes e instituição revisados | ✔ |

---

## 6. Pontos a conferir/adaptar quando saírem as regras oficiais

Esta versão é **preliminar**. Ao divulgar o modelo oficial, revisar:

1. **Dimensões e orientação** (o modelo oficial pode não ser A0 retrato).
2. **Formato e arquivo para envio/impressão** (tamanho, margens, resolução).
3. **Identidade visual e logotipos obrigatórios** (SENAI / UniSENAI-SP / fomento), ainda **não inseridos**.
4. **Seções obrigatórias** exigidas pela comissão (podem diferir das atuais).
5. **Regras de autoria** (ordem, filiação, formato dos nomes).
6. **Demais orientações** da comissão organizadora.

> **Não imprimir** o banner antes de confirmar regras e dimensões oficiais do evento. Acompanhar a página oficial: <https://www.even3.com.br/iiicongressounisenai-sp-721261/>

---

## 7. Checklist dos Requisitos Mínimos

| Requisito | Status | Observação |
|-----------|:------:|------------|
| Selecionar um template acadêmico provisório | ✔ | Pôster A0 retrato (seção 2) |
| Registrar a fonte do template | ✔ | Galerias de referência na seção 2 |
| Preparar o banner com base no resumo expandido da Tarefa 07 | ✔ | Conteúdo sintetizado do PDF submetido |
| Incluir as seções relevantes ao estágio atual | ✔ | Resultados **parciais**; IC em andamento |
| Conferir autores, instituição, referências e consistência | ✔ | Seção 5 |
| Salvar uma versão em PDF | ✔ | [`banner-v1.pdf`](banner-v1.pdf) |
| Manter também o arquivo editável | ✔ | [`banner-v1.pptx`](banner-v1.pptx) |
| Registrar no README template e ajustes pendentes | ✔ | Seções 2 e 6 |
| Organizar os arquivos no repositório | ✔ | Pasta `publicacao/tarefa08-banner/` |
