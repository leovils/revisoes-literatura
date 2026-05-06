# Meta-análise

> **Família:** Quantitativa/Computacional

## Definição

Síntese estatística que combina resultados de múltiplos estudos primários quantitativos para estimar um tamanho de efeito agregado, com seu intervalo de confiança e teste de heterogeneidade. É o padrão-ouro da síntese de evidência quantitativa.

## Quando usar

- ✓ Quando há múltiplos estudos quantitativos sobre a mesma relação
- ✓ Para estimar tamanho de efeito médio de uma relação X→Y
- ✓ Para testar moderadores e fontes de heterogeneidade
- ✓ Forte aderência ao paradigma das New Statistics (Cumming)

## Quando NÃO usar

- ✗ Quando os estudos são metodologicamente incomparáveis
- ✗ Para sínteses qualitativas (use meta-síntese ou síntese temática)
- ✗ Em campos com pouca evidência primária quantitativa

## Passo a passo

1. Definir pergunta e protocolo (idealmente registrar)
2. Conduzir SLR como base para o corpus
3. Extrair tamanhos de efeito e estatísticas necessárias
4. Calcular tamanhos de efeito padronizados (d, r, OR, RR)
5. Escolher modelo (efeitos fixos vs. aleatórios — geralmente aleatórios)
6. Combinar efeitos com pesos por inverso da variância
7. Avaliar heterogeneidade (Q, I², τ²)
8. Análise de moderadores (meta-regressão, subgrupos)
9. Avaliar viés de publicação (funnel plot, trim-and-fill, Egger)
10. Reportar com forest plot e checklist PRISMA

## Ferramentas

R (metafor, meta), CMA, Stata, RevMan, jamovi/JASP.

## Critérios de qualidade

- Modelo de efeitos aleatórios em ciências sociais
- Avaliação de heterogeneidade reportada
- Análise de viés de publicação
- Reportar forest plot e funnel plot
- Aderência ao MARS (Meta-Analysis Reporting Standards) da APA

## Armadilhas

- ⚠️ Garbage in, garbage out (corpus mal selecionado)
- ⚠️ Confundir significância estatística com tamanho de efeito
- ⚠️ Ignorar heterogeneidade alta (I² > 75%)
- ⚠️ Não testar viés de publicação

## Exemplo

Meta-análise sobre o efeito da liderança transformacional na satisfação no trabalho, agregando 80 estudos com k=78.000 respondentes.

## Referência metodológica chave

Borenstein, M., Hedges, L. V., Higgins, J. P., & Rothstein, H. R. (2009). Introduction to Meta-Analysis. Wiley. | Hunter, J. E., & Schmidt, F. L. (2004). Methods of Meta-Analysis. Sage.

---

*Material do curso MTPQI · Programa de Pós-Graduação em Administração · UNINOVE*