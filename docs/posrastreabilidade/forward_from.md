# Forward From

## Introdução

A rastreabilidade pode ser definido como uma técnica usado para determinar o relacionamento entre os requisitos, arquitetura e a implementação final do produto, auxiliando a compreender os artefatos. Vale ressaltar que os requisitos não podem ser gerenciados efetivamente sem sua rastreabilidade, na qual se divide em pré-rastreabilidade (sendo requisitos ligados a fontes) e pós-rastreabilidade (requisitos ligados aos artefatos criados durante o ciclo de vida do produto de software), onde é conhecido também como **Gerência de Desenvolvimento de Software baseado à Baseline**.

## Metodologia

A metodologia utilizada para conectar os requisitos com os artefatos foi o "foward-from" (para frente, a partir de). Desse modo, a pós-rastreabilidade compreende informações de rastreabilidade entre requisitos e artefatos de atividades de desenvolvimento subsequentes, bem como a rastreabilidade entre requisitos, que é sobre o mapeamento de dependências entre requisitos. Um exemplo desse tipo de rastreabilidade é a informação de que um requisito refina outro requisito, generaliza ou o substitui.

## Mapeamento

Na Tabela 1 é possível ver a legenda referente as Tabelas 2 a 30, as quais as quais demostram a pós-rastrabilidade associando os requistos a sua implementação.

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

<div style="text-align: center">
<p> Tabela 1: Legenda (Fonte: autor, 2023).</p>
</div>

### Requisitos Funcionais

**RF01**
|        RF01         |                 Deve existir um sistema de recompensas para incentivar os jogadores                 |
| :-----------------: | :-------------------------------------------------------------------------------------------------: |
|        Épico        |                                               [E08]()                                               |
|        Tema         |                                          [Ranqueamento]()                                           |
| História de Usuário | [US17]() Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado |
|      Artefatos      |                                [Q04](../elicitacao/questionario.md)                                 |
|   Funcionalidade    |                         ![Vídeo RF01-RF03](./assets/forward/RF01-RF03.mp4)                          |
|     Comentários     |                                       Implementação completa                                        |

**RF02**
|        RF02         |                               Deve existir uma apresentação inicial do aplicativo para o usuário no primeiro acesso                                |
| :-----------------: | :------------------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                      [E05]()                                                                       |
|        Tema         |                                                                   [Tutoriais]()                                                                    |
| História de Usuário | [US10]() Eu, como usuário, desejo que um tutorial do aplicativo seja exibido na primeira vez que eu utilizá-lo, para que eu não fique desorientado |
|      Artefatos      |                                                        [Q10](../elicitacao/questionario.md)                                                        |
|   Funcionalidade    |                                                                         -                                                                          |
|     Comentários     |                                                             Implementação inexistente                                                              |


**RF03**
|        RF03         |        Deve existir uma apresentação inicial do aplicativo para o usuário no primeiro acesso        |
| :-----------------: | :-------------------------------------------------------------------------------------------------: |
|        Épico        |                                               [E08]()                                               |
|        Tema         |                                          [Ranqueamento]()                                           |
| História de Usuário | [US17]() Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado |
|      Artefatos      |           [Q04](../elicitacao/questionario.md)<br/> [Q08](../elicitacao/questionario.md)            |
|   Funcionalidade    |                         ![Vídeo RF01-RF03](./assets/forward/RF01-RF03.mp4)                          |
|     Comentários     |                                       Implementação completa                                        |

**RF04**
|        RF04         |                            Deve ser possível adicionar outros jogadores                             |
| :-----------------: | :-------------------------------------------------------------------------------------------------: |
|        Épico        |                                               [E10]()                                               |
|        Tema         |                                          [Socialização]()                                           |
| História de Usuário | [US21]() Eu, como usuário, desejo adicionar outros jogadores como contatos, para fazer novos amigos |
|      Artefatos      |                                [ST07](../elicitacao/storytelling.md)                                |
|   Funcionalidade    |                              ![Vídeo RF04](./assets/forward/RF04.mp4)                               |
|     Comentários     |                                       Implementação completa                                        |

**RF05**
|        RF05         |                            Deve ser possível aprender movimentos de xadrez por meio de tutoriais                            |
| :-----------------: | :-------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                           [E06]()                                                           |
|        Tema         |                                                        [Tutoriais]()                                                        |
| História de Usuário |     [US12]() Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho     |
|      Artefatos      | [INT07](../elicitacao/introspeccao.md)<br/> [Q13](../elicitacao/questionario.md)<br/> [ST11](../elicitacao/storytelling.md) |
|   Funcionalidade    |                                     ![Vídeo RF05 RF23](./assets/forward/RF05-RF23.mp4)                                      |
|     Comentários     |                                                   Implementação completa                                                    |

**RF06**
|        RF06         |                           Deve ser possível assistir partidas de outras pessoas                           |
| :-----------------: | :-------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                  [E11]()                                                  |
|        Tema         |                                               [Torneios]()                                                |
| História de Usuário | [US23]() Eu, como usuário, desejo assistir partidas de outros jogadores, para observar as técnicas usadas |
|      Artefatos      |                                   [ST06](../elicitacao/storytelling.md)                                   |
|   Funcionalidade    |                                 ![Vídeo RF06](./assets/forward/RF06.mp4)                                  |
|     Comentários     |                                          Implementação completa                                           |

**RF07**
|        RF07         |                                 Deve ser possível configurar a dificuldade da partida contra o computador                                 |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                  [E01]()                                                                  |
|        Tema         |                                                               [Partidas]()                                                                |
| História de Usuário | [US02]() Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida |
|      Artefatos      |                                                  [INT04](../elicitacao/introspeccao.md)                                                   |
|   Funcionalidade    |                                         ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4)                                         |
|     Comentários     |                                                          Implementação completa                                                           |

**RF08**
|        RF08         |                                 Deve ser possível configurar a modalidade de jogo ao iniciar uma partida                                  |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                  [E01]()                                                                  |
|        Tema         |                                                               [Partidas]()                                                                |
| História de Usuário | [US02]() Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida |
|      Artefatos      |        [GLO01](../elicitacao/glossario.md)<br/> [INT03](../elicitacao/introspeccao.md)<br/> [ST04](../elicitacao/storytelling.md)         |
|   Funcionalidade    |                                         ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4)                                         |
|     Comentários     |                                                          Implementação completa                                                           |

**RF09**
|        RF09         |                     Deve ser possível configurar o tempo de duração da partida e incremento ao iniciar uma partida                     |
| :-----------------: | :------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                [E01]()                                                                 |
|        Tema         |                                                              [Partidas]()                                                              |
| História de Usuário | [US01]() Eu, como usuário, desejo configurar o tempo de partida e incremento ao iniciar uma partida para adequar ao meu estilo de jogo |
|      Artefatos      |        [ENT01](../elicitacao/entrevista.md)<br/> [GLO02](../elicitacao/glossario.md)<br/> [ST04](../elicitacao/storytelling.md)        |
|   Funcionalidade    |                                                ![Video RF09](./assets/forward/RF09.mp4)                                                |
|     Comentários     |                                                         Implementação completa                                                         |

**RF10**
|        RF10         |                Deve ser possível configurar um estilo de jogo para o robô, baseado em jogadores famosos, nas partidas contra o computador                |
| :-----------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                         [E02]()                                                                          |
|        Tema         |                                                                       [Partidas]()                                                                       |
| História de Usuário | [US05]() Eu, como usuário, desejo configurar um estilo de jogo para o robô, baseado em jogadores famosos, para me preparar para os campeonatos de xadrez |
|      Artefatos      |                                     [ENT02](../elicitacao/entrevista.md)<br/> [ST04](../elicitacao/storytelling.md)                                      |
|   Funcionalidade    |                                                                            -                                                                             |
|     Comentários     |                                                                Implementação Inexistente                                                                 |

