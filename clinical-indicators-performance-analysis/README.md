# Clinical Indicators Performance Analysis

## Sobre o projeto

Este projeto foi desenvolvido para automatizar a análise de indicadores utilizados na área da saúde, permitindo avaliar o desempenho de diferentes especialidades clínicas por meio da comparação entre resultados observados e seus respectivos benchmarks.

O notebook substitui um processo manual realizado em planilhas, tornando a análise mais padronizada, reproduzível e escalável.

Embora tenha sido desenvolvido utilizando indicadores hospitalares, a metodologia pode ser aplicada em qualquer contexto que envolva acompanhamento de indicadores, comparação contra metas e monitoramento de desempenho.

---

## Problema

A base continha dezenas de indicadores distribuídos entre diferentes especialidades, apresentando características distintas, como:

- indicadores percentuais e absolutos;
- indicadores em que valores maiores representam melhor desempenho;
- indicadores em que valores menores representam melhor desempenho;
- benchmarks específicos para cada indicador;
- séries históricas de resultados.

Realizar essa avaliação manualmente dificultava a identificação de indicadores críticos e comprometia a padronização das análises.

---

## Solução desenvolvida

Foi construída uma rotina em Python para automatizar todo o processo de avaliação dos indicadores.

O notebook realiza as seguintes etapas:

1. Leitura da base de indicadores;
2. Limpeza e padronização dos dados;
3. Conversão de valores percentuais e absolutos;
4. Comparação entre resultado e benchmark considerando a direção clínica do indicador;
5. Classificação automática do desempenho;
6. Cálculo de score por indicador;
7. Cálculo da variação entre períodos;
8. Consolidação dos resultados;
9. Geração de visualizações para apoio à tomada de decisão.

---

## Principais análises produzidas

- Distribuição dos indicadores por classificação;
- Comparação entre resultados e benchmarks;
- Classificação automática dos indicadores;
- Cálculo de score de desempenho;
- Identificação de mudanças entre anos;
- Visualização gráfica dos resultados.

---

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- OpenPyXL

---

## Competências demonstradas

- Limpeza e transformação de dados
- Data Wrangling
- Análise de KPIs
- Benchmark Analysis
- Healthcare Analytics
- Business Intelligence
- Desenvolvimento de regras de negócio
- Visualização de dados
- Automação de análises

---

## Estrutura do projeto

```text
clinical-indicators-performance-analysis/
│
├── README.md
├── clinical-indicators-performance-analysis.ipynb
```

---

## Confidencialidade

Os dados utilizados originalmente pertencem a um ambiente corporativo e foram removidos deste repositório.

Este projeto preserva exclusivamente a metodologia, a estrutura analítica e as regras de negócio desenvolvidas, sem expor informações institucionais.

---

## Possíveis aplicações

A metodologia pode ser adaptada para diferentes cenários, incluindo:

- monitoramento de indicadores assistenciais;
- acompanhamento de KPIs corporativos;
- comparação entre resultados e metas;
- avaliação de desempenho organizacional;
- construção de dashboards gerenciais;
- suporte à tomada de decisão baseada em dados.

---

## Principais habilidades evidenciadas

Ao longo deste projeto foram aplicadas técnicas relacionadas a todo o ciclo de análise de dados:

- Importação e tratamento de bases em Excel;
- Padronização e limpeza de dados;
- Implementação de regras de negócio em Python;
- Manipulação de DataFrames com Pandas;
- Criação de funções reutilizáveis;
- Análise comparativa entre indicadores e benchmarks;
- Geração de métricas derivadas;
- Construção de visualizações para comunicação dos resultados.

Essas atividades representam um fluxo completo de análise de dados aplicado a um problema real de acompanhamento de indicadores.
