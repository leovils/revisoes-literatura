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

## Referência metodológica chave

Small, H. (1973). Co-citation in the scientific literature: A new measure of the relationship between two documents. Journal of the American Society for Information Science, 24(4), 265–269.

---

*Material do curso MTPQI · Programa de Pós-Graduação em Administração · UNINOVE*