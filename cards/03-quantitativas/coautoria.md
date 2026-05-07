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

## Exemplos publicados

### Exemplo 1

Newman, M. E. J. (2001). The structure of scientific collaboration networks. *Proceedings of the National Academy of Sciences*, 98(2), 404–409.

**Ranking:** Top journal científico geral

**Por que é exemplar:** Paper fundador da análise de redes de coautoria. Aplica métricas de network analysis (centralidade, small world) a redes de coautoria científica. Mais de 8 mil citações.

### Exemplo 2

Acedo, F. J., Barroso, C., Casanueva, C., & Galán, J. L. (2006). Co-authorship in management and organizational studies: An empirical and network analysis. *Journal of Management Studies*, 43(5), 957–983.

**Ranking:** ABS 4 · Qualis A1

**Por que é exemplar:** Aplicação canônica em management. Mostra a estrutura social do campo em JMS — quem colabora com quem, quais são os hubs. Modelo prático de network de coautoria com interpretação substantiva.

## Referência metodológica chave

Newman, M. E. J. (2001). The structure of scientific collaboration networks. Proceedings of the National Academy of Sciences, 98(2), 404–409.

---

*Material do curso MTPQI · Programa de Pós-Graduação em Administração · UNINOVE*