**RF11**
|        RF11         |                                                           Deve ser possível consultar as estatísticas das partidas anteriores                                                            |
| :-----------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                                         [E08]()                                                                                          |
|        Tema         |                                                                                     [Ranqueamento]()                                                                                     |
| História de Usuário |                                         [US18]() Eu, como usuário, desejo consultar as estatísticas das minhas partidas, para me preparar melhor                                         |
|      Artefatos      |                                                     [ST09](../elicitacao/storytelling.md)<br/> [Q02](../elicitacao/questionario.md)                                                      |
|   Funcionalidade    |                                                                         ![Vídeo RF11](./assets/forward/RF11.mp4)                                                                         |
|     Comentários     | Implementação incompleta, é possível consultar a partida e após isso utilizar o computador para observar melhores lances, porém não há estatisticas relacionadas as partidas diretamente |

**RF12**
|        RF12         |                                                        Deve ser possível consultar as regras da modalidade de jogo em andamento                                                         |
| :-----------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                                         [E06]()                                                                                         |
|        Tema         |                                                                                      [Tutoriais]()                                                                                      |
| História de Usuário |                      [US14]() Eu, como usuário, desejo ter acesso às regras utilizadas na modalidade de xadrez durante a partida, para não me sentir desorientado                       |
|      Artefatos      |                                                                           [GLO03](../elicitacao/glossario.md)                                                                           |
|   Funcionalidade    |                                                                                            -                                                                                            |
|     Comentários     | Implementação incompleta, o modo escolhido é uma breve introdução que aparece somente no início da partida e somente para usuários "logados", ou seja, utilizando a conta da plataforma |

**RF13**
|        RF13         |                                     Deve ser possível consultar um tutorial de uso do aplicativo                                     |
| :-----------------: | :----------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                               [E05]()                                                                |
|        Tema         |                                                            [Tutoriais]()                                                             |
| História de Usuário | [US11]() Eu, como usuário, desejo ter acesso à uma seção de tutorial do aplicativo, para me sentir seguro durante momentos de dúvida |
|      Artefatos      |                                                [INT08](../elicitacao/introspeccao.md)                                                |
|   Funcionalidade    |                                                                  -                                                                   |
|     Comentários     |                                                      Implementação inexistente                                                       |

**RF14**
|        RF14         |                        Deve ser possível elaborar tutoriais para outros jogadores                        |
| :-----------------: | :------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                 [E07]()                                                  |
|        Tema         |                                              [Tutoriais]()                                               |
| História de Usuário | [US15]() Eu, como usuário, desejo cadastrar tutoriais para outros usuários, para auxiliar outras pessoas |
|      Artefatos      |                                  [ST13](../elicitacao/storytelling.md)                                   |
|   Funcionalidade    |                                                    -                                                     |
|     Comentários     |                  Implementação inexistente, somente pode ser criado no Lichess via web                   |

**RF15**    
|        RF15         |                        Deve ser possível escolher o nível do oponente ao iniciar uma partida contra outro jogador                         |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                  [E01]()                                                                  |
|        Tema         |                                                               [Partidas]()                                                                |
| História de Usuário | [US02]() Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida |
|      Artefatos      |                              [Q08](../elicitacao/questionario.md)<br/> [Q04](../elicitacao/questionario.md)                               |
|   Funcionalidade    |                                         ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4)                                         |
|     Comentários     |             Implementação incompleta, apenas usuarios com conta na plataforma conseguem selecionar o nível de seus oponentes              |

**RF16**    
|        RF16         |                                        Deve ser possível jogar partidas não ranqueadas                                         |
| :-----------------: | :----------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                            [E04]()                                                             |
|        Tema         |                                                          [Partidas]()                                                          |
| História de Usuário | [US08]() Eu, como usuário, desejo jogar partidas casuais sem interferir no meu ranqueamento, para não diminuir minha pontuação |
|      Artefatos      |                                             [ST03](../elicitacao/storytelling.md)                                              |
|   Funcionalidade    |                                            ![Vídeo RF16](./assets/forward/RF16.mp4)                                            |
|     Comentários     |                                                     Implementação completa                                                     |

**RF17**
|        RF17         |                      Deve ser possível jogar partidas online sem criar uma conta                       |
| :-----------------: | :----------------------------------------------------------------------------------------------------: |
|        Épico        |                                                [E04]()                                                 |
|        Tema         |                                              [Partidas]()                                              |
| História de Usuário | [US09]() Eu, como usuário, desejo jogar partidas online sem precisar criar uma conta, para me divertir |
|      Artefatos      |                                  [Q09](../elicitacao/questionario.md)                                  |
|   Funcionalidade    |                       ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4)                        |
|     Comentários     |                                         Implementação completa                                         |


