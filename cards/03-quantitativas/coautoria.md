# Coautoria

> **Família:** Quantitativa/Computacional

## Definição

Analisa redes de colaboração entre autores, instituições ou países. Revela a estrutura social do campo.

## Quando usar

- ✓ Mapear comunidades científicas e suas conexões
- ✓ Identificar autores centrais e brokers (intermediários)
- ✓ Estudos sobre internacionalização de um campo

## Quando NÃO usar

- ✗ Para mapear estrutura conceitual ou intelectual

## Passo a passo

1. Coletar metadados de autoria
2. Construir rede (nós = autores, arestas = coautoria)
3. Calcular métricas de rede (grau, betweenness, closeness)
4. Identificar comunidades (algoritmo de Louvain)
5. Visualizar e interpretar

## Ferramentas

VOSviewer, Gephi, UCINet, Bibliometrix.

## Critérios de qualidade

- Limiar mínimo de coautorias
- Cálculo de centralidades adequado
- Interpretação social dos clusters

## Armadilhas

- ⚠️ Inflar redes com autocitações
- ⚠️ Não desambiguar nomes
- ⚠️ Ignorar instituições e países como unidades complementares

## Exemplo

Rede de coautoria internacional em pesquisa de inovação em saúde, identificando 5 hubs principais (USA, UK, Brasil, China, Alemanha).

## Referência metodológica chave

Newman, M. E. J. (2001). The structure of scientific collaboration networks. Proceedings of the National Academy of Sciences, 98(2), 404–409.

---

*Material do curso MTPQI · Programa de Pós-Graduação em Administração · UNINOVE*