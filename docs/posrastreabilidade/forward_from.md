# Forward From

## Introdução

A rastreabilidade pode ser definido como uma técnica usado para determinar o relacionamento entre os requisitos, arquitetura e a implementação final do produto, auxiliando ao compreender os artefatos. Vale ressaltar que os requisitos não devem podem ser gerenciados efetivamente sem sua rastreabilidade, no qual se divide em pré-rastreabilidade (sendo requisitos ligados a fontes) e pós-rastreabilidade (requisitos ligados aos artefatos criados durante o ciclo de vida do produto de software), onde é conhecido também como **Gerência de Desenvolvimento de Software baseado à Baseline**

## Metodologia

A metodologia utilizada para conectar os requisitos com os artefatos foi o "foward-from". Desse modo, a pós-rastreabilidade compreende informações de rastreabilidade entre requisitos e artefatos de atividades de desenvolvimento subsequentes. Bem como também, a rastreabilidade entre requisitos, que é sobre o mapeamento de dependências entre requisitos. Um exemplo desse tipo de rastreabilidade é a informação de que um requisito refina outro requisito, generaliza ou o substitui.

Iremos utilizar tabelas as quais serão dividias em requisitos funcionais e nao funcionais.

<!-- TO DO: Finalizar a metodologia -->

## Mapeamento

Serão apresentados na tabela 1, o mapeamento dos documentos e sua referência dos artefatos apresentados em seguida.

| Legenda | Artefato                  |
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

<!-- TO DO: Finalizar a mapeamento -->

## Requisitos Funcionais

Na tabelas a seguir serão registrados os requisitos não funcionais, agora com o método de pós-rastreabilidade