**RF18**
|        RF18         |                                     Deve ser possível jogar uma partida de xadrez contra o computador                                     |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                  [E02]()                                                                  |
|        Tema         |                                                               [Partidas]()                                                                |
| História de Usuário | [US03]() Eu, como usuário, desejo escolher jogar contra o computador ou contra um jogador para refletir as minhas necessidades do momento |
|      Artefatos      |                                                  [INT01](../elicitacao/introspeccao.md)                                                   |
|   Funcionalidade    |                                                 ![Vídeo RF18](./assets/forward/RF18.mp4)                                                  |
|     Comentários     |                                                          Implementação completa                                                           |

**RF19**
|        RF19         |                   Deve ser possível jogar uma partida de xadrez contra outro jogador aleatório ou escolhido                    |
| :-----------------: | :----------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                            [E03]()                                                             |
|        Tema         |                                                          [Partidas]()                                                          |
| História de Usuário | [US06]() Eu, como usuário, desejo escolher o meu oponente podendo filtrar por nome e nível, para não me frustrar com a partida |
|      Artefatos      |  [INT02](../elicitacao/introspeccao.md)<br/> [ST02](../elicitacao/storytelling.md)<br/> [ST05](../elicitacao/storytelling.md)  |
|   Funcionalidade    |                                                               -                                                                |
|     Comentários     |                                                   Implementação Inexistente                                                    |

**RF20**
|        RF20         |                         Deve ser possível pausar uma partida contra o computador                          |
| :-----------------: | :-------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                  [E02]()                                                  |
|        Tema         |                                               [Partidas]()                                                |
| História de Usuário | [US04]()Eu, como usuário, desejo poder pausar uma partida contra o computador para poder retomá-la depois |
|      Artefatos      |                                  [INT05](../elicitacao/introspeccao.md)                                   |
|   Funcionalidade    |                                                     -                                                     |
|     Comentários     |                                         Implementação inexistente                                         |

**RF21**
|        RF21         |                                         Deve ser possível receber notificações sobre torneios ao vivo                                         |
| :-----------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                                    [E11]()                                                                    |
|        Tema         |                                                                 [Torneios]()                                                                  |
| História de Usuário | [US24]() Eu, como usuário, desejo ser notificado quando partidas de outros jogadores iniciarem, para não perder partidas importantes para mim |
|      Artefatos      |                                                     [Q03](../elicitacao/questionario.md)                                                      |
|   Funcionalidade    |                                                                       -                                                                       |
|     Comentários     |                                                           Implementação inexistente                                                           |

**RF22**
|        RF22         |                         Deve ser possível resolver quebra cabeças elaborados por outros jogadores                          |
| :-----------------: | :------------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                          [E06]()                                                           |
|        Tema         |                                                       [Tutoriais]()                                                        |
| História de Usuário |   [US13]() Eu, como usuário, desejo aprimorar movimentos de xadrez por meio de quebra cabeças, para me sentir desafiado    |
|      Artefatos      | [GLO04](../elicitacao/glossario.md)<br/> [INT12](../elicitacao/introspeccao.md)<br/> [ST12](../elicitacao/storytelling.md) |
|   Funcionalidade    |                                          ![Vídeo RF22](./assets/forward/RF22.mp4)                                          |
|     Comentários     |                                                   Implementação completa                                                   |

**RF23**
|        RF23         |                        Deve ser possível resolver tutoriais elaborados por outros jogadores                         |
| :-----------------: | :-----------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                       [E06]()                                                       |
|        Tema         |                                                    [Tutoriais]()                                                    |
| História de Usuário | [US12]() Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho |
|      Artefatos      |                                        [ST13](../elicitacao/storytelling.md)                                        |
|   Funcionalidade    |                                 ![Vídeo RF05 RF23](./assets/forward/RF05-RF23.mp4)                                  |
|     Comentários     |                                               Implementação completa                                                |

