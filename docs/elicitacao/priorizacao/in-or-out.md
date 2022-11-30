# In or Out

## 1. Introdução
<p align="justify">&emsp;&emsp;Dado que são elicitados vários requisitos, para saber por onde começar o desenvolvimento, torna-se necessário priorizar esses requisitos.</p>

<p align="justify">&emsp;&emsp;Dessa forma, nessa seção a técnica utilizada para a priorização dos requisitos é a In or Out.</p>

## 2. Metodologia
<p align="justify">&emsp;&emsp;Essa técnica pode ser considerada uma das mais simples, uma vez que consiste em fazer uma escolha binária para cada um dos requisitos In (dentro) ou Out (fora), representando se ele deveria ser implementado nessa release do projeto ou não, respectivamente. Dessa forma, ao percorrer do desenvolvimento do projeto, pode-se voltar na lista e trabalhar com os requisitos que inicialmente foram escolhidos como Out, a fim de decidir se devem ser implementados na próxima etapa.</p>

<p align="justify">&emsp;&emsp;A partir disso, o integrante do grupo Caio Vitor se reuniu com um usuário do GrassHopper não integrante da equipe e pediu/guiou a realização da técnica. O nome desse usuário externo é Pedro Henrique,20 anos e cursa Engenharia de Software.</p>


# Requisitos Funcionais

|     ID     |                                                         Requisito                                                         |  Técnica  | Prioridade |
| :--------: | :-----------------------------------------------------------------------------------------------------------------------: |:---------:| :--------: |
| ST01 |Eu, como usuário, gostaria de definir meus horários de estudo, para poder se encaixar em meu horário de trabalho |storytelling|in|
| ST02 |Eu, como usuário, gostaria de realizar tarefas focadas em lógica, para aprender o que nescessito mais rápido |storytelling|in|
| ST03 |Eu, como usuário, gostaria de navegar entre as tarefas, para poder buscar as relevantes para mim |storytelling|in|
| ST04 |Eu, como usuário, gostaria de realizar tarefas relacionadas a cálculos matemáticos, para poder aplicar em meu dia a dia |storytelling|out|
| ST05 |Eu, como usuário, gostaria de logar na aplicação com minha conta da Google, para facilitar meu login |storytelling|in|
| ST06 |Eu, como usuário, gostaria de ter um sistema para treinar meus conhecimentos, para aperfeiçoar meu conhecimento |storytelling|in|
| ST07 |Eu, como usuário, gostaria de definir o nível de dificuldade das minhas tarefas, para nivelar com meu conhecimento |storytelling|in|
| ST08 |Eu, como usuário, gostaria de acompanhar meu avanço, para ter noção de como estou indo nos estudos |storytelling|in|
| BS01 |              O usuário deve poder personalizar seu ambiente.              |brainstorm|out|
| BS02 |           O usuário deve poder acessar o seu progresso no jogo.           |brainstorm|in|
| BS03 |              O usuário deve poder acessar seu nível no jogo.              |brainstorm|in|
| BS04 |                 O usuário deve poder ver suas conquistas.                 |brainstorm|in|
| BS05 |        O usuário deve poder escolher a dificuldade de suas lições.        |brainstorm|in|
| BS06 |       O usuário deve poder determinar metas diárias a ser comprida.       |brainstorm|in|
| BS07 |        O usuário deve poder escolher a atividade que deseja fazer.        |brainstorm|in|
| BS08 |  O usuário deve poder ver seus erros nas atividades e tentar refaze-las.  |brainstorm|in|
| BS09 |               O usuário deve poder personalizar o mascote.                |brainstorm|out|
| BS10 |     O usuário deve poder adicionar amigos que utilizam a plataforma.      |brainstorm|in|
| BS11 | O usuário deve poder ver o ranque de usuários com mais frequencia do app. |brainstorm|in|
| BS12 |                O usuário deve poder criar uma comunidade.                 |brainstorm|out|
| BS13 |                O usuário deve poder fazer lições rápidas.                 |brainstorm|in|
| BS14 |            O usuário deve poder ver o funcionamento do código.            |brainstorm|in|
| BS15 |             O usuário deve poder fazer atividades de revisão.             |brainstorm|in|
| BS16 |       O usuário deve poder pedir dicas nos exercicios que desejar.        |brainstorm|in|
| BS17 |          O usuário deve poder se cadastrar ou logar no sistema.           |brainstorm|in|
| OBS01 | Deve ser possível utilizar o app normalmente sem efetuar login |observacao|in|
| OBS02 | Deve ser possível efetuar login com Google |observacao|in|
| OBS03 | Deve ser possível visualizar nível e avanço em Painel de Controle |observacao|in|
| OBS04 | Deve ser possível visualizar selos conquitados em Painel de Controle |observacao|in|
| OBS05 | Deve ser possível visualizar conceitos aprendidos em Painel de Controle |observacao|in|
| OBS06 | Deve ser possível visualizar adereços do mascote (chapéu, bolsas, acessórios e calçados) |observacao|out|
| OBS07 | Deve ser possível mudar adereços do mascote |observacao|out|
| OBS08 | Deve ser possível visualizar os cursos no menu de navegação |observacao|in|
| OBS09 | Deve ser possível navegar pelos cursos no menu de navegação |observacao|in|
| OBS10 | Deve ser possível visualizar a trilha/fluxo de atividades de um curso |observacao|in|
| OBS11 | Deve ser possível resolver as atividades de forma gameficada |observacao|in|
| OBS12 | Deve ser possível compartilhar uma atividade |observacao|in|
| OBS13 | Deve ser possível criar snippet de código em Playground de Código |observacao|in|
| OBS14 | Deve ser possível visualizar desafios extras em Prática |observacao|in|
| OBS15 | Deve ser possível resolver desafios extras |observacao|out|
| OBS16 | Deve ser possível acessar fórum de suporte do app |observacao|in|
| OBS17 | Deve ser possível visualizar e acessar mensagens |observacao|in|
| OBS18 | Deve ser possível acessar o perfil do Twitter do app |observacao|out|
| OBS19 | Deve ser possível ativar e desativar recebimento de notificações |observacao|out|
| OBS20 | Deve ser possível receber lembretes por notifição push |observacao|out|
| OBS21 | Deve ser possível receber lembretes por e-mail |observacao|in|
| OBS22 | Deve ser possível configurar lembretes diários |observacao|in|
| OBS23 | Deve ser possível enviar feedback ao app |observacao|in|
| OBS24 | Deve ser possível relatar bug do app |observacao|in|
| OBS25 | Deve ser possível ativar e desativar efeitos sonoros |observacao|in|
| OBS26 | Deve ser possível configurar idioma (Português, Espanhol e Inglês) |observacao|in|
| OBS27 | Deve ser possível redefinir progresso de atividades |observacao|in|
| OBS28 | Deve ser possível sair da conta, caso esteja logada |observacao|in|
| OBS29 | Deve ser possível excluir conta, caso esteja logada |observacao|in|
| OBS30 | Deve ser possível visualizar conquistas (conceitos desbloqueados, teclas JavaScript usadas e sequência de programação do dia) |observacao|in|

