# Especificação Suplementar - Lichess

## Introdução

<p style="text-align: justify;">Este documento tem como objetivo verificar o artefato de <a href= https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/especificacao_suplementar/ target="_blank">Especificação Suplementar</a> para detectar os erros e defeitos antes de finalizar o projeto. Para a especificação suplementar, será analisado a forma como foram levantados e documentados os requisitos não funcionais de usabilidade, confiabilidade, desempenho e suportabilidade(FURPS+). Foi utilizado o Checklist para fazer essa verificação o que facilita a identificação de erros. Checklist é básicamente um conjunto de perguntas ou afirmações sobre determinada circunstância ao qual se deseja verificar, dependendo da sua finalidade e objetivo.</p>

## Verificações gerais

<p align="justify">A <i>Tabela 1</i> a seguir descreve os critérios gerais, ou seja, que todos os artefatos desenvolvidos devem estar de acordo.</p>
 
| ID | Verificação | Resposta | Observação |
| :--: | :-------: | :------: | :------------: |
| 1 | Contém um texto fazendo introdução ao artefato? | ✔ |  |
| 2 | Os textos estão ortograficamente corretos? | ✔ |  |
| 3 | Os textos estão em formato justificado?<br><i>&lt;p align="justify"&gt;&lt;/p&gt;</i> | ✖ |  |
| 4 | As tabelas e/ou figuras contém legenda (título e fonte)? |  | Não possuem tabelas ou figuras. |
| 5 | As legendas das figuras e tabelas estão conforme padrão?<br><i>&lt;figcaption align="center"&gt;&lt;/figcaption&gt;</i> |  | Não possuem tabelas ou figuras. |
| 6 | As tabelas e/ou figuras são chamadas dentro dos textos? |  |  Não possuem tabelas ou figuras.|
| 7 | As seções seguem uma hierarquia de títulos correta? | ✔ |  |
| 8 | Possui um histórico de versão conforme o padrão? | ✔ |  |
| 9 | As versões do histórico seguem a partir do 1.0? | ✔ |  |
| 10 | Contém o(s) autor(es) do artefato no histórico de versão? | ✔ |  |
| 11 | Contém o revisor do artefato no histórico de versão? | ✔ |  |
<figcaption align="center">Tabela 1: Critérios gerais da página. (Fonte: Autores, 2022)</figcaption>

## Verificações específicas

<p align="justify">A <i>Tabela 2</i> a seguir descreve os critérios específicos do artefato de Backlog do produto e informa se está de acordo com o esperado.</p>

| ID  |                                          Verificação                                           | Resposta |     Observações     |
| :-: | :--------------------------------------------------------------------------------------------: | :------: | :-----------------: |
| 01  |                                O documento possui padronização?                                |    ✔     |                     |
| 02  |                          O documento possui Linkagem e versionamento?                          |    ✔     |                     |
| 03  |                           O documento é orientado pelo padrão FURPS?                           |    ✔     |                     |
| 04  |                 O documento aborda sobre a estética e o design na Usabilidade?                 |    ✔     |                     |
| 05  |       O documento aborda e especifíca sobre a facilidade de memorização na usabilidade?        |    ✔     |                     |
| 06  |               O documento aborda e especifíca sobre a eficiência na usabilidade?               |    ✔     |                     |
| 07  |               O documento aborda e especifíca sobre a Satisfação na Usabilidade?               |    ✔     |                     |
| 08  |           O documento aborda e especifíca sobre a disponibilidade na Confiabilidade?           |    ✔     |                     |
| 09  |         O documento aborda e especifíca sobre a Segurança a falhas na Confiabilidade ?         |    ✔     |                     |
| 10  | O documento aborda e especifíca sobre a segurança no armazenamento de dados na confiabilidade? |    ✖     | Não foi encontrado. |
| 11  |                O documento aborda e especifíca a maturidade na Confiabilidade?                 |    ✖     | Não foi encontrado. |
| 12  |              O documento aborda e especifíca a rapidez na resposta no Desempenho?              |    ✔     |                     |
| 13  |                 O documento aborda e especifíca o Armazenamento no Desempenho?                 |    ✖     | Não foi encontrado. |
| 14  |          O documento aborda e especifíca sobre a compatibilidade na Suportabilidade ?          |    ✔     |                     |
| 15  |           O documento aborda e especifíca sobre a escalabilidade na Suportabilidade?           |    ✔     |                     |
| 16  |     O documento aborda e especifíca sobre o termo de uso nos Requisitos de licenciamento?      |    ✖     | Não foi encontrado. |
| 17  |  O documento aborda e especifíca sobre o termo de privacidade os Requisitos de licenciamento?  |    ✖     | Não foi encontrado. |

<figcaption align="center">Tabela 2: Critérios específicos do artefato. (Fonte: Autores, 2022)</figcaption>

## Conclusão

<p style="text-align: justify;">Foi possivel identificar que os tópicos com o ID de número: 10, 11, 13, 16, 17 não foram abordados e especificados nas documentações. Sendo assim necessário a implementação desses tópicos. </p>

## Referência

> SERRANO, Maurício; SERRANO, Milene. Requisitos - Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de versão

| Versão |    Data    |                Descrição                 |      Autor      | Revisor |
| :----: | :--------: | :--------------------------------------: | :-------------: | :-----: |
|  1.0   | 08/01/2023 | Criação e desenvolvimento da verificação | Hellen Fernanda | Philipe |
