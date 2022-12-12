# Cenários

## Introdução

<p align="justify">No contexto do desenvolvimento de sistemas, usualmente esta interação se dá entre o sistema em desenvolvimento e os atores externos, que podem ser usuários ou outros sistemas. Segundo Carroll, a propriedade que melhor define um cenário é o fato do mesmo projetar uma descrição concreta de uma atividade em que o usuário se engaja no momento em que está realizando uma tarefa específica. Cenários têm sido amplamente utilizados no processo de elicitação dos requisitos de sistemas de software. Neste contexto, cenários são utilizados para descrever as situações de uso do sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos. </p>

## Metodologia

<p align="justify">Para a construção dos cenários foi utilizado o formato descrito na <i>Tabela 1</i>.</p>

**Título: identifica o cenário.**

| Item      | Descrição                                                                                                              |
| --------- | ---------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Estabelece a finalidade de um cenário. O cenário deve descrever de que modo este objetivo deve ser alcançado.          |
| Contexto  | Descreve o estado inicial de um cenário, suas précondições, o local (físico) e tempo.                                  |
| Atores    | Pessoas ou estruturas organizacionais que tem um papel no cenário.                                                     |
| Recursos  | Identifica os objetos passivos com os quais lidam os atores.                                                           |
| Episódios | Cada episódio representa uma ação realizada por um ator onde participam outros atores utilizando recursos disponíveis. |
| Exceção   | É o tratamento para uma situação excepcional ou de erro.                                                               |

<figcaption align="center">Tabela 1: Descrição dos itens dos cenários (Fonte: Autores, 2022).</figcaption>

## Cenários

<p align="justify">As tabelas a seguir referem-se aos cenários desenvolvidos a partir de alguns requisitos funcionais priorizados como "Requisitos de Alta Prioridade", na priorização da Three Level-Scale.</p>

### C01 - Efetuar login/cadastro com Google

| Item      | Descrição                                                                                                                                                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Utilizar uma conta Google para fazer login/cadastro                                                                                                                                                                                                                               |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado, possuir conta no Google/Gmail.                                                                                                                                            |
| Atores    | Usuário                                                                                                                                                                                                                                                                           |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                      |
| Episódios | Usuário está em horário livre<br>Usuário quer aprender programação<br>Usuário pega o celular<br>Usuário instala o Grasshopper<br>Usuário abre o aplicativo<br>Usuário clica em entrar com Google<br>Usuário informa o e-mail<br>Usuário digita a senha<br>Usuário clica em entrar |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário esqueceu o e-mail<br>Usuário esqueceu a senha                                                                                                               |

<figcaption align="center">Tabela 2: Cenário 1 (Fonte: Autores, 2022).</figcaption>

---

### C02 - Navegar pelos cursos no menu de navegação

| Item      | Descrição                                                                                                                                                                                                                                                          |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Objetivo  | Utilizar o menu de navegação para navegar pelos cursos                                                                                                                                                                                                             |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                             |
| Atores    | Usuário                                                                                                                                                                                                                                                            |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                       |
| Episódios | Usuário está em horário livre<br>Usuário quer aprender programação<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário visualiza e escolhe o curso que deseja, dentre os disponíveis |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu                                                                      |

<figcaption align="center">Tabela 3: Cenário 2 (Fonte: Autores, 2022).</figcaption>

---

### C03 - Acessar fórum de suporte do app

| Item      | Descrição                                                                                                                                                                                                                                                                                                          |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Objetivo  | Entrar no fórum de suporte pelo aplicativo                                                                                                                                                                                                                                                                         |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                           |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                            |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                       |
| Episódios | Usuário está em horário livre<br>Usuário está com alguma dificuldade na utilização do app<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário encontra e clica em "Fórum de suporte"<br>Usuário é redirecionado para o site do fórum |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra o link para "Fórum de suporte"                                                               |

<figcaption align="center">Tabela 4: Cenário 3 (Fonte: Autores, 2022).</figcaption>

---

### C04 - Ativar e/ou desativar recebimento de notificações

| Item      | Descrição                                                                                                                                                                                                                                                                                                                                          |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Configurar recebimento de notificações do app                                                                                                                                                                                                                                                                                                      |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                                           |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                                            |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                                       |
| Episódios | Usuário está incomodado com o recebimento ou falta de recebimento de notificações<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário encontra e clica em "Configurações"<br>Usuário encontra e clica em "Notificações"<br>Usuário ativa ou desativa as notificações |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra o acesso às configurações<br>Usuário não encontra o acesso às notificações                                                   |

<figcaption align="center">Tabela 5: Cenário 4 (Fonte: Autores, 2022).</figcaption>

