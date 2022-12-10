## Introdução

Casos de Uso são usados para representar um conjunto de ações que um sistema ou um conjunto de sistemas, deve realizar em colaboração com um ou mais usuários externos ao sistema. Cada caso de uso deverá fornecer algum resultado observável e com valor para outros interessados no sistema.

## Metodologia

Para elaborar dos casos de uso foram verificados e analisados os documentos de elicitação de requisitos. A partir disso, foram feitos os casos de uso utilizando a ferramenta Lucidchart.

## Casos de Uso & Especificação

### **UC01 - Fazer Login**

Primeiro Caso de Uso(<i>Figura 1</i>) que representa o subconjunto **Realizar login**, seguido da tabela de especificação(Tabela 1).

![Caso-Login](./assest/UC1-login.jpeg)

<figcaption align='center'>
 <h6> <b>Figura 1 – UC01</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>


| UC01                     | Fazer Login |Rastreabilidade|
| --------------           |:----------- |---------------|
| **Descrição**            | Fazer Login no Grasshopper |
| **Ator(es)**             | > Usuário <br> > Serviço de autenticação Google |
| **Pré condições**        | > Usuário estar deslogado no aplicativo |
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica no botão "Fazer login com o Google" <br> > Usuário escolhe a conta para continuar no Grasshopper <br> > Os dados de login são autenticados |OBS17<br>OBS02, ST06<br>OBS02, ST06<br>OBS02, ST06|
| **Fluxos alternativos**  | **Fluxo Alternativo 1 - Iniciar sem fazer login:** <br> > Usuário acessa o Grasshopper <br> > Usuário clica no botão "Iniciar sem fazer login" <br> > Usuário segue os passos e responde as perguntas de nivelamento <br> > O usuário é logado automaticamente |<br>OBS17<br>OBS01<br>ST11, BS05
|
| **Fluxos de exceção**    |  **Fluxo de Exceção 1 - Desconectado:** <br> > Aplicativo apresentar uma mensagem de erro avisando que não foi possível fazer o Login pois está sem conexão com a internet<br> <br> 
| **Pós condições**        | Usuário fica logado no Grasshopper e é direcionado para a aula tutorial|

<figcaption align='center'>
 <h6> <b>Tabela 1 – UC01</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>

### **UC02 - Realizar Aula**


Segundo Caso de Uso(<i>Figura 2</i>) que representa o subconjunto **Realziar Aulas**, seguido da tabela de especificação(Tabela 2).

![Caso-aulas](./assest/UC2-Realiza-aula.jpeg)

<figcaption align='center'>
 <h6> <b>Figura 2 – UC02</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>



| UC02                     | Aulas |Rastreabilidae|
| --------------           |:----------- |-----------|
| **Descrição**            | Usuário deve selecionar aula disponível e realizar a tarefa solicitada |
| **Ator(es)**             | > Usuário |
| **Pré condições**        | > Usuário deve ter finalizado a aula anterior do curso |
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica na aula disponível do curso escolhido <br> > Usuário clica no nome da aula <br> > E as tarefas solicitadas são listadas |BS17<br><br>ST12<br>ST03|
| **Fluxos alternativos**  | **Fluxos alternativos - Aula Opcional** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na aula disponível do curso escolhido <br> > Usuário clica no nome da aula <br> > O Grasshopper libera duas aulas em sequência (aula opcional) |<br>BS17<br>OBS10, ST08
| **Fluxos de exceção**    | --- |
| **Pós condições**        | Usuário pode sair da aula e finalizar tarefa depois |

<figcaption align='center'>
 <h6> <b>Tabela 2 – UC02</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>


### **UC03 - Menu de opções**

Terceiro Caso de Uso(<i>Figura 3</i>) que representa o subconjunto **Menu de opções**, seguido da tabela de especificação(Tabela 3).

![Caso-menu](./assest/UC03-Menu.jpeg)

<figcaption align='center'>
 <h6> <b>Figura 3 – UC03</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>

| UC03                     | Menu de opções| Rastreabilidade|
| --------------           |:----------- | --------|
| **Descrição**            | Usuário deve selecionar a barra lateral para acessar o menu de opções  |
| **Ator(es)**             | > Usuário |
| **Pré condições**        | > Usuário deve ter finalizado a aula tutorial, logo após ter respondido  o nivelamento|
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo  <br> > Usuário clica sobre o cursos desejado <br> > E realiza as tarefas da aula |BS17<br>OBS33<br>OBS08<br>ST03
| **Fluxos alternativos**  | **Fluxo alternativos 1 - Personalizar mascote** <br> > Usuário acessa o Grasshopper   <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica no mascote do Grasshopper <br> > O Usuário escolhe um adereço para o mascote <br> <br> **Fluxo alternativos 2 - Praticar no playground** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica na opção playground de código <br> > O Usuário faz práticas de javascript com mais liberdade, não se limitando a uma tarefa específica. |<br>BS17<br>OBS33<br>OBS06<br>OBS07, BS09<br><br><br>BS17<br>OBS33<br><br>BS07|
| **Fluxos de exceção**    | --- |
| **Pós condições**        | Usuário volta para tela do curso |

