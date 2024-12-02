# Projeto TSE - Coleta, Preparação e Análise de Dados

Este repositório contém o código e os notebooks utilizados para a coleta, preparação e análise dos dados eleitorais do Tribunal Superior Eleitoral (TSE). O objetivo do trabalho é analisar o desempenho eleitoral de candidatos ao longo dos anos, com ênfase em variáveis como sexo, grau de instrução e raça.

## Descrição do Trabalho

Este trabalho foi desenvolvido no contexto da disciplina "Coleta, Preparação e Análise de Dados", do Prof. Luan Garcia. O projeto tem como foco a utilização de dados abertos fornecidos pelo TSE para investigar tendências e padrões eleitorais no Brasil.

A questão de pesquisa central é: **Como se deu a distribuição do número de candidatos ao longo dos anos, por grau de instrução e sexo?** A análise foi realizada com base nos dados de candidaturas, incluindo variáveis como grau de instrução, sexo, e outras características demográficas dos candidatos.

## Metodologia CRISP-DM

O trabalho seguiu a metodologia CRISP-DM (Cross-Industry Standard Process for Data Mining), com ênfase nas seguintes etapas:
1. **Data Understanding**: Compreensão dos dados disponíveis e formulação da questão de pesquisa.
2. **Data Preparation**: Preparação dos dados para análise, incluindo limpeza, transformação e integração dos datasets.

## Dados Utilizados

Os dados foram coletados do portal de dados abertos do TSE, disponível [aqui](https://dadosabertos.tse.jus.br/). A principal base de dados utilizada foi a **CONSULTA_CAND**, que contém informações sobre candidatos em diversas eleições, e a **CONSULTA_CAND_COMPLEMENTAR**, que fornece dados adicionais sobre os candidatos.

### Principais Atributos:
- `NM_CANDIDATO`: Nome do candidato
- `NR_CANDIDATO`: Número na urna
- `SG_UF`: Estado
- `SG_PARTIDO`: Partido político
- `CD_GENERO` e `DS_GENERO`: Gênero do candidato
- `CD_COR_RACA` e `DS_COR_RACA`: Raça/Cor do candidato
- `CD_GRAU_INSTRUCAO` e `DS_GRAU_INSTRUCAO`: Grau de instrução
- `NR_IDADE_DATA_POSSE`: Idade do candidato na data da posse

## Análise Realizada

Foram realizadas análises sobre a evolução do número de candidatos em diferentes eleições, segmentados por grau de instrução e sexo. As principais descobertas incluem:
- O aumento no número de candidaturas femininas ao longo dos anos, com uma leve queda em 2024.
- A redução de candidatos com grau de instrução fundamental completo, enquanto aumentou o número de candidatos com grau de instrução médio e superior.

## Dashboards

O painel interativo com as visualizações criadas para este trabalho está disponível no Tableau:
- [Dashboard - Perfil dos Candidatos ao Longo das Eleições](https://public.tableau.com/app/profile/gabriel.zurawski/viz/PerfildosCadidatosaoLongodasEleies/Painel1?p)
