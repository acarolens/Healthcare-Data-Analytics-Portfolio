# REDCap Survey Generator

## Sobre o projeto

Este projeto foi desenvolvido para automatizar a criação de planilhas de importação para o REDCap a partir de uma lista de indicadores.

A solução elimina a necessidade de cadastrar manualmente cada pergunta do formulário, reduzindo significativamente o tempo necessário para configuração de pesquisas e minimizando erros de digitação ou inconsistências na nomenclatura das variáveis.

Embora tenha sido desenvolvido para indicadores hospitalares, a metodologia pode ser aplicada a qualquer projeto que utilize o REDCap como plataforma de coleta de dados.

---

## Problema

Durante a construção de formulários no REDCap, cada indicador precisava ser cadastrado manualmente juntamente com perguntas auxiliares utilizadas no acompanhamento de planos de ação.

Além de repetitivo, esse processo era demorado e aumentava a possibilidade de erros humanos.

---

## Solução desenvolvida

Foi criada uma rotina em Python capaz de gerar automaticamente toda a estrutura necessária para importação no REDCap.

O notebook realiza as seguintes etapas:

1. Leitura da planilha contendo os indicadores;
2. Conversão automática dos nomes dos indicadores para variáveis compatíveis com o REDCap;
3. Geração das perguntas principais;
4. Geração automática das perguntas de acompanhamento;
5. Tratamento de variáveis duplicadas;
6. Exportação da planilha pronta para importação.

---

## Funcionalidades

- Geração automática de variáveis;
- Padronização da nomenclatura;
- Tratamento de indicadores duplicados;
- Criação automática de perguntas relacionadas ao plano de ação;
- Exportação em formato Excel.

---

## Tecnologias utilizadas

- Python
- Pandas
- Regex
- OpenPyXL

---

## Competências demonstradas

- Automação de processos
- Manipulação de dados
- Desenvolvimento de ferramentas internas
- Processamento de texto
- Integração com REDCap
- Data Quality
- Healthcare Analytics

---

## Estrutura do projeto

```text
redcap-survey-generator/
│
├── README.md
├── redcap-survey-generator.ipynb
```

---

## Confidencialidade

Os dados utilizados originalmente pertencem a um ambiente corporativo e foram removidos deste repositório.

Este projeto preserva apenas a lógica de implementação, permitindo demonstrar a metodologia utilizada sem expor informações institucionais.

---

## Possíveis aplicações

A metodologia pode ser aplicada em diversos cenários, incluindo:

- criação automática de formulários REDCap;
- geração de dicionários de dados;
- padronização de pesquisas clínicas;
- automação de cadastros repetitivos;
- preparação de estudos observacionais;
- apoio à gestão de indicadores assistenciais.
