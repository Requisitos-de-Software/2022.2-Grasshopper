## Introdução

Casos de Uso são usados para representar um conjunto de ações que um sistema ou um conjunto de sistemas, deve realizar em colaboração com um ou mais usuários externos ao sistema. Cada caso de uso deverá fornecer algum resultado observável e com valor para outros interessados no sistema.

## Metodologia

Para elaborar dos casos de uso foram verificados e analisados os documentos de elicitação de requisitos. A partir disso, foram feitos os casos de uso utilizando a ferramenta Lucidchart.

## Casos de Uso & Especificação

### **UC01 - Fazer Login**

![Caso-Login](./assest/UC1-login.jpeg)

| UC01                     | Fazer Login |
| --------------           |:----------- |
| **Descrição**            | Fazer Login no Grasshopper |
| **Ator(es)**             | > Usuário <br> > Serviço de autenticação Google |
| **Pré condições**        | > Usuário estar deslogado no aplicativo |
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica no botão "Fazer login com o Google" <br> > Usuário escolhe a conta para continuar no Grasshopper <br> > Os dados de login são autenticados |
| **Fluxos alternativos**  | **Fluxo Alternativo 1 - Iniciar sem fazer login:** <br> > Usuário acessa o Grasshopper <br> > Usuário clica no botão "Iniciar sem fazer login" <br> > Usuário segue os passos e responde as perguntas de nivelamento <br> > O usuário é logado automaticamente |
| **Fluxos de exceção**    |  **Fluxo de Exceção 1 - Desconectado:** <br> > Aplicativo apresentar uma mensagem de erro avisando que não foi possível fazer o Login pois está sem conexão com a internet<br> <br> 
| **Pós condições**        | Usuário fica logado no Grasshopper e é direcionado para a aula tutorial|

### **UC02 - Realizar Aula**

![Caso-aulas](./assest/UC2-Realiza-aula.jpeg)

| UC02                     | Aulas |
| --------------           |:----------- |
| **Descrição**            | Usuário deve selecionar aula disponível e realizar a tarefa solicitada |
| **Ator(es)**             | > Usuário |
| **Pré condições**        | > Usuário deve ter finalizado a aula anterior do curso |
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica na aula disponível do curso escolhido <br> > Usuário clica no nome da aula <br> > E as tarefas solicitadas são listadas |
| **Fluxos alternativos**  | **Fluxos alternativos - Aula Opcional** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na aula disponível do curso escolhido <br> > Usuário clica no nome da aula <br> > O Grasshopper libera duas aulas em sequência (aula opcional) |
| **Fluxos de exceção**    | --- |
| **Pós condições**        | Usuário pode sair da aula e finalizar tarefa depois |

### **UC03 - Menu de opções**

![Caso-menu](./assest/UC03-Menu.jpeg)

| UC03                     | Aulas |
| --------------           |:----------- |
| **Descrição**            | Usuário deve selecionar a barra lateral para acessar o menu de opções  |
| **Ator(es)**             | > Usuário |
| **Pré condições**        | > Usuário deve ter finalizado a aula tutorial, logo após ter respondido  o nivelamento|
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo  <br> > Usuário clica sobre o cursos desejado <br> > E realiza as tarefas da aula |
| **Fluxos alternativos**  | **Fluxo alternativos 1 - Personalizar mascote** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica no mascote do Grasshopper <br> > O Usuário escolhe um adereço para o mascote <br> <br> **Fluxo alternativos 2 - Praticar no playground** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica na opção playground de código <br> > O Usuário faz práticas de javascript com mais liberdade, não se limitando a uma tarefa específica. |
| **Fluxos de exceção**    | --- |
| **Pós condições**        | Usuário volta para tela do curso |

### **UC04 - Menu de opções**

![Caso-config](./assest/UC04-Config.jpeg)

| UC04                    | Aulas |
| --------------           |:----------- |
| **Descrição**            | Usuário deve selecionar a barra lateral para acessar o menu de opções para ir para as configurações do Grasshopper |
| **Ator(es)**             | > Usuário |
| **Pré condições**        | > Usuário deve ter finalizado a aula tutorial, logo após ter respondido o nivelamento|
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo  <br> > Usuário clica sobre em configurações <br> > Navega até Notificações de apps <br> > O usuário desativa as notificações e lembretes|
| **Fluxos alternativos**  | **Fluxo alternativos 1 - Troca de idioma** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica em configurações <br> > O Usuário escolhe o idioma de sua preferência<br> <br> **Fluxo alternativos 2 - Pesquisa demográfica** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica na opção de responder a pesquisa <br> > O Usuário responde o questionário.<br> > E enviar os resultados <br> <br> **Fluxo alternativos 3 - Enviar feedback** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica na opção de enviar feedback <br> > O Usuário escolhe uma nota de 0 a 10, sobre a probabilidade de recomenddar o Grasshooper para um amigo <br> > E envia o feedback |
| **Fluxos de exceção**    | --- |
| **Pós condições**        | As modificações feitas no menu de configuração são aplicadas |

### **UC05 - Conquistas**

![Caso-conquista](./assest/UC05-conquistas.jpeg)

| UC05                     | Conquistas|
| --------------           |:----------- |
| **Descrição**            | Usuário irá ver a suas conquistas |
| **Ator(es)**             | > Usuário |
| **Pré condições**        | > Usuário deve ter completado no mínimo uma tarefa para conseguir visualizar|
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica no icone de um troféu no canto superior direito <br> > E visualiza os conceitos desbloqueados <br> |
| **Fluxos alternativos**  | **Fluxo Alternativo 1 - Visualizar Sequência do dia:** <br> > Usuário acessa o Grasshopper <br> > Usuário clica no icone de um troféu no canto superior direito <br> > Seleciona Sequência do dia <br> > E visualiza tela com as datas e sequências <br>|
| **Fluxos de exceção**    | --- |
| **Pós condições**        | Usuário irá ver as suas conquistas |


## Referências
>SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 11;

>UML Use Case Diagrams. UML Diagrams. Disponível em:  https://www.uml-diagrams.org/use-case-diagrams.html. Acesso em: 08/12/2022.

## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 08/12/2022 | Início da página e casos de uso | Philipe de Sousa | -- | 