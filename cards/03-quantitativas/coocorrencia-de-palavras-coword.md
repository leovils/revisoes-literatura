# Coocorrência de Palavras (Coword)

> **Família:** Quantitativa/Computacional

## Definição

Analisa pares de palavras-chave que aparecem juntas em artigos para revelar a estrutura conceitual do campo — os temas e suas relações.

## Quando usar

- ✓ Mapear estrutura conceitual e tópicos do campo
- ✓ Identificar temas emergentes e em declínio (com análise temporal)
- ✓ Complementar cocitação ou acoplamento com nível conceitual

## Quando NÃO usar

- ✗ Quando keywords são pobres ou inexistentes (use topic modeling)

## Passo a passo

1. Coletar artigos com keywords (author + indexer keywords)
2. Limpar e harmonizar (sinonímia, plural, capitalização)
3. Construir matriz de coocorrência
4. Clusterizar conceitualmente
5. Análise temporal (overlay) para tendências
6. Interpretar com leitura qualitativa

## Ferramentas

VOSviewer, CiteSpace, Bibliometrix.

## Critérios de qualidade

- Limpeza criteriosa das keywords
- Limiar mínimo de coocorrência
- Visualização temporal quando relevante

## Armadilhas

- ⚠️ Pular limpeza de keywords (resultados ruidosos)
- ⚠️ Confundir coword com topic modeling
- ⚠️ Não usar análise temporal quando ela seria informativa

## Exemplo

Coocorrência de keywords em 1.200 artigos sobre "digital marketing" mostrando emergência de "AI", "chatbot" e "voice search" após 2020.

## Exemplos publicados

### Exemplo 1

Callon, M., Courtial, J. P., & Laville, F. (1991). Co-word analysis as a tool for describing the network of interactions between basic and technological research: The case of polymer chemistry. *Scientometrics*, 22(1), 155–205.

**Ranking:** Paper fundador

**Por que é exemplar:** Paper canônico que define o método. Introduz "strategic diagram" (centralidade × densidade) para identificar temas motor, periféricos, emergentes e em declínio. Base de toda análise de coword publicada depois.

### Exemplo 2

Cobo, M. J., López-Herrera, A. G., Herrera-Viedma, E., & Herrera, F. (2011). An approach for detecting, quantifying, and visualizing the evolution of a research field: A practical application to the Fuzzy Sets Theory field. *Journal of Informetrics*, 5(1), 146–166.

**Ranking:** Qualis A1

**Por que é exemplar:** Atualiza o método para mostrar **evolução longitudinal** (não só snapshot). Apresenta o software SciMAT (gratuito) e demonstra com aplicação real. Padrão atual para coword com componente temporal.

## Referência metodológica chave

Callon, M., Courtial, J. P., & Laville, F. (1991). Co-word analysis as a tool for describing the network of interactions between basic and technological research. Scientometrics, 22(1), 155–205.

---

*Material do curso MTPQI · Programa de Pós-Graduação em Administração · UNINOVE*