# Forward From

## Introdução

Esse documento tem como objetivo apresentar todos os requisitos levantados no [forward from](forward_from.md) e no [backward from](backward.md) a partir de uma matriz de rastreabilidade.

## Metodologia

A metodologia aplicada consiste em uma matriz composta por 6 colunas as quais buscam apresentar os dados do requisito de maneira plena e sucinta.

## Mapeamento

Serão apresentados na tabela 1, o mapeamento dos documentos e sua referência dos artefatos apresentados em seguida.

| Legenda | Descrição                 |
| ------- | ------------------------- |
| US      | História usuário          |
| ST      | Storytelling              |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| INT     | Introspecção              |
| Q       | Questionário              |
| GLO     | Glossário                 |
| ENT     | Entrevista                |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |
<div style="text-align: center">
<p> Tabela 1: Legenda do mapeamento de requisitos (Fonte: Autores[2023]).</p>
</div>


<!-- TO DO: Finalizar a mapeamento -->

## Matriz Geral

Na tabela a seguir será apresentado a matriz:

| ID             | Descrição                                                                                                                                        | Elicitação    | Artefatos                           | Implementação                                                                                                            |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| RF09           | Eu, como usuário, desejo configurar o tempo de partida e incremento ao iniciar uma partida para adequar ao meu estilo de jogo.                   | Entrevista    | US01,ENT01,GLO02,ST04,UC01          | Completo                                                                                                                 |
| RF08,RF07,RF15 | Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida.                | Introspecção  | US02,INT04,INT03,GLO01,ST04,Q04,Q08 | Incompleto                                                                                                               |
| RF18           | Eu, como usuário, desejo escolher jogar contra o computador ou contra um jogador para refletir as minhas necessidades do momento.                | Introspecção  | US03, UC01,UC02                     | Completo                                                                                                                 |
| RF20           | Eu, como usuário, desejo poder pausar uma partida contra o computador para poder retomá-la depois.                                               | Introspecção  | US04, UC02                          | Inexistente                                                                                                              |
| RF10           | Eu, como usuário, desejo configurar um estilo de jogo para o robô, baseado em jogadores famosos, para me preparar para os campeonatos de xadrez. | Entrevista    | US05, ST04, UC02                    | Inexistente                                                                                                              |
| RF15, RF19     | Eu, como usuário, desejo escolher o meu oponente podendo filtrar por por nome e nível, para não me frustrar com a partida.                       | Introspecção  | US06, Q08, Q04, ST02, ST05          | Inexistente                                                                                                              |
| RF27           | Eu, como usuário, desejo que meu oponente não possa pausar uma partida, para manter o jogo justo.                                                | Introspecção  | US07, UC01                          | Inexistente                                                                                                              |
| RF16           | Eu, como usuário, desejo jogar partidas casuais sem interferir no meu ranqueamento, para não diminuir minha pontuação.                           | Story Telling | US08, UC01                          | Completo                                                                                                                 |
| RF17           | Eu, como usuário, desejo jogar partidas online sem precisar criar uma conta, para me divertir.                                                   | Questionário  | US09, Q09                           | Completo                                                                                                                 |
| RF02           | Eu, como usuário, desejo que um tutorial do aplicativo seja exibido na primeira vez que eu utilizá-lo, para que eu não fique desorientado.       | Questionário  | US10, UC04                          | Inexistente                                                                                                              |
| RF13           | Eu, como usuário, desejo ter acesso à uma seção de tutorial do aplicativo, para me sentir seguro durante momentos de dúvida.                     | Introspecção  | US11, UC04                          | Inexistente                                                                                                              |
| RF05, RF23     | Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho.                                      | Introspecção  | US12,Q13,ST11,ST13, UC04            | Completo                                                                                                                 |
| RF22           | Eu, como usuário, desejo aprimorar movimentos de xadrez por meio de quebra cabeças, para me sentir desafiado.                                    | Introspecção  | US13, GLO04,ST12, UC04              | Completo                                                                                                                 |
| RF12           | Eu, como usuário, desejo ter acesso às regras utilizadas na modalidade de xadrez durante a partida, para não me sentir desorientado.             | Glossário     | US14, UC04                          | Incompleto, o modo escolhido e uma breve introdução aparece somente no início da partida e somente para usuários logados |
| RF14           | Eu, como usuário, desejo cadastrar tutoriais para outros usuários, para auxiliar outras pessoas.                                                 | Story Telling | US15,UC04                           | Inexistente, somente pode ser criado no Lichess via web                                                                  |
| RF15           | Eu, como usuário, desejo criar quebra cabeças para outros usuários resolverem, para desafiar outras pessoas.                                     | Questionário  | US16,Q04,Q08, UC04                  | Inexistente, somente pode ser criado no Lichess via web                                                                  |
| RF01, RF03     | Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado.                                                      | Questionário  | US17,Q04,Q08, UC05                  | Completo                                                                                                                 |
| RF11           | Eu, como usuário, desejo consultar as estatísticas das minhas partidas, para me preparar melhor.                                                 | Story Telling | US18,ST09,Q02,UC05                  | Completo                                                                                                                 |
| RF26           | Eu, como usuário, desejo visualizar e filtrar o ranqueamento dos jogadores, para me manter motivado.                                             | Questionário  | US19,Q06,ST10,UC05                  | Inexistente                                                                                                              |
| RF25           | Eu, como usuário, desejo consultar as estatísticas dos quebra cabeças resolvidos, para me preparar melhor.                                       | Questionário  | US20,Q02,UC05                       | Completo                                                                                                                 |
| RF04           | Eu, como usuário, desejo adicionar outros jogadores como contatos, para fazer novos amigos.                                                      | Story Telling | ST07,UC01,US21                      | Completo                                                                                                                 |
| RF24           | Eu, como usuário, desejo trocar mensagens com outros jogadores, para fortalecer minhas amizades.                                                 | Story Telling | US22, ST08                          | Completo                                                                                                                 |
| RF06           | Eu, como usuário, desejo assistir partidas de outros jogadores, para observar as técnicas usadas.                                                | Story Telling | US23, ST06, UC03                    | Completo                                                                                                                 |
| RF21           | Eu, como usuário, desejo ser notificado quando partidas de outros jogadores iniciarem, para não perder partidas importantes para mim.            | Questionário  | US24, Q03, UC03,UC04                | Inexistente                                                                                                              |

<div style="text-align: center">
<p> Tabela 2: Matriz (Fonte: Autores[2023]).</p>
</div>

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acessado em: 22/01/2023

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 22/01/2023

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es) | Revisor(es)   |
| ------ | ---------- | -------------------- | --------- | ------------- |
| `1.0`  | 29/01/2023 | Criação do documento | Davi      | Lucas Gabriel |

