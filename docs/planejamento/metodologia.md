# Metodologia

## Introdução

Visando aprimorar a agilidade da equipe, e utilizar de técnicas que são conhecidas pelo grupo, foi definido que iremos utilizar metodologias ágeis, especificamente o Scrum.
</br>
O Scrum é um framework para desenvolvimento ágil tanto de software como de outras áreas. Derivado do manifesto ágil, se tornou o principal a ser utilzado para a organização e gerencia de grandes projetos, visando sempre a otimização do time, e entregas rápidas e contínuas de releases. 

A seguir temos a <i>Imagem 1</i> que mostra o fluxo do scrum:

</br>

### Fluxo do Scrum

![scrum Fluxo](./assets/scrumFluxo.png)

<figcaption align="center">Figura 1: Fluxo do Scrum (Fonte: <a href="https://metodologiaagil.com/scrum/" target="_blanck">Metodologias Ágeis e Scrum</a>, 2022)</figcaption>

### Legenda:
- **Product backlog**: artefatos a ser trabalho, como por exemplo uma funcionalidade;
- **Sprint backlog**: artefato escolhido para ser trabalho naquela fase;
- **Daily scrum meeting**: Reuniões diárias e semanais para acompanhamento da sprint;
- **Potentially shippable product increment**: É o artefato concluído na sprint que será implementado no sistema;
- **Sprint**: Termo utlizado para expressar o períodod de trabalho;
- **24 hours**: 24 horas;
- **2-4 weeks**: 2-4 semanas;

</br>

## Política de commit

Para maior controle sobre as alterações que são feitas nos documentos, será definido uma política de commit para organizarmos as alterações que são feitas, e quem as executou.  
De acordo com o que foi definido pela equipe, a mensagem do commit deve ser igual a mensagem de modificação deixada no histórico de versionamento do arquivo para que caso seja nescessário encontrar seu commit no repositório.  
Também foi recomendado que não seja editado mais de um arquivo de página por commit, pois logo o commit englobará os dois arquivos e será mais complicado saber o que foi modificado em cada um.  
Segue o modelo a ser seguido:

```git
git commit -m "Mudança que foi feita no arquivo"
```

Caso seja nescessário usar co-authored, será utilizado normalmente sem nenhuma restrição.

## Política de revisão

Para que nenhum arquivo fique com alguma informação faltando ou errada, foi definido que a cada nova modificação feita nos arquivos, será escolhido pelo autor um outro membro da equipe para executar a revisão e apontar os pontos que precisarão ser modificados caso nescessário. Se tornando obrigatório a requisição de um revisador desde a sprint 1 onde foi acordado tal exigência.

## Referências

> Site metodologias ágeis - <a href="https://www.metodologiaagil.com">www.metodologiaagil.com</a>

</br>

## Histórico de versão

| Versão |    Data    |                            Descrição                            |      Autor       |              Revisor              |
| :----: | :--------: | :-------------------------------------------------------------: | :--------------: | :-------------------------------: |
|  1.0   | 15/11/2022 |                Criado arquivo sobre metodologias                | Wildemberg Sales |         João Pedro Alves          |
|  1.1   | 15/11/2022 | Resolvido bug de não aparecer imagem e adicionado bibliografias | Wildemberg Sales |         João Pedro Alves          |
|  1.2   | 18/11/2022 |                    Ajustado links e títulos                     | Wildemberg Sales | João Pedro Alves, Hellen Fernanda |
| 1.3 | 24/11/2022 | Ajuste dos números de revisões, ajustado legenda da imagem | Wildemberg Sales | João Pedro Alves |