---

### C05 - Enviar feedback ao app

| Item      | Descrição                                                                                                                                                                                                                                                                                                                                      |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Enviar feedback sobre o app aos desenvolvedores                                                                                                                                                                                                                                                                                                |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                                         |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                                        |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                                   |
| Episódios | Usuário está safisteifo e contente com o app<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário encontra e clica em "Enviar feedback"<br>Usuário é redirecionado para página de envio de feedback<br>Usuário relata suas satisfações e/ou insatisfações com app |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra o acesso ao botão de enviar feedback                                                                                     |

<figcaption align="center">Tabela 6: Cenário 5 (Fonte: Autores, 2022).</figcaption>

---

### C06 - Relatar bug do app

| Item      | Descrição                                                                                                                                                                                                                                                                                                         |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Enviar descrição de bug do aplicativo                                                                                                                                                                                                                                                                             |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                            |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                           |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                      |
| Episódios | Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário identifica uma irregularidade na aplicação<br>Usuário clica no ícone de menu<br>Usuário encontra e clica em "Configurações"<br>Usuário encontra e clica em "Relatar um bug"<br>Usuário descreve o bug detalhadamente |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra o acesso às configurações<br>Usuário não encontra o local para relatar um bug               |

<figcaption align="center">Tabela 7: Cenário 6 (Fonte: Autores, 2022).</figcaption>

---

### C07 - Configurar idioma

| Item      | Descrição                                                                                                                                                                                                                                                                                                                                                                                       |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Configurar o idioma desejado pelo usuário                                                                                                                                                                                                                                                                                                                                                       |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                                                                                        |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                                                                                         |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                                                                                    |
| Episódios | Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário está insatisfeito com o idioma padrão do app<br>Usuário clica no ícone de menu<br>Usuário encontra e clica em "Configurações"<br>Usuário encontra e clica para configurar idioma<br>Usuário escolhe o idioma que deseja utilizar, entre português, inglês e espanhol<br>Usuário seleciona o idioma |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra o acesso às configurações<br>Usuário não encontra local para configurar idioma                                                                                            |

<figcaption align="center">Tabela 8: Cenário 7 (Fonte: Autores, 2022).</figcaption>

---

### C08 - Sair da conta

| Item      | Descrição                                                                                                                                                                                                                                                                                |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Fazer logout da conta logada                                                                                                                                                                                                                                                             |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                   |
| Atores    | Usuário                                                                                                                                                                                                                                                                                  |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                             |
| Episódios | Usuário deseja deslogar da conta vinculada ao app<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário encontra e clica em "Configurações"<br>Usuário encontra e clica em "Sair"<br>Usuário confirma a ação |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra o acesso às configurações<br>Usuário não encontra o botão de sair  |

<figcaption align="center">Tabela 9: Cenário 8 (Fonte: Autores, 2022).</figcaption>

---

### C09 - Excluir conta

| Item      | Descrição                                                                                                                                                                                                                                                                                                |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Desvincular a conta do aplicativo                                                                                                                                                                                                                                                                        |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                 |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                  |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                             |
| Episódios | Usuário desvincular por completo sua conta ao aplicativo<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário encontra e clica em "Configurações"<br>Usuário encontra e clica em "Excluir conta"<br>Usuário confirma a ação |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra o acesso às configurações<br>Usuário não encontra o botão de excluir conta         |

<figcaption align="center">Tabela 10: Cenário 9 (Fonte: Autores, 2022).</figcaption>

---

### C10 - Escolher a atividade que deseja fazer

| Item      | Descrição                                                                                                                                                                                                                                                                                                                                       |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Escolher atividade de um curso que deseja fazer, dentre as disponíveis                                                                                                                                                                                                                                                                          |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                                        |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                                         |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                                    |
| Episódios | Usuário está em horário livre<br>Usuário quer aprender programação<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário clica em um dos cursos disponíveis<br>Usuário escolhe e seleciona uma das atividades, dentre as disponíveis<br>Usuário desenvolve a tarefa |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário tem acesso à somente uma atividade de um curso até o momento                                                                           |

<figcaption align="center">Tabela 11: Cenário 10 (Fonte: Autores, 2022).</figcaption>

---

### C11 - Ver os erros cometidos e tentar refazer

| Item      | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Ver os erros cometidos na lição e poder refaze-las                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                                                                                                                                                                             |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Episódios | Usuário está em horário livre<br>Usuário quer aprender programação<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário clica em um dos cursos disponíveis<br>Usuário escolhe e seleciona uma das atividades, dentre as disponíveis<br>Usuário desenvolve a tarefa<br>Usuário comete um erro na tarefa<br>Usuário localiza o erro e entende o porque errou<br>Usuário decide se refaz ou não a tarefa |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não comete nenhum erro                                                                                                                                                                                                                                                    |

