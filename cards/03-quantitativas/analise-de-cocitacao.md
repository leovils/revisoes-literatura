# Análise de Cocitação

> **Família:** Quantitativa/Computacional

## Definição

Mede a frequência com que pares de obras (ou autores, ou journals) são citados juntos por outros artigos. Revela a estrutura intelectual passada — as raízes teóricas que sustentam o campo.

## Quando usar

- ✓ Mapear tradições teóricas e "escolas de pensamento"
- ✓ Identificar obras-pilares e suas conexões
- ✓ Estudos histórico-conceituais de campos consolidados

## Quando NÃO usar

- ✗ Para mapear pesquisa em curso (use acoplamento bibliográfico)
- ✗ Em campos muito jovens (poucas citações ainda)

## Passo a passo

1. Coletar artigos do campo (citing articles)
2. Extrair as referências citadas (cited references)
3. Construir matriz de cocitação (frequência de pares co-citados)
4. Aplicar normalização (similaridade — cosseno, Salton, association strength)
5. Clusterizar (algoritmo de modularidade no VOSviewer ou similar)
6. Interpretar clusters como tradições/escolas
7. Validar com leitura qualitativa de obras centrais

## Ferramentas

VOSviewer, CiteSpace, Bibliometrix.

## Critérios de qualidade

- Limiar mínimo de cocitação justificado
- Normalização adequada da matriz
- Interpretação qualitativa dos clusters

## Armadilhas

- ⚠️ Confundir com acoplamento bibliográfico
- ⚠️ Limiar muito baixo gera ruído
- ⚠️ Não interpretar os clusters teoricamente

## Exemplo

Cocitação de autores em estudos de empreendedorismo internacional revelando 4 escolas: Uppsala, Born Global, RBV e Networks.

## Exemplos publicados

### Exemplo 1

Small, H. (1973). Co-citation in the scientific literature: A new measure of the relationship between two documents. *Journal of the American Society for Information Science*, 24(4), 265–269.

**Ranking:** Paper fundador

**Por que é exemplar:** Paper que define o método. Seminal para entender a lógica: dois papers cocitados pelo mesmo terceiro paper têm relação intelectual, mesmo sem citar um ao outro. Fundamento de tudo que veio depois.

### Exemplo 2

Vogel, R., & Güttel, W. H. (2013). The dynamic capabilities view in strategic management: A bibliometric review. *International Journal of Management Reviews*, 15(4), 426–446.

**Ranking:** ABS 3 · Qualis A1

**Por que é exemplar:** Modelo de cocitação aplicada em management. Mapeia raízes intelectuais de "dynamic capabilities" e identifica clusters teóricos. Excelente template para revisões em qualquer subcampo de strategy.

### Exemplo 3

Ramos-Rodríguez, A. R., & Ruíz-Navarro, J. (2004). Changes in the intellectual structure of strategic management research: A bibliometric study of the Strategic Management Journal, 1980–2000. *Strategic Management Journal*, 25(10), 981–1004.

**Ranking:** ABS 4* · Qualis A1

**Por que é exemplar:** Cocitação aplicada de forma rigorosa em SMJ — top journal. Mostra evolução da estrutura intelectual de strategic management ao longo de 20 anos. Modelo do que faz cocitação ser "publicável em top journal".

### Exemplo 4

Serra, F. A. R., Ferreira, M. P., Guerrazzi, L. A. de C., & Scaciotta, V. V. (2018). Doing bibliometric reviews for the Iberoamerican Journal of Strategic Management. *Revista Ibero-Americana de Estratégia*, 17(3), 1–16.

**Ranking:** Qualis A2

**Por que é exemplar:** Comentário editorial da RIAE com roteiro metodológico robusto para estudos bibliométricos de cocitação E pareamento (acoplamento). Em português, com olhar de editor experiente em journal brasileiro de estratégia. Útil para o aluno entender o que reviewers brasileiros valorizam.

## Referência metodológica chave

Small, H. (1973). Co-citation in the scientific literature: A new measure of the relationship between two documents. Journal of the American Society for Information Science, 24(4), 265–269.

---

*Material do curso MTPQI · Programa de Pós-Graduação em Administração · UNINOVE*