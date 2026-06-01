# Módulo 38 — Análise Descritiva II: Tabelas e Gráficos

**Aluna:** Alessandra Vaz Cardoso  
**Curso:** Profissão: Cientista de Dados — EBAC  
**Data de entrega:** 01 de junho de 2026  

---

## Sobre este módulo

Este módulo aprofunda as técnicas de **Análise Descritiva**, com foco na construção de **tabelas de frequência**, **tabelas cruzadas (crosstab)** e **gráficos variados** para comunicar padrões e insights presentes nos dados.

---

## Exercício — Parte 1

**Arquivo:** `M38_Exercicio_01_AlessandraVazCardoso.ipynb`  
**Dataset utilizado:** `tips` (gorjetas em restaurante) — disponível via `seaborn.load_dataset('tips')`

### Conteúdo abordado

| Seção | Tópico |
|-------|--------|
| 0 | Configuração do ambiente e bibliotecas |
| 1 | Carregamento e inspeção do dataset |
| 2 | Tabelas de frequência absolutas, relativas e acumuladas |
| 3 | Tabelas cruzadas (crosstab) e pivot tables |
| 4 | Estatísticas descritivas por grupo |
| 5.1 | Gráfico de barras — atendimentos por dia |
| 5.2 | Gráfico de pizza — distribuição por sexo |
| 5.3 | Histogramas — conta total e gorjeta |
| 5.4 | Boxplot — gorjeta por dia e período |
| 5.5 | Dispersão — conta × gorjeta (com correlação) |
| 5.6 | Barras empilhadas — fumantes por dia |
| 5.7 | Heatmap — gorjeta média por dia e período |
| 5.8 | Linhas — conta e gorjeta por tamanho do grupo |
| 6 | Análise do percentual de gorjeta (violin plot) |
| 7 | Resumo executivo e conclusões |

### Bibliotecas utilizadas

- `pandas` — manipulação de dados e tabelas
- `numpy` — cálculos numéricos
- `matplotlib` — visualizações base
- `seaborn` — visualizações estatísticas

---

## Como executar

1. Abra o arquivo `.ipynb` no **Google Colab** ou **Jupyter Notebook**
2. Execute todas as células em ordem (`Runtime > Run all` no Colab)
3. O dataset `tips` é carregado automaticamente via `seaborn.load_dataset('tips')` — não requer upload de arquivos