<figcaption align="center">Tabela 12: Cenário 11 (Fonte: Autores, 2022).</figcaption>

---

### C12 - Escolher lições rápidas

| Item      | Descrição                                                                                                                                                                                                                                                                                                                        |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Poder escolher lições menores do que o habitual                                                                                                                                                                                                                                                                                  |
| Contexto  | Local: em casa<br>Tempo: durante o dia<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                           |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                          |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                     |
| Episódios | Usuário está com pouco tempo<br>Usuário quer aprender programação<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário clica em um dos cursos disponíveis<br>Usuário escolhe e seleciona uma das atividades, dentre as atividades de lições rápidas |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não encontra as lições rápidas                                                                                          |

<figcaption align="center">Tabela 13: Cenário 12 (Fonte: Autores, 2022).</figcaption>

---

### C13 - Ver o código sendo executado

| Item      | Descrição                                                                                                                                                                                                                                                                                                                                                                                                           |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Ver o código sendo executado                                                                                                                                                                                                                                                                                                                                                                                        |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                                                                                                            |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                                                                                                             |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                                                                                                        |
| Episódios | Usuário está em horário livre<br>Usuário quer aprender programação<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário clica em um dos cursos disponíveis<br>Usuário escolhe e seleciona uma das atividades, dentre as disponíveis<br>Usuário desenvolve a tarefa<br>Usuário clica em um botão<br>Usuário ve o código sendo executado |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário comete algum erro<br>Usuário não encontra o botão de execução do código                                                                                                                                    |

<figcaption align="center">Tabela 14: Cenário 13 (Fonte: Autores, 2022).</figcaption>

---

### C14 - Pedir dicas

| Item      | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Pedir dicas para ajudar na resolução da tarefa                                                                                                                                                                                                                                                                                                                                                                                           |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                                                                                                                                 |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                                                                                                                             |
| Episódios | Usuário está em horário livre<br>Usuário quer aprender programação<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário clica em um dos cursos disponíveis<br>Usuário escolhe e seleciona uma das atividades, dentre as disponíveis<br>Usuário não consegue desenvolver a tarefa<br>Usuário clica em um botão<br>Usuário ve dicas de como resolver a tarefa |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário consegue fazer o código<br>Usuário não encontra o botão de dicas                                                                                                                                                                |

<figcaption align="center">Tabela 15: Cenário 14 (Fonte: Autores, 2022).</figcaption>

---

### C15 - Escolher nível de dificuldade

| Item      | Descrição                                                                                                                                                                                                                                                                                                                                                            |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo  | Escolher o nível de dificuldade das tarefas                                                                                                                                                                                                                                                                                                                          |
| Contexto  | Local: em casa<br>Tempo: durante a noite<br>Pré-condições: acesso à internet, ter o aplicativo instalado                                                                                                                                                                                                                                                             |
| Atores    | Usuário                                                                                                                                                                                                                                                                                                                                                              |
| Recursos  | Smartphone<br>Internet<br>Conta Google/Gmail                                                                                                                                                                                                                                                                                                                         |
| Episódios | Usuário está em horário livre<br>Usuário quer aprender programação<br>Usuário pega o celular<br>Usuário abre o aplicativo<br>Usuário entra em sua conta<br>Usuário clica no ícone de menu<br>Usuário clica em um dos cursos disponíveis<br>Usúario escolhe o nível de dificuldade da tarefa<br>Usuário escolhe e seleciona uma das atividades, dentre as disponíveis |
| Exceção   | Falta de energia<br>Smartphone descarregado<br>Smartphone é danificado de alguma forma<br>Perda de conexão com a internet<br>Não possuir conta Google<br>Usuário não encontra o ícone de menu<br>Usuário não consegue selecionar a dificuldade                                                                                                                       |

<figcaption align="center">Tabela 16: Cenário 15 (Fonte: Autores, 2022).</figcaption>

---

## Referências

> Cenários - Rastreamento de Cenários. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 06 dez. 2022.

## Histórico de versão

| Versão |    Data    |          Descrição          |      Autor      |     Revisor      |
| :----: | :--------: | :-------------------------: | :-------------: | :--------------: |
|  1.0   | 06/12/2022 | Início da página e cenários |   Lucas Lopes   | Philipe de Sousa |
|  1.1   | 07/12/2022 |   Adição de mais cenários   |   Lucas Lopes   | Philipe de Sousa |
|  1.2   | 10/12/2022 |   Finalização de cenários   | Hellen Fernanda | Philipe de Sousa |