## Requisitos Não Funcionais

|     ID     |                                                         Requisito                                                         |  Técnica  | Prioridade |
| :--------: | :-----------------------------------------------------------------------------------------------------------------------: |:---------:| :--------: |
| ST09 | Eu, como usuário, gostaria de aprender do zero como programar, para aprender a programar |storytelling|in|
| ST010 | Eu, como usuário, gostaria de aprender uma linguagem de programação, para poder me capacitar |storytelling|in|
| ST09 | Eu, como usuário, gostaria de ter uma trilha de ensinamentos para seguir, para ter um guia de estudos |storytelling|in|
| ST10 | Eu, como usuário, gostaria de um material de apoio, para ter mais conteúdos para estudar |Brainstorm e storytelling|in|
| ST11 | Eu, como usuário, gostaria de ter um passo a passo para realizar as tarefas, para aprender de forma fácil |Brainstorm e storytelling|in|
| ST12 | Eu, como usuário, gostaria de aprender sobre as bibliotecas da linguagem, para aumentar o escopo dos meus conhecimentos |storytelling|in|
| ST13 | Eu, como usuário, gostaria de ter ensino gratuito, para ser mais acessível as minhas condições |storytelling|in|
| BS18 |  A cada nível que o usuário avançar, as fases devem aumentar a dificuldade.   |Brainstorm|in|
| BS20 |               O sistema deve ter a opção de conectar com Anki.                |Brainstorm|in|
| BS22 |                   O sistema deve conter videos de auxilio.                    |Brainstorm|in|
| BS23 | O sistema deve conter um portal com noticias de ti e oportunidade de emprego. |Brainstorm|in|
| BS24 |      O sistema deve conter a opção de traduzir o nome de uma estrutura.       |Brainstorm|in|
| BS25 | O sistema deve conter um painel de controle para configuração do aplicativo.  |Brainstorm|in|
| BS26 |               O sistema deve mandar notificações de uso do app.               |Brainstorm|out|
| BS27 |             O sistema deve conter uma ferramenta de nívelamento.              |Brainstorm|in|
| BS28 |            O sistema deve conter atividades baseadas no cotidiano.            |Brainstorm|in|
| OBS31 | A inteface deve ser responsiva |Brainstorm|in|
| OBS32 | O app deve estar disponível para sistemas Android e iOS |Brainstorm|in|
| OBS33 | Deve conter menu de navegação |Brainstorm|in|
| OBS34 | O app deve ser gameficado |Brainstorm|in|
| OBS35 | O sistema deve garantir segurança dos dados do usuário |Brainstorm|in|

## Gravação
<iframe width="560" height="315" src="https://www.youtube.com/embed/FktdLE6fQ94?start=3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Histórico de versão

| Versão |    Data    |                                 Descrição                                 |          Autor           |     Revisor      |
| :----: | :--------: | :-----------------------------------------------------------------------: | :----------------------: | :--------------: |
|  1.0   | 29/11/2022 |   Conceito de priorização ir or out e construção das tabelas   | Caio, João, Hellen    |  Wildemberg Sales    |

