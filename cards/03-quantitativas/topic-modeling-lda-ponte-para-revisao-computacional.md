# Topic Modeling (LDA) — ponte para revisão computacional

> **Família:** Quantitativa/Computacional

## Definição

Técnica de aprendizado de máquina não supervisionada que descobre tópicos latentes em grandes corpora textuais (abstracts, artigos completos). Latent Dirichlet Allocation (LDA) é a abordagem mais usada.

## Quando usar

- ✓ Corpora muito grandes (milhares de documentos)
- ✓ Quando keywords são insuficientes ou inexistentes
- ✓ Para descobrir tópicos não previstos pelo pesquisador
- ✓ Como complemento à bibliometria tradicional

## Quando NÃO usar

- ✗ Em corpora pequenos (< 200 docs)
- ✗ Quando o objetivo é interpretação fina de poucos textos
- ✗ Sem competência mínima em programação (R/Python)

## Passo a passo

1. Coletar corpus textual (abstracts ou full-texts)
2. Pré-processamento (tokenização, stopwords, lematização)
3. Definir número de tópicos K (perplexity, coherence)
4. Treinar modelo LDA
5. Inspecionar tópicos (top words por tópico)
6. Nomear tópicos com leitura qualitativa
7. Análise temporal/comparativa quando aplicável

## Ferramentas

R (topicmodels, stm), Python (gensim, sklearn), MALLET.

## Critérios de qualidade

- Pré-processamento criterioso
- Justificativa do K
- Coherence score reportado
- Validação humana dos tópicos

## Armadilhas

- ⚠️ K mal escolhido gera tópicos sem sentido
- ⚠️ Pular validação qualitativa
- ⚠️ Aplicar a corpora pequenos demais

## Exemplo

LDA aplicado a 10.000 abstracts de pesquisa em sustentabilidade revelando 12 tópicos latentes não capturados pelas keywords.

## Referência metodológica chave

Blei, D. M., Ng, A. Y., & Jordan, M. I. (2003). Latent Dirichlet Allocation. Journal of Machine Learning Research, 3, 993–1022.

---

*Material do curso MTPQI · Programa de Pós-Graduação em Administração · UNINOVE*