| Origem         | Épico | Tema         | História de Usuário (US)                                                                                                                         | ID   | Funcionalidade                                            | Artefato                                 | Cenário   |                                                                                                                          | Observação |
| -------------- | ----- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | --------------------------------------------------------- | ---------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------ | ---------- |
| RF09           | E01   | Partidas     | Eu, como usuário, desejo configurar o tempo de partida e incremento ao iniciar uma partida para adequar ao meu estilo de jogo.                   | US01 | ![Video RF09](./assets/forward/RF09.mp4)                  | ETN01,GLO02,ST04                         | UC01      | Completo                                                                                                                 |
| RF08,RF07,RF15 | E01   | Partidas     | Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida.                | US02 | ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4) | INT04,INT03,GLO01,ST04,Q04,Q08           | UC02      | Incompleto                                                                                                               |
| RF18           | E01   | Partidas     | Eu, como usuário, desejo escolher jogar contra o computador ou contra um jogador para refletir as minhas necessidades do momento.                | US03 | ![Vídeo RF18](./assets/forward/RF18.mp4)                  | INT01                                    | UC01,UC02 | Completo                                                                                                                 |
| RF20           | E02   | Partidas     | Eu, como usuário, desejo poder pausar uma partida contra o computador para poder retomá-la depois.                                               | US04 |                                                           | INT05                                    | UC02      | Inexistente                                                                                                              |
| RF10           | E02   | Partidas     | Eu, como usuário, desejo configurar um estilo de jogo para o robô, baseado em jogadores famosos, para me preparar para os campeonatos de xadrez. | US05 |                                                           | ENT02,ST04                               | UC02      | Inexistente                                                                                                              |
| RF15, RF19     | E03   | Partidas     | Eu, como usuário, desejo escolher o meu oponente podendo filtrar por por nome e nível, para não me frustrar com a partida.                       | US06 |                                                           | Q08,Q04,INT02,ST02,ST05                  | UC01      | Inexistente                                                                                                              |
| RF27           | E03   | Partidas     | Eu, como usuário, desejo que meu oponente não possa pausar uma partida, para manter o jogo justo.                                                | US07 |                                                           | INT06                                    | UC01      | Inexistente                                                                                                              |
| RF16           | E04   | Partidas     | Eu, como usuário, desejo jogar partidas casuais sem interferir no meu ranqueamento, para não diminuir minha pontuação.                           | US08 | ![Vídeo RF16](./assets/forward/RF16.mp4)                  | ST03                                     | UC01      | Completo                                                                                                                 |
| RF17           | E04   | Partidas     | Eu, como usuário, desejo jogar partidas online sem precisar criar uma conta, para me divertir.                                                   | US09 | ![Vídeo RF16](./assets/forward/RF16.mp4)                  | Q09                                      |           | Completo                                                                                                                 |
| RF02           | E05   | Tutoriais    | Eu, como usuário, desejo que um tutorial do aplicativo seja exibido na primeira vez que eu utilizá-lo, para que eu não fique desorientado.       | US10 |                                                           | Q10                                      | UC04      | Inexistente                                                                                                              |
| RF13           | E05   | Tutoriais    | Eu, como usuário, desejo ter acesso à uma seção de tutorial do aplicativo, para me sentir seguro durante momentos de dúvida.                     | US11 |                                                           | INT08                                    | UC04      | Inexistente                                                                                                              |
| RF05, RF23     | E06   | Tutoriais    | Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho.                                      | US12 | ![Vídeo RF05 RF23](./assets/forward/RF05-RF23.mp4)        | INT07, Q13,ST11,ST13                     | UC04      | Completo                                                                                                                 |
| RF22           | E06   | Tutoriais    | Eu, como usuário, desejo aprimorar movimentos de xadrez por meio de quebra cabeças, para me sentir desafiado.                                    | US13 | ![Vídeo RF22](./assets/forward/RF22.mp4)                  | GLO04,INT12,ST12                         | UC04      | Completo                                                                                                                 |
| RF12           | E06   | Tutoriais    | Eu, como usuário, desejo ter acesso às regras utilizadas na modalidade de xadrez durante a partida, para não me sentir desorientado.             | US14 |                                                           | GLO03                                    | UC04      | Incompleto, o modo escolhido e uma breve introdução aparece somente no início da partida e somente para usuários logados |
| RF14           | E07   | Tutoriais    | Eu, como usuário, desejo cadastrar tutoriais para outros usuários, para auxiliar outras pessoas.                                                 | US15 |                                                           | ST13                                     | UC04      | Inexistente, somente pode ser criado no Lichess via web                                                                  |
| RF15           | E07   | Tutoriais    | Eu, como usuário, desejo criar quebra cabeças para outros usuários resolverem, para desafiar outras pessoas.                                     | US16 |                                                           | Q04,Q08                                  | UC04      | Inexistente, somente pode ser criado no Lichess via web                                                                  |
| RF01, RF03     | E08   | Ranqueamento | Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado.                                                      | US17 | ![Vídeo RF01-RF03](./assets/forward/RF01-RF03.mp4)        | Q04,Q08                                  | UC05      | Completo                                                                                                                 |
| RF11           | E08   | Ranqueamento | Eu, como usuário, desejo consultar as estatísticas das minhas partidas, para me preparar melhor.                                                 | US18 | ![Vídeo RF11](./assets/forward/RF11.mp4)                  | ST09,Q02                                 | UC05      | Completo                                                                                                                 |
| RF26           | E08   | Ranqueamento | Eu, como usuário, desejo visualizar e filtrar o ranqueamento dos jogadores, para me manter motivado.                                             | US19 |                                                           | Q06,ST10                                 | UC05      | Inexistente                                                                                                              |
| RF25           | E09   | Ranqueamento | Eu, como usuário, desejo consultar as estatísticas dos quebra cabeças resolvidos, para me preparar melhor.                                       | US20 | ![Vídeo RF25](./assets/forward/RF11.mp4)                  | Q02                                      | UC05      | Completo                                                                                                                 |
| RF04           | E10   | Socialização | Eu, como usuário, desejo adicionar outros jogadores como contatos, para fazer novos amigos.                                                      | US21 | ST07                                                      | ![Vídeo RF04](./assets/forward/RF04.mp4) | UC01      | Completo                                                                                                                 |
| RF24           | E10   | Socialização | Eu, como usuário, desejo trocar mensagens com outros jogadores, para fortalecer minhas amizades.                                                 | US22 | ![Vídeo RF24](./assets/forward/RF24.mp4)                  | ST08                                     | -         | Completo                                                                                                                 |
| RF06           | E11   | Ranqueamento | Eu, como usuário, desejo assistir partidas de outros jogadores, para observar as técnicas usadas.                                                | US23 | ![Vídeo RF06](./assets/forward/RF06.mp4)                  | ST06                                     | UC03      | Completo                                                                                                                 |
| RF21           | E11   | Ranqueamento | Eu, como usuário, desejo ser notificado quando partidas de outros jogadores iniciarem, para não perder partidas importantes para mim.            | US24 |                                                           | Q03                                      | UC03,UC04 | Inexistente                                                                                                              |

<div style="text-align: center">
<p> Tabela 1: Legenda do mapeamento de requisitos (Fonte: Autores[2023]).</p>
</div>

<!--## Requisitos Não Funcionais  -->

<!-- TO DO: Finalizar a nao funcionais -->

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acessado em: 22/01/2023

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 22/01/2023

## Histórico de Versão

| Versão | Data       | Descrição                      | Autor(es)           | Revisor(es)   |
| ------ | ---------- | ------------------------------ | ------------------- | ------------- |
| `1.0`  | 22/01/2023 | Criação do documento           | Lucas Macedo e Davi | Lucas Gabriel |
| `1.1`  | 23/01/2023 | Adicionando partes do artefato | Lucas Macedo e Davi | Lucas Gabriel |
| `1.2`  | 23/01/2023 | Adição gravação requisitos     | Mauricio Machado    | Davi          |