<figcaption align='center'>
 <h6> <b>Tabela 3 – UC03</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>


### **UC04 - Configurações**

Quarto Caso de Uso(<i>Figura 4</i>) que representa o subconjunto **Configurações**, seguido da tabela de especificação(Tabela 4).

![Caso-config](./assest/UC04-Config.jpeg)

<figcaption align='center'>
 <h6> <b>Figura 4 – UC04</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>


| UC04                    | Configurações | Rastreabilidade|
| --------------           |:----------- |:---------------|
| **Descrição**            | Usuário deve selecionar a barra lateral para acessar o menu de opções para ir para as configurações do Grasshopper |
| **Ator(es)**             | > Usuário |
| **Pré condições**        | > Usuário deve ter finalizado a aula tutorial, logo após ter respondido o nivelamento|
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo  <br> > Usuário clica sobre em configurações <br> > Navega até Notificações de apps <br> > O usuário desativa as notificações e lembretes|OBS17<br>OBS33<br>BS25<br><br>OBS19
| **Fluxos alternativos**  | **Fluxo alternativos 1 - Troca de idioma** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica em configurações <br> > O Usuário escolhe o idioma de sua preferência<br> <br> **Fluxo alternativos 2 - Pesquisa demográfica** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica na opção de responder a pesquisa <br> > O Usuário responde o questionário.<br> > E enviar os resultados <br> <br> **Fluxo alternativos 3 - Enviar feedback** <br> > Usuário acessa o Grasshopper <br> > Usuário clica na barra lateral no canto superior esquerdo <br> > Usuário clica na opção de enviar feedback <br> > O Usuário escolhe uma nota de 0 a 10, sobre a probabilidade de recomenddar o Grasshooper para um amigo <br> > E envia o feedback |<br>OBS17<br>OBS33<br>BS25<br>OBS26<br><br><br>OBS17<br>OBS33<br><br><br><br><br><br>OBS17<br>OBS33<br>OBS23
| **Fluxos de exceção**    | --- |
| **Pós condições**        | As modificações feitas no menu de configuração são aplicadas |

<figcaption align='center'>
 <h6> <b>Tabela 4 – UC04</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>


### **UC05 - Conquistas**

Quinto Caso de Uso(<i>Figura 5</i>) que representa o subconjunto **Conquistas**, seguido da tabela de especificação(Tabela 5).

![Caso-conquista](./assest/UC05-conquistas.jpeg)

<figcaption align='center'>
 <h6> <b>Figura 5 – UC05</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>


| UC05                     | Conquistas |Rastreabilidade|
| --------------           |:----------- |-------------|
| **Descrição**            | Usuário irá ver a suas conquistas |
| **Ator(es)**             | > Usuário |
| **Pré condições**        | > Usuário deve ter completado no mínimo uma tarefa para conseguir visualizar|
| **Fluxo principal**      | > Usuário acessa o Grasshopper <br> > Usuário clica no icone de um troféu no canto superior direito <br> > E visualiza os conceitos desbloqueados <br> |
| **Fluxos alternativos**  | **Fluxo Alternativo 1 - Visualizar Sequência do dia:** <br> > Usuário acessa o Grasshopper <br> > Usuário clica no icone de um troféu no canto superior direito <br> > Seleciona Sequência do dia <br> > E visualiza tela com as datas e sequências <br>|<br>OBS17<br>OBS33<br>OBS30, BS04
| **Fluxos de exceção**    | --- |
| **Pós condições**        | Usuário irá ver as suas conquistas |

<figcaption align='center'>
 <h6> <b>Tabela 5 – UC05</b><br>
  Fonte: Philipe de Sousa</h6>
</figcaption>



## Referências
>SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 11;

>UML Use Case Diagrams. UML Diagrams. Disponível em:  https://www.uml-diagrams.org/use-case-diagrams.html. Acesso em: 08/12/2022.

## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 08/12/2022 | Início da página e casos de uso | Philipe de Sousa | -- |
| 1.1 | 08/12/2022 | Casos de uso correção | Philipe de Sousa | -- |  