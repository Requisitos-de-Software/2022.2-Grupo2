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
| HU      | História usuário          |
| ST      | Storytelling              |
| BS      | Brainstorm                |
| L       | Léxico                    |
| NFR     | NFR                       |
| CAU     | Casos de Uso              |
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

| Origem         | Épico | Tema         | História de Usuário (US)                                                                                                                         | ID   | Funcionalidade | Artefato |
| -------------- | ----- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | ---- | -------------- | -------- |
| RF09           | E01   | Partidas     | Eu, como usuário, desejo configurar o tempo de partida e incremento ao iniciar uma partida para adequar ao meu estilo de jogo.                   | US01 |                |          |
| RF08,RF07,RF15 | E01   | Partidas     | Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida.                | US02 |                |          |
| RF18           | E01   | Partidas     | Eu, como usuário, desejo escolher jogar contra o computador ou contra um jogador para refletir as minhas necessidades do momento.                | US03 |                |          |
| RF20           | E02   | Partidas     | Eu, como usuário, desejo poder pausar uma partida contra o computador para poder retomá-la depois.                                               | US04 |                |          |
| RF10           | E02   | Partidas     | Eu, como usuário, desejo configurar um estilo de jogo para o robô, baseado em jogadores famosos, para me preparar para os campeonatos de xadrez. | US05 |                |          |
| RF15, RF19     | E03   | Partidas     | Eu, como usuário, desejo escolher o meu oponente podendo filtrar por por nome e nível, para não me frustrar com a partida.                       | US06 |                |          |
| RF27           | E03   | Partidas     | Eu, como usuário, desejo que meu oponente não possa pausar uma partida, para manter o jogo justo.                                                | US07 |                |          |
| RF16           | E04   | Partidas     | Eu, como usuário, desejo jogar partidas casuais sem interferir no meu ranqueamento, para não diminuir minha pontuação.                           | US08 |                |          |
| RF17           | E04   | Partidas     | Eu, como usuário, desejo jogar partidas online sem precisar criar uma conta, para me divertir.                                                   | US09 |                |          |
| RF02           | E05   | Tutoriais    | Eu, como usuário, desejo que um tutorial do aplicativo seja exibido na primeira vez que eu utilizá-lo, para que eu não fique desorientado.       | US10 |                |          |
| RF13           | E05   | Tutoriais    | Eu, como usuário, desejo ter acesso à uma seção de tutorial do aplicativo, para me sentir seguro durante momentos de dúvida.                     | US11 |                |          |
| RF05, RF23     | E06   | Tutoriais    | Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho.                                      | US12 |                |          |
| RF22           | E06   | Tutoriais    | Eu, como usuário, desejo aprimorar movimentos de xadrez por meio de quebra cabeças, para me sentir desafiado.                                    | US13 |                |          |
| RF12           | E06   | Tutoriais    | Eu, como usuário, desejo ter acesso às regras utilizadas na modalidade de xadrez durante a partida, para não me sentir desorientado.             | US14 |                |          |
| RF14           | E07   | Tutoriais    | Eu, como usuário, desejo cadastrar tutoriais para outros usuários, para auxiliar outras pessoas.                                                 | US15 |                |          |
| RF15           | E07   | Tutoriais    | Eu, como usuário, desejo criar quebra cabeças para outros usuários resolverem, para desafiar outras pessoas.                                     | US16 |                |          |
| RF01, RF03     | E08   | Ranqueamento | Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado.                                                      | US17 |                |          |
| RF11           | E08   | Ranqueamento | Eu, como usuário, desejo consultar as estatísticas das minhas partidas, para me preparar melhor.                                                 | US18 |                |          |
| RF26           | E08   | Ranqueamento | Eu, como usuário, desejo visualizar e filtrar o ranqueamento dos jogadores, para me manter motivado.                                             | US19 |                |          |
| RF25           | E09   | Ranqueamento | Eu, como usuário, desejo consultar as estatísticas dos quebra cabeças resolvidos, para me preparar melhor.                                       | US20 |                |          |
| RF04           | E10   | Socialização | Eu, como usuário, desejo adicionar outros jogadores como contatos, para fazer novos amigos.                                                      | US21 |                |          |
| RF24           | E10   | Socialização | Eu, como usuário, desejo trocar mensagens com outros jogadores, para fortalecer minhas amizades.                                                 | US22 |                |          |
| RF06           | E11   | Ranqueamento | Eu, como usuário, desejo assistir partidas de outros jogadores, para observar as técnicas usadas.                                                | US23 |                |          |
| RF21           | E11   | Ranqueamento | Eu, como usuário, desejo ser notificado quando partidas de outros jogadores iniciarem, para não perder partidas importantes para mim.            | US24 |                |          |

<div style="text-align: center">
<p> Tabela 1: Legenda do mapeamento de requisitos (Fonte: Autores[2023]).</p>
</div>

<!--## Requisitos Não Funcionais  -->

<!-- TO DO: Finalizar a nao funcionais -->

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acessado em: 22/01/2023

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 22/01/2023

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es)           | Revisor(es) |
| ------ | ---------- | -------------------- | ------------------- | ----------- |
| `1.0`  | 22/01/2023 | Criação do documento | Lucas Macedo e Davi | ---         |
| `1.1`  | 23/01/2023 | Adicionando partes do artefato | Lucas Macedo e Davi | ---         |
