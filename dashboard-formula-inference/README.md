# Dashboard Formula Inference

## Sobre o projeto

Este projeto foi desenvolvido para identificar automaticamente quais indicadores provavelmente compõem os cálculos apresentados em um dashboard por meio de uma abordagem de engenharia reversa.

A solução automatiza um processo que, originalmente, exigia inúmeras tentativas manuais para descobrir quais indicadores eram utilizados como numerador e denominador de cada métrica apresentada.

Embora tenha sido desenvolvido utilizando indicadores da área da saúde, a metodologia pode ser aplicada a qualquer contexto em que seja necessário inferir fórmulas ou regras de cálculo a partir de resultados conhecidos.

---

## Problema

O dashboard disponibilizava apenas o resultado final dos indicadores, sem documentação sobre as fórmulas utilizadas.

Para compreender quais variáveis originavam cada métrica, seria necessário testar centenas ou milhares de combinações entre os indicadores disponíveis.

Realizar essa tarefa manualmente seria demorado, sujeito a erros e pouco escalável.

---

## Solução desenvolvida

Foi construída uma rotina em Python capaz de testar automaticamente todas as combinações possíveis entre os indicadores da base original.

O algoritmo realiza as seguintes etapas:

1. Leitura das planilhas contendo os indicadores e os resultados do dashboard;
2. Estruturação dos indicadores em memória utilizando um dicionário;
3. Geração de todas as combinações possíveis entre numeradores e denominadores;
4. Aplicação automática de multiplicadores quando necessário;
5. Cálculo da diferença entre o resultado obtido e o valor apresentado no dashboard;
6. Classificação das combinações de acordo com sua proximidade em relação ao valor esperado;
7. Exportação dos resultados para análise em Excel.

---

## Principais análises produzidas

- Identificação das combinações mais prováveis para cada indicador do dashboard;
- Ranking das melhores aproximações;
- Comparação entre valores calculados e valores observados;
- Classificação automática por nível de proximidade;
- Exportação dos resultados para Excel.

---

## Tecnologias utilizadas

- Python
- Pandas
- Itertools
- Regex
- OpenPyXL

---

## Competências demonstradas

- Engenharia reversa de indicadores
- Manipulação de dados com Pandas
- Algoritmos combinatórios
- Automação de processos
- Análise exploratória
- Business Intelligence
- Healthcare Analytics
- Desenvolvimento de ferramentas analíticas

---

## Estrutura do projeto

```text
dashboard-formula-inference/
│
├── README.md
├── dashboard-formula-inference.ipynb
└── images/
```

---

## Confidencialidade

Os dados utilizados no projeto original pertencem a um ambiente corporativo e foram removidos deste repositório.

Foram preservados apenas a metodologia, a lógica de implementação e a estrutura analítica da solução.

---

## Possíveis aplicações

A metodologia desenvolvida pode ser adaptada para diferentes cenários, como:

- engenharia reversa de indicadores;
- auditoria de dashboards;
- validação de regras de negócio;
- identificação de fórmulas não documentadas;
- conferência de indicadores estratégicos;
- análise de KPIs corporativos.