**RF24**
|        RF24         |                         Deve ser possível trocar mensagens com outros jogadores                          |
| :-----------------: | :------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                 [E10]()                                                  |
|        Tema         |                                             [Socialização]()                                             |
| História de Usuário | [US22]() Eu, como usuário, desejo trocar mensagens com outros jogadores, para fortalecer minhas amizades |
|      Artefatos      |                                  [ST08](../elicitacao/storytelling.md)                                   |
|   Funcionalidade    |                                 ![Vídeo RF24](./assets/forward/RF24.mp4)                                 |
|     Comentários     |                                          Implementação completa                                          |

**RF25**
|        RF25         |                       Deve ser possível visualizar dados sobre os quebra-cabeças concluídos                        |
| :-----------------: | :----------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                      [E09]()                                                       |
|        Tema         |                                                  [Ranqueamento]()                                                  |
| História de Usuário | [US20]() Eu, como usuário, desejo consultar as estatísticas dos quebra cabeças resolvidos, para me preparar melhor |
|      Artefatos      |                                        [Q02](../elicitacao/questionario.md)                                        |
|   Funcionalidade    |                                                         -                                                          |
|     Comentários     |                                             Implementação inexistente                                              |

**RF26**
|        RF26         |                      Deve ser possível visualizar e filtrar o ranqueamento de jogadores                      |
| :-----------------: | :----------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                   [E08]()                                                    |
|        Tema         |                                               [Ranqueamento]()                                               |
| História de Usuário | [US19]() Eu, como usuário, desejo visualizar e filtrar o ranqueamento dos jogadores, para me manter motivado |
|      Artefatos      |               [Q06](../elicitacao/questionario.md)<br/> [ST10](../elicitacao/storytelling.md)                |
|   Funcionalidade    |                                                      -                                                       |
|     Comentários     |                                          Implementação inexistente                                           |

**RF27**
|        RF27         |                       Não deve ser possível pausar uma partida contra outro jogador                       |
| :-----------------: | :-------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                  [E03]()                                                  |
|        Tema         |                                               [Partidas]()                                                |
| História de Usuário | [US07]() Eu, como usuário, desejo que meu oponente não possa pausar uma partida, para manter o jogo justo |
|      Artefatos      |                                  [INT06](../elicitacao/introspeccao.md)                                   |
|   Funcionalidade    |                                 ![Vídeo RF16](./assets/forward/RF16.mp4)                                  |
|     Comentários     |                                          Implementação completa                                           |


**RF28**
|        RF28         |                        Deve ser possível criar quebra cabeça para outros jogadores resolverem                        |
| :-----------------: | :------------------------------------------------------------------------------------------------------------------: |
|        Épico        |                                                       [E07]()                                                        |
|        Tema         |                                                    [Tutoriais]()                                                     |
| História de Usuário | [US16]() Eu, como usuário, desejo criar quebra cabeças para outros usuários resolverem, para desafiar outras pessoas |
|      Artefatos      |                   [GLO04](../elicitacao/glossario.md)<br/> [INT15](../elicitacao/introspeccao.md)                    |
|   Funcionalidade    |                                                          -                                                           |
|     Comentários     |                                              Implementação inexistente                                               |

### Requisitos Não Funcionais


## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acessado em: 22/01/2023

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 22/01/2023

## Histórico de Versão

| Versão | Data       | Descrição                                                                                                              | Autor(es)           | Revisor(es)   |
| ------ | ---------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------- |
| `1.0`  | 22/01/2023 | Criação do documento                                                                                                   | Lucas Macedo e Davi | Lucas Gabriel |
| `1.1`  | 23/01/2023 | Adicionando partes do artefato                                                                                         | Lucas Macedo e Davi | Lucas Gabriel |
| `1.2`  | 23/01/2023 | Adição gravação requisitos                                                                                             | Mauricio Machado    | Davi          |
| `2.0`  | 29/01/2023 | Ajustes na metodologia, modificação da tabela de todos os requisitos funcionais e adição dos requisitos não funcionais | Lucas Gabriel       |               |
                                                                                                         
