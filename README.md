# Revisões de Literatura — Família Completa

> Repositório de referência sobre **abordagens de revisão de literatura** em ciências sociais aplicadas, com foco em Administração. Material pedagógico do curso **MTPQI — Métodos e Técnicas de Pesquisa Quantitativa I** do PPGA/UNINOVE.

**🌳 [Árvore de decisão interativa →](https://SEU-USUARIO.github.io/revisoes-literatura-mtpqi/)** *(será o link após publicar via GitHub Pages)*

---

## O que tem aqui

- 📇 **24 abordagens** de revisão de literatura, cada uma com card padronizado (definição, quando usar, passo a passo, ferramentas, armadilhas, exemplo, referência canônica)
- 📊 **Apresentação** estilo MTPQI (.pptx) — 38 slides para uso em aula
- 📄 **Material completo** em Word (.docx) — 40 páginas para leitura
- 🌳 **Widget interativo** de árvore de decisão (HTML estático, publicável via GitHub Pages)
- 🔧 **Templates e protocolos** (PRISMA 2020, extração de dados, strings de busca por base)
- 💻 **Scripts** em R e Python para meta-análise, bibliometria e topic modeling

---

## Mapa das 5 famílias

### I. [Tradicionais](cards/01-tradicionais/) (4)
Sem protocolo formal — argumento, contexto, fundamentação teórica.

- [Revisão Narrativa (tradicional)](cards/01-tradicionais/narrativa.md)
- [Revisão Crítica](cards/01-tradicionais/critica.md)
- [Estado da Arte](cards/01-tradicionais/estado-da-arte.md)
- [Ensaio Teórico-Conceitual](cards/01-tradicionais/ensaio-teorico-conceitual.md)

### II. [Com Protocolo](cards/02-com-protocolo/) (6)
Reprodutíveis, baseadas em protocolo registrado, alinhadas a guidelines (PRISMA, RAMESES).

- [Revisão Sistemática (SLR)](cards/02-com-protocolo/sistematica-slr.md)
- [Revisão de Escopo (Scoping Review)](cards/02-com-protocolo/de-escopo.md)
- [Revisão Integrativa](cards/02-com-protocolo/integrativa.md)
- [Revisão Realista (Realist Review)](cards/02-com-protocolo/realista-realist-review.md)
- [Revisão Rápida (Rapid Review)](cards/02-com-protocolo/rapida-rapid-review.md)
- [Umbrella Review (Revisão de Revisões)](cards/02-com-protocolo/umbrella-review-revisao-de-revisoes.md)

### III. [Quantitativas e Computacionais](cards/03-quantitativas/) (8)
Bibliometria (citação, cocitação, acoplamento, coautoria, coword), meta-análise, topic modeling.

- [Bibliometria — Visão Geral](cards/03-quantitativas/bibliometria-visao-geral.md)
- [Análise de Citação](cards/03-quantitativas/analise-de-citacao.md)
- [Análise de Cocitação](cards/03-quantitativas/analise-de-cocitacao.md)
- [Acoplamento Bibliográfico](cards/03-quantitativas/acoplamento-bibliografico.md)
- [Coautoria](cards/03-quantitativas/coautoria.md)
- [Coocorrência de Palavras (Coword)](cards/03-quantitativas/coocorrencia-de-palavras-coword.md)
- [Meta-análise](cards/03-quantitativas/meta-analise.md)
- [Topic Modeling (LDA) — ponte para revisão computacional](cards/03-quantitativas/topic-modeling-lda-ponte-para-revisao-computacional.md)

### IV. [Sínteses Qualitativas](cards/04-sinteses-qualitativas/) (3)
Meta-síntese, meta-etnografia, síntese temática.

- [Meta-síntese](cards/04-sinteses-qualitativas/meta-sintese.md)
- [Meta-etnografia](cards/04-sinteses-qualitativas/meta-etnografia.md)
- [Síntese Temática](cards/04-sinteses-qualitativas/sintese-tematica.md)

### V. [Frameworks de Administração](cards/05-frameworks-admin/) (3)
TCCM, SPAR-4-SLR, ADO — específicos para revisões em business e management.

- [TCCM Framework](cards/05-frameworks-admin/tccm-framework.md)
- [SPAR-4-SLR Protocol](cards/05-frameworks-admin/spar-4-slr-protocol.md)
- [ADO Framework (Antecedents–Decisions–Outcomes)](cards/05-frameworks-admin/ado-framework-antecedents-decisions-outcomes.md)

---

## Como decidir qual usar

```
PERGUNTA INICIAL: qual o objetivo principal da sua revisão?

├── SINTETIZAR EVIDÊNCIA → família II (Com Protocolo) ou meta-análise
│     ├── X→Y quantitativo comparável → Meta-análise
│     ├── X→Y heterogêneo → Sistemática (SLR)
│     ├── Quali + Quanti → Integrativa
│     ├── Por que/em que contexto funciona → Realista
│     ├── Estudos quali → Síntese Temática ou Meta-etnografia
│     ├── Várias SLRs já existem → Umbrella Review
│     └── Prazo curto → Rápida
│
├── MAPEAR/EXPLORAR CAMPO → família III (Quantitativas) ou Escopo
│     ├── "O que se sabe sobre X?" → Escopo
│     ├── Diagnóstico completo → Bibliometria
│     ├── Raízes intelectuais → Cocitação
│     ├── Frentes atuais → Acoplamento bibliográfico
│     ├── Estrutura social → Coautoria
│     ├── Estrutura conceitual → Coword
│     └── Tópicos latentes em corpus textual → Topic Modeling (LDA)
│
└── ARGUMENTAR/PROPOR TEORIA → família I (Tradicionais) ou família V
      ├── Contextualização ampla → Narrativa
      ├── Questionar paradigma → Crítica
      ├── Propor framework novo → Ensaio teórico-conceitual
      ├── Atualização recente do campo → Estado da arte
      └── Revisão em business → TCCM, SPAR-4-SLR ou ADO
```

Para usar a versão interativa: [abra o widget](widget/index.html) ou acesse via [GitHub Pages](#) após o deploy.

---

## Sete princípios transversais

Independente da abordagem escolhida, estes elevam a qualidade e reduzem rejeição em revisão por pares:

1. **Pergunta de pesquisa clara** (PICO, PICOC, SPIDER, CIMO, TCCM)
2. **Protocolo explícito** — reprodutibilidade é inegociável
3. **Bases adequadas e justificadas** — WoS + Scopus se complementam
4. **Strings de busca testadas** — *garbage in, garbage out*
5. **Dois revisores na triagem** — cego, com kappa de Cohen reportado
6. **Avaliação de qualidade** — CASP, MMAT, ROBIS, Newcastle-Ottawa
7. **Reporte conforme guideline** — PRISMA 2020, eMERGe, RAMESES, MARS

---

## Estrutura do repositório

```
revisoes-literatura-mtpqi/
├── cards/                  # 19 cards em markdown (fonte de verdade)
│   ├── 01-tradicionais/
│   ├── 02-com-protocolo/
│   ├── 03-quantitativas/
│   ├── 04-sinteses-qualitativas/
│   └── 05-frameworks-admin/
├── aulas/
│   ├── pptx/              # apresentação MTPQI (38 slides)
│   └── docx/              # texto-base (40 páginas)
├── widget/                # árvore de decisão interativa (publicada via Pages)
├── protocolos/            # templates PRISMA, extração, etc.
├── queries/               # strings de busca por base (WoS, Scopus)
├── scripts/
│   ├── R/                 # meta-análise (metafor), bibliometria (bibliometrix)
│   └── python/            # topic modeling (gensim, BERTopic)
└── exemplos/              # papers exemplares por abordagem
```

---

## Como usar este material

**Em aula expositiva** → use o PPTX (`aulas/pptx/`).
**Como leitura prévia** → distribua o DOCX (`aulas/docx/`).
**Como atividade de fixação** → peça que o aluno use o widget interativo pensando na própria pesquisa e justifique a escolha.
**Como referência permanente** → cada card é um arquivo `.md` autocontido, navegável pelo GitHub.

---

## Como contribuir

Pull requests com correções, exemplos novos ou abordagens adicionais são bem-vindos. Veja [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Licença

- **Conteúdo** (textos, slides, widget): [CC BY 4.0](LICENSE-content) — use, adapte, compartilhe com atribuição.
- **Código** (scripts, build tools): [MIT](LICENSE-code).

---

## Citação

Se este material for útil em seu ensino ou pesquisa, cite assim:

> Vils, L. (2026). *Revisões de Literatura — Família Completa: material didático do curso MTPQI*. PPGA/UNINOVE. Disponível em: https://github.com/SEU-USUARIO/revisoes-literatura-mtpqi

---

**Prof. Dr. Leonardo Vils** · MTPQI · PPGA/UNINOVE
