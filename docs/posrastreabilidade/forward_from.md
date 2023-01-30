# Forward From

## Introdução

A rastreabilidade pode ser definido como uma técnica usado para determinar o relacionamento entre os requisitos, arquitetura e a implementação final do produto, auxiliando a compreender os artefatos. Vale ressaltar que os requisitos não podem ser gerenciados efetivamente sem sua rastreabilidade, na qual se divide em pré-rastreabilidade (sendo requisitos ligados a fontes) e pós-rastreabilidade (requisitos ligados aos artefatos criados durante o ciclo de vida do produto de software), onde é conhecido também como **Gerência de Desenvolvimento de Software baseado à Baseline**.

## Metodologia

A metodologia utilizada para conectar os requisitos com os artefatos foi o "foward-from" (para frente, a partir de). Desse modo, a pós-rastreabilidade compreende informações de rastreabilidade entre requisitos e artefatos de atividades de desenvolvimento subsequentes, bem como a rastreabilidade entre requisitos, que é sobre o mapeamento de dependências entre requisitos. Um exemplo desse tipo de rastreabilidade é a informação de que um requisito refina outro requisito, generaliza ou o substitui.

## Mapeamento

Na Tabela 1 é possível ver a legenda referente as Tabelas 2 a 53, as quais as quais demostram a pós-rastrabilidade associando os requistos a sua implementação.

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
|                 RF01                 |                              Deve existir um sistema de recompensas para incentivar os jogadores                              |
| :----------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                [E08](../modelagem/agil/backlog/#e08-estatisticas-de-partidas)                                 |
|                 Tema                 |                                                         Ranqueamento                                                          |
|         História de Usuário          | [US17](../modelagem/agil/us/#us17) Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado |
|                Léxico                |                                                                                                                               |
|             Casos de uso             |                                                                                                                               |
|               Cenários               |                                                                                                                               |
| Artefatos (elicitação de requisitos) |                                             [Q04](../elicitacao/questionario.md)                                              |
|             Comentários              |                                                    Implementação completa                                                     |
|            Funcionalidade            |                                      ![Vídeo RF01-RF03](./assets/forward/RF01-RF03.mp4)                                       |

<div style="text-align: center">
<p> Tabela 2: RF01 (Fonte: autor, 2023).</p>
</div>

**RF02**
|                 RF02                 |                                            Deve existir uma apresentação inicial do aplicativo para o usuário no primeiro acesso                                             |
| :----------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                           [E05](../modelagem/agil/backlog/#e05-manual-do-usuario)                                                            |
|                 Tema                 |                                                                                  Tutoriais                                                                                   |
|         História de Usuário          | [US10](../modelagem/agil/us/#us10) Eu, como usuário, desejo que um tutorial do aplicativo seja exibido na primeira vez que eu utilizá-lo, para que eu não fique desorientado |
|                Léxico                |                                                                                                                                                                              |
|             Casos de uso             |                                                                                                                                                                              |
|               Cenários               |                                                                                                                                                                              |
| Artefatos (elicitação de requisitos) |                                                                     [Q10](../elicitacao/questionario.md)                                                                     |
|             Comentários              |                                                                          Implementação inexistente                                                                           |
|            Funcionalidade            |                                                                                      -                                                                                       |

<div style="text-align: center">
<p> Tabela 3: RF02 (Fonte: autor, 2023).</p>
</div>

**RF03**
|                 RF03                 |                     Deve existir uma apresentação inicial do aplicativo para o usuário no primeiro acesso                     |
| :----------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                [E08](../modelagem/agil/backlog/#e08-estatisticas-de-partidas)                                 |
|                 Tema                 |                                                         Ranqueamento                                                          |
|         História de Usuário          | [US17](../modelagem/agil/us/#us17) Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado |
|                Léxico                |                                                                                                                               |
|             Casos de uso             |                                                                                                                               |
|               Cenários               |                                                                                                                               |
| Artefatos (elicitação de requisitos) |                        [Q04](../elicitacao/questionario.md)<br/> [Q08](../elicitacao/questionario.md)                         |
|             Comentários              |                                                    Implementação completa                                                     |
|            Funcionalidade            |                                      ![Vídeo RF01-RF03](./assets/forward/RF01-RF03.mp4)                                       |

<div style="text-align: center">
<p> Tabela 4: RF03 (Fonte: autor, 2023).</p>
</div>

**RF04**
|                 RF04                 |                                         Deve ser possível adicionar outros jogadores                                          |
| :----------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                               [E10](..//2022.2-Lichess/modelagem/agil/backlog/#e10-comunicacao)                               |
|                 Tema                 |                                                         Socialização                                                          |
|         História de Usuário          | [US21](../modelagem/agil/us/#us21) Eu, como usuário, desejo adicionar outros jogadores como contatos, para fazer novos amigos |
|                Léxico                |                                                                                                                               |
|             Casos de uso             |                                                                                                                               |
|               Cenários               |                                                                                                                               |
| Artefatos (elicitação de requisitos) |                                             [ST07](../elicitacao/storytelling.md)                                             |
|             Comentários              |                                                    Implementação completa                                                     |
|            Funcionalidade            |                                           ![Vídeo RF04](./assets/forward/RF04.mp4)                                            |

<div style="text-align: center">
<p> Tabela 5: RF04 (Fonte: autor, 2023).</p>
</div>

**RF05**
|                 RF05                 |                                     Deve ser possível aprender movimentos de xadrez por meio de tutoriais                                     |
| :----------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                             [E06](../modelagem/agil/backlog/#e06-estudar-xadrez)                                              |
|                 Tema                 |                                                                   Tutoriais                                                                   |
|         História de Usuário          | [US12](../modelagem/agil/us/#us12) Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho |
|                Léxico                |                                                                                                                                               |
|             Casos de uso             |                                                                                                                                               |
|               Cenários               |                                                                                                                                               |
| Artefatos (elicitação de requisitos) |          [INT07](../elicitacao/introspeccao.md)<br/> [Q13](../elicitacao/questionario.md)<br/> [ST11](../elicitacao/storytelling.md)          |
|             Comentários              |                                                            Implementação completa                                                             |
|            Funcionalidade            |                                              ![Vídeo RF05 RF23](./assets/forward/RF05-RF23.mp4)                                               |

<div style="text-align: center">
<p> Tabela 6: RF05 (Fonte: autor, 2023).</p>
</div>

**RF06**
|                 RF06                 |                                        Deve ser possível assistir partidas de outras pessoas                                        |
| :----------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E11](../modelagem/agil/backlog/#e11-torneios)                                            |
|                 Tema                 |                                                              Torneios                                                               |
|         História de Usuário          | [US23](../modelagem/agil/us/#us23) Eu, como usuário, desejo assistir partidas de outros jogadores, para observar as técnicas usadas |
|                Léxico                |                                                                                                                                     |
|             Casos de uso             |                                                                                                                                     |
|               Cenários               |                                                                                                                                     |
| Artefatos (elicitação de requisitos) |                                                [ST06](../elicitacao/storytelling.md)                                                |
|             Comentários              |                                                       Implementação completa                                                        |
|            Funcionalidade            |                                              ![Vídeo RF06](./assets/forward/RF06.mp4)                                               |

<div style="text-align: center">
<p> Tabela 7: RF06 (Fonte: autor, 2023).</p>
</div>

**RF07**
|                 RF07                 |                                              Deve ser possível configurar a dificuldade da partida contra o computador                                              |
| :----------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                    [E01](../modelagem/agil/backlog/#e01-configuracao-de-partida)                                                    |
|                 Tema                 |                                                                              Partidas                                                                               |
|         História de Usuário          | [US02](../modelagem/agil/us/#us02) Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida |
|                Léxico                |                                                                                                                                                                     |
|             Casos de uso             |                                                                                                                                                                     |
|               Cenários               |                                                                                                                                                                     |
| Artefatos (elicitação de requisitos) |                                                               [INT04](../elicitacao/introspeccao.md)                                                                |
|             Comentários              |                                                                       Implementação completa                                                                        |
|            Funcionalidade            |                                                      ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4)                                                      |

<div style="text-align: center">
<p> Tabela 8: RF07 (Fonte: autor, 2023).</p>
</div>

**RF08**
|                 RF08                 |                                              Deve ser possível configurar a modalidade de jogo ao iniciar uma partida                                               |
| :----------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                    [E01](../modelagem/agil/backlog/#e01-configuracao-de-partida)                                                    |
|                 Tema                 |                                                                              Partidas                                                                               |
|         História de Usuário          | [US02](../modelagem/agil/us/#us02) Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida |
|                Léxico                |                                                                                                                                                                     |
|             Casos de uso             |                                                                                                                                                                     |
|               Cenários               |                                                                                                                                                                     |
| Artefatos (elicitação de requisitos) |                     [GLO01](../elicitacao/glossario.md)<br/> [INT03](../elicitacao/introspeccao.md)<br/> [ST04](../elicitacao/storytelling.md)                      |
|             Comentários              |                                                                       Implementação completa                                                                        |
|            Funcionalidade            |                                                      ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4)                                                      |

<div style="text-align: center">
<p> Tabela 9: RF08 (Fonte: autor, 2023).</p>
</div>

**RF09**
|                 RF09                 |                                  Deve ser possível configurar o tempo de duração da partida e incremento ao iniciar uma partida                                  |
| :----------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                  [E01](../modelagem/agil/backlog/#e01-configuracao-de-partida)                                                   |
|                 Tema                 |                                                                             Partidas                                                                             |
|         História de Usuário          | [US01](../modelagem/agil/us/#us01) Eu, como usuário, desejo configurar o tempo de partida e incremento ao iniciar uma partida para adequar ao meu estilo de jogo |
|                Léxico                |                                                                                                                                                                  |
|             Casos de uso             |                                                                                                                                                                  |
|               Cenários               |                                                                                                                                                                  |
| Artefatos (elicitação de requisitos) |                     [ENT01](../elicitacao/entrevista.md)<br/> [GLO02](../elicitacao/glossario.md)<br/> [ST04](../elicitacao/storytelling.md)                     |
|             Comentários              |                                                                      Implementação completa                                                                      |
|            Funcionalidade            |                                                             ![Video RF09](./assets/forward/RF09.mp4)                                                             |

<div style="text-align: center">
<p> Tabela 10: RF09 (Fonte: autor, 2023).</p>
</div>

**RF10**
|                 RF10                 |                             Deve ser possível configurar um estilo de jogo para o robô, baseado em jogadores famosos, nas partidas contra o computador                             |
| :----------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                         [E02](../modelagem/agil/backlog/#e02-partida-contra-o-computador)                                                          |
|                 Tema                 |                                                                                      Partidas                                                                                      |
|         História de Usuário          | [US05](../modelagem/agil/us/#us05) Eu, como usuário, desejo configurar um estilo de jogo para o robô, baseado em jogadores famosos, para me preparar para os campeonatos de xadrez |
|                Léxico                |                                                                                                                                                                                    |
|             Casos de uso             |                                                                                                                                                                                    |
|               Cenários               |                                                                                                                                                                                    |
| Artefatos (elicitação de requisitos) |                                                  [ENT02](../elicitacao/entrevista.md)<br/> [ST04](../elicitacao/storytelling.md)                                                   |
|             Comentários              |                                                                             Implementação Inexistente                                                                              |
|            Funcionalidade            |                                                                                         -                                                                                          |

<div style="text-align: center">
<p> Tabela 11: RF10 (Fonte: autor, 2023).</p>
</div>

**RF11**
|                 RF11                 |                                                           Deve ser possível consultar as estatísticas das partidas anteriores                                                            |
| :----------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                              [E08](../modelagem/agil/backlog/#e08-estatisticas-de-partidas)                                                              |
|                 Tema                 |                                                                                       Ranqueamento                                                                                       |
|         História de Usuário          |                            [US18](../modelagem/agil/us/#us18) Eu, como usuário, desejo consultar as estatísticas das minhas partidas, para me preparar melhor                            |
|                Léxico                |                                                                                                                                                                                          |
|             Casos de uso             |                                                                                                                                                                                          |
|               Cenários               |                                                                                                                                                                                          |
| Artefatos (elicitação de requisitos) |                                                     [ST09](../elicitacao/storytelling.md)<br/> [Q02](../elicitacao/questionario.md)                                                      |
|             Comentários              | Implementação incompleta, é possível consultar a partida e após isso utilizar o computador para observar melhores lances, porém não há estatisticas relacionadas as partidas diretamente |
|            Funcionalidade            |                                                                         ![Vídeo RF11](./assets/forward/RF11.mp4)                                                                         |

<div style="text-align: center">
<p> Tabela 12: RF11 (Fonte: autor, 2023).</p>
</div>

**RF12**
|                 RF12                 |                                                        Deve ser possível consultar as regras da modalidade de jogo em andamento                                                         |
| :----------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                                  [E06](../modelagem/agil/backlog/#e06-estudar-xadrez)                                                                   |
|                 Tema                 |                                                                                        Tutoriais                                                                                        |
|         História de Usuário          |         [US14](../modelagem/agil/us/#us14) Eu, como usuário, desejo ter acesso às regras utilizadas na modalidade de xadrez durante a partida, para não me sentir desorientado          |
|                Léxico                |                                                                                                                                                                                         |
|             Casos de uso             |                                                                                                                                                                                         |
|               Cenários               |                                                                                                                                                                                         |
| Artefatos (elicitação de requisitos) |                                                                           [GLO03](../elicitacao/glossario.md)                                                                           |
|             Comentários              | Implementação incompleta, o modo escolhido é uma breve introdução que aparece somente no início da partida e somente para usuários "logados", ou seja, utilizando a conta da plataforma |
|            Funcionalidade            |                                                                                            -                                                                                            |

<div style="text-align: center">
<p> Tabela 13: RF12 (Fonte: autor, 2023).</p>
</div>

**RF13**
|                 RF13                 |                                                  Deve ser possível consultar um tutorial de uso do aplicativo                                                  |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                    [E05](../modelagem/agil/backlog/#e05-manual-do-usuario)                                                     |
|                 Tema                 |                                                                           Tutoriais                                                                            |
|         História de Usuário          | [US05](../modelagem/agil/us/#us11) Eu, como usuário, desejo ter acesso à uma seção de tutorial do aplicativo, para me sentir seguro durante momentos de dúvida |
|                Léxico                |                                                                                                                                                                |
|             Casos de uso             |                                                                                                                                                                |
|               Cenários               |                                                                                                                                                                |
| Artefatos (elicitação de requisitos) |                                                             [INT08](../elicitacao/introspeccao.md)                                                             |
|             Comentários              |                                                                   Implementação inexistente                                                                    |
|            Funcionalidade            |                                                                               -                                                                                |

<div style="text-align: center">
<p> Tabela 14: RF13 (Fonte: autor, 2023).</p>
</div>

**RF14**
|                 RF14                 |                                     Deve ser possível elaborar tutoriais para outros jogadores                                     |
| :----------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                        [E07](../modelagem/agil/backlog/#e07-ensinar-xadrez)                                        |
|                 Tema                 |                                                             Tutoriais                                                              |
|         História de Usuário          | [US07](../modelagem/agil/us/#us15) Eu, como usuário, desejo cadastrar tutoriais para outros usuários, para auxiliar outras pessoas |
|                Léxico                |                                                                                                                                    |
|             Casos de uso             |                                                                                                                                    |
|               Cenários               |                                                                                                                                    |
| Artefatos (elicitação de requisitos) |                                               [ST13](../elicitacao/storytelling.md)                                                |
|             Comentários              |                               Implementação inexistente, somente pode ser criado no Lichess via web                                |
|            Funcionalidade            |                                                                 -                                                                  |

<div style="text-align: center">
<p> Tabela 15: RF14 (Fonte: autor, 2023).</p>
</div>

**RF15**    
|                 RF15                 |                                     Deve ser possível escolher o nível do oponente ao iniciar uma partida contra outro jogador                                      |
| :----------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                    [E01](../modelagem/agil/backlog/#e01-configuracao-de-partida)                                                    |
|                 Tema                 |                                                                              Partidas                                                                               |
|         História de Usuário          | [US02](../modelagem/agil/us/#us02) Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida |
|                Léxico                |                                                                                                                                                                     |
|             Casos de uso             |                                                                                                                                                                     |
|               Cenários               |                                                                                                                                                                     |
| Artefatos (elicitação de requisitos) |                                           [Q08](../elicitacao/questionario.md)<br/> [Q04](../elicitacao/questionario.md)                                            |
|             Comentários              |                          Implementação incompleta, apenas usuarios com conta na plataforma conseguem selecionar o nível de seus oponentes                           |
|            Funcionalidade            |                                                      ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4)                                                      |

<div style="text-align: center">
<p> Tabela 16: RF15 (Fonte: autor, 2023).</p>
</div>

**RF16**    
|                 RF16                 |                                                     Deve ser possível jogar partidas não ranqueadas                                                      |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                  [E04](../modelagem/agil/backlog/#e04-partidas-casuais)                                                  |
|                 Tema                 |                                                                         Partidas                                                                         |
|         História de Usuário          | [US08](../modelagem/agil/us/#us08) Eu, como usuário, desejo jogar partidas casuais sem interferir no meu ranqueamento, para não diminuir minha pontuação |
|                Léxico                |                                                                                                                                                          |
|             Casos de uso             |                                                                                                                                                          |
|               Cenários               |                                                                                                                                                          |
| Artefatos (elicitação de requisitos) |                                                          [ST03](../elicitacao/storytelling.md)                                                           |
|             Comentários              |                                                                  Implementação completa                                                                  |
|            Funcionalidade            |                                                         ![Vídeo RF16](./assets/forward/RF16.mp4)                                                         |

<div style="text-align: center">
<p> Tabela 17: RF16 (Fonte: autor, 2023).</p>
</div>

**RF17**
|                 RF17                 |                                   Deve ser possível jogar partidas online sem criar uma conta                                    |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                      [E04](../modelagem/agil/backlog/#e04-partidas-casuais)                                      |
|                 Tema                 |                                                             Partidas                                                             |
|         História de Usuário          | [US09](../modelagem/agil/us/#us09) Eu, como usuário, desejo jogar partidas online sem precisar criar uma conta, para me divertir |
|                Léxico                |                                                                                                                                  |
|             Casos de uso             |                                                                                                                                  |
|               Cenários               |                                                                                                                                  |
| Artefatos (elicitação de requisitos) |                                               [Q09](../elicitacao/questionario.md)                                               |
|             Comentários              |                                                      Implementação completa                                                      |
|            Funcionalidade            |                                    ![Vídeo RF08, RF07M](./assets/forward/RF08-RF07-RF15.mp4)                                     |

<div style="text-align: center">
<p> Tabela 18: RF17 (Fonte: autor, 2023).</p>
</div>


**RF18**
|                 RF18                 |                                                  Deve ser possível jogar uma partida de xadrez contra o computador                                                  |
| :----------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                  [E02](../modelagem/agil/backlog/#e02-partida-contra-o-computador)                                                  |
|                 Tema                 |                                                                              Partidas                                                                               |
|         História de Usuário          | [US03](../modelagem/agil/us/#us03) Eu, como usuário, desejo escolher jogar contra o computador ou contra um jogador para refletir as minhas necessidades do momento |
|                Léxico                |                                                                                                                                                                     |
|             Casos de uso             |                                                                                                                                                                     |
|               Cenários               |                                                                                                                                                                     |
| Artefatos (elicitação de requisitos) |                                                               [INT01](../elicitacao/introspeccao.md)                                                                |
|             Comentários              |                                                                       Implementação completa                                                                        |
|            Funcionalidade            |                                                              ![Vídeo RF18](./assets/forward/RF18.mp4)                                                               |

<div style="text-align: center">
<p> Tabela 19: RF18 (Fonte: autor, 2023).</p>
</div>

**RF19**
|                 RF19                 |                                Deve ser possível jogar uma partida de xadrez contra outro jogador aleatório ou escolhido                                 |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                              [E03](../modelagem/agil/backlog/#e03-partida-contra-oponente)                                               |
|                 Tema                 |                                                                         Partidas                                                                         |
|         História de Usuário          | [US06](../modelagem/agil/us/#us06) Eu, como usuário, desejo escolher o meu oponente podendo filtrar por nome e nível, para não me frustrar com a partida |
|                Léxico                |                                                                                                                                                          |
|             Casos de uso             |                                                                                                                                                          |
|               Cenários               |                                                                                                                                                          |
| Artefatos (elicitação de requisitos) |               [INT02](../elicitacao/introspeccao.md)<br/> [ST02](../elicitacao/storytelling.md)<br/> [ST05](../elicitacao/storytelling.md)               |
|             Comentários              |                                                                Implementação Inexistente                                                                 |
|            Funcionalidade            |                                                                            -                                                                             |

<div style="text-align: center">
<p> Tabela 20: RF19 (Fonte: autor, 2023).</p>
</div>

**RF20**
|                 RF20                 |                                      Deve ser possível pausar uma partida contra o computador                                       |
| :----------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                  [E02](../modelagem/agil/backlog/#e02-partida-contra-o-computador)                                  |
|                 Tema                 |                                                              Partidas                                                               |
|         História de Usuário          | [US04](../modelagem/agil/us/#us04)Eu, como usuário, desejo poder pausar uma partida contra o computador para poder retomá-la depois |
|                Léxico                |                                                                                                                                     |
|             Casos de uso             |                                                                                                                                     |
|               Cenários               |                                                                                                                                     |
| Artefatos (elicitação de requisitos) |                                               [INT05](../elicitacao/introspeccao.md)                                                |
|             Comentários              |                                                      Implementação inexistente                                                      |
|            Funcionalidade            |                                                                  -                                                                  |

<div style="text-align: center">
<p> Tabela 21: RF20 (Fonte: autor, 2023).</p>
</div>

**RF21**
|                 RF21                 |                                                      Deve ser possível receber notificações sobre torneios ao vivo                                                      |
| :----------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                                             [E11](../modelagem/agil/backlog/#e11-torneios)                                                              |
|                 Tema                 |                                                                                Torneios                                                                                 |
|         História de Usuário          | [US24](../modelagem/agil/us/#us24) Eu, como usuário, desejo ser notificado quando partidas de outros jogadores iniciarem, para não perder partidas importantes para mim |
|                Léxico                |                                                                                                                                                                         |
|             Casos de uso             |                                                                                                                                                                         |
|               Cenários               |                                                                                                                                                                         |
| Artefatos (elicitação de requisitos) |                                                                  [Q03](../elicitacao/questionario.md)                                                                   |
|             Comentários              |                                                                        Implementação inexistente                                                                        |
|            Funcionalidade            |                                                                                    -                                                                                    |

<div style="text-align: center">
<p> Tabela 22: RF21 (Fonte: autor, 2023).</p>
</div>

**RF22**
|                 RF22                 |                                    Deve ser possível resolver quebra cabeças elaborados por outros jogadores                                    |
| :----------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                              [E06](../modelagem/agil/backlog/#e06-estudar-xadrez)                                               |
|                 Tema                 |                                                                    Tutoriais                                                                    |
|         História de Usuário          | [US13](../modelagem/agil/us/#us13) Eu, como usuário, desejo aprimorar movimentos de xadrez por meio de quebra cabeças, para me sentir desafiado |
|                Léxico                |                                                                                                                                                 |
|             Casos de uso             |                                                                                                                                                 |
|               Cenários               |                                                                                                                                                 |
| Artefatos (elicitação de requisitos) |           [GLO04](../elicitacao/glossario.md)<br/> [INT12](../elicitacao/introspeccao.md)<br/> [ST12](../elicitacao/storytelling.md)            |
|             Comentários              |                                                             Implementação completa                                                              |
|            Funcionalidade            |                                                    ![Vídeo RF22](./assets/forward/RF22.mp4)                                                     |

<div style="text-align: center">
<p> Tabela 23: RF22 (Fonte: autor, 2023).</p>
</div>

**RF23**
|                 RF23                 |                                     Deve ser possível resolver tutoriais elaborados por outros jogadores                                      |
| :----------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                             [E06](../modelagem/agil/backlog/#e06-estudar-xadrez)                                              |
|                 Tema                 |                                                                   Tutoriais                                                                   |
|         História de Usuário          | [US12](../modelagem/agil/us/#us12) Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho |
|                Léxico                |                                                                                                                                               |
|             Casos de uso             |                                                                                                                                               |
|               Cenários               |                                                                                                                                               |
| Artefatos (elicitação de requisitos) |                                                     [ST13](../elicitacao/storytelling.md)                                                     |
|             Comentários              |                                                            Implementação completa                                                             |
|            Funcionalidade            |                                              ![Vídeo RF05 RF23](./assets/forward/RF05-RF23.mp4)                                               |

<div style="text-align: center">
<p> Tabela 24: RF23 (Fonte: autor, 2023).</p>
</div>

**RF24**
|                 RF24                 |                                      Deve ser possível trocar mensagens com outros jogadores                                       |
| :----------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                 [E10](..//2022.2-Lichess/modelagem/agil/backlog/#e10-comunicacao)                                  |
|                 Tema                 |                                                            Socialização                                                            |
|         História de Usuário          | [US22](../modelagem/agil/us/#us22) Eu, como usuário, desejo trocar mensagens com outros jogadores, para fortalecer minhas amizades |
|                Léxico                |                                                                                                                                    |
|             Casos de uso             |                                                                                                                                    |
|               Cenários               |                                                                                                                                    |
| Artefatos (elicitação de requisitos) |                                               [ST08](../elicitacao/storytelling.md)                                                |
|             Comentários              |                                                       Implementação completa                                                       |
|            Funcionalidade            |                                              ![Vídeo RF24](./assets/forward/RF24.mp4)                                              |

<div style="text-align: center">
<p> Tabela 25: RF24 (Fonte: autor, 2023).</p>
</div>

**RF25**
|                 RF25                 |                                    Deve ser possível visualizar dados sobre os quebra-cabeças concluídos                                     |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                     [E09](../modelagem/agil/backlog/#e09-estatisticas-de-quebra-cabecas)                                     |
|                 Tema                 |                                                                 Ranqueamento                                                                 |
|         História de Usuário          | [US20](../modelagem/agil/us/#us20) Eu, como usuário, desejo consultar as estatísticas dos quebra cabeças resolvidos, para me preparar melhor |
|                Léxico                |                                                                                                                                              |
|             Casos de uso             |                                                                                                                                              |
|               Cenários               |                                                                                                                                              |
| Artefatos (elicitação de requisitos) |                                                     [Q02](../elicitacao/questionario.md)                                                     |
|             Comentários              |                                                          Implementação inexistente                                                           |
|            Funcionalidade            |                                                                      -                                                                       |

<div style="text-align: center">
<p> Tabela 26: RF25 (Fonte: autor, 2023).</p>
</div>

**RF26**
|                 RF26                 |                                   Deve ser possível visualizar e filtrar o ranqueamento de jogadores                                   |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                     [E08](../modelagem/agil/backlog/#e08-estatisticas-de-partidas)                                     |
|                 Tema                 |                                                              Ranqueamento                                                              |
|         História de Usuário          | [US19](../modelagem/agil/us/#us19) Eu, como usuário, desejo visualizar e filtrar o ranqueamento dos jogadores, para me manter motivado |
|                Léxico                |                                                                                                                                        |
|             Casos de uso             |                                                                                                                                        |
|               Cenários               |                                                                                                                                        |
| Artefatos (elicitação de requisitos) |                            [Q06](../elicitacao/questionario.md)<br/> [ST10](../elicitacao/storytelling.md)                             |
|             Comentários              |                                                       Implementação inexistente                                                        |
|            Funcionalidade            |                                                                   -                                                                    |

<div style="text-align: center">
<p> Tabela 27: RF26 (Fonte: autor, 2023).</p>
</div>

**RF27**
|                 RF27                 |                                    Não deve ser possível pausar uma partida contra outro jogador                                    |
| :----------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                    [E03](../modelagem/agil/backlog/#e03-partida-contra-oponente)                                    |
|                 Tema                 |                                                              Partidas                                                               |
|         História de Usuário          | [US07](../modelagem/agil/us/#us07) Eu, como usuário, desejo que meu oponente não possa pausar uma partida, para manter o jogo justo |
|                Léxico                |                                                                                                                                     |
|             Casos de uso             |                                                                                                                                     |
|               Cenários               |                                                                                                                                     |
| Artefatos (elicitação de requisitos) |                                               [INT06](../elicitacao/introspeccao.md)                                                |
|             Comentários              |                                                       Implementação completa                                                        |
|            Funcionalidade            |                                              ![Vídeo RF16](./assets/forward/RF16.mp4)                                               |

<div style="text-align: center">
<p> Tabela 28: RF27 (Fonte: autor, 2023).</p>
</div>

**RF28**
|                 RF28                 |                                     Deve ser possível criar quebra cabeça para outros jogadores resolverem                                     |
| :----------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                              [E07](../modelagem/agil/backlog/#e07-ensinar-xadrez)                                              |
|                 Tema                 |                                                                   Tutoriais                                                                    |
|         História de Usuário          | [US16](../modelagem/agil/us/#us16) Eu, como usuário, desejo criar quebra cabeças para outros usuários resolverem, para desafiar outras pessoas |
|                Léxico                |                                                                                                                                                |
|             Casos de uso             |                                                                                                                                                |
|               Cenários               |                                                                                                                                                |
| Artefatos (elicitação de requisitos) |                                [GLO04](../elicitacao/glossario.md)<br/> [INT15](../elicitacao/introspeccao.md)                                 |
|             Comentários              |                                                           Implementação inexistente                                                            |
|            Funcionalidade            |                                                                       -                                                                        |

<div style="text-align: center">
<p> Tabela 29: RF28 (Fonte: autor, 2023).</p>
</div>

### Requisitos Não Funcionais

**RNF01**  
|           RNF01           | Sistema deve ter barra de navegação que siga padrões de UI/UX bem estabelecidos no mercado |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                                                                                            |
| Especificação Suplementar |                                                                                            |
|        Comentários        |                                   Implementação completa                                   |

**RNF02**  
|           RNF02           | Usuário deve conseguir padronizar sua interface de maneira única |
| :-----------------------: | :--------------------------------------------------------------: |
|            NFR            |                                                                  |
| Especificação Suplementar |                                                                  |
|        Comentários        |                      Implementação completa                      |

**RNF03**  
|           RNF03           | Sistema deve ter no máximo 5 interações por funcionalidade |
| :-----------------------: | :--------------------------------------------------------: |
|            NFR            |                                                            |
| Especificação Suplementar |                                                            |
|        Comentários        |                   Implementação completa                   |

**RNF04**  
|           RNF04           | Sistema deve ter animações simples de no máximo 300 milésimos |
| :-----------------------: | :-----------------------------------------------------------: |
|            NFR            |                                                               |
| Especificação Suplementar |                                                               |
|        Comentários        |                    Implementação completa                     |

**RNF05**  
|           RNF05           | Sistema deve apresentar acesso a todas as funcionalidades logo no início do app |
| :-----------------------: | :-----------------------------------------------------------------------------: |
|            NFR            |                                                                                 |
| Especificação Suplementar |                                                                                 |
|        Comentários        |                             Implementação completa                              |

**RNF06**  
|           RNF06           | Sistema deve permitir customização de tema (claro e escuro) |
| :-----------------------: | :---------------------------------------------------------: |
|            NFR            |                                                             |
| Especificação Suplementar |                                                             |
|        Comentários        |                   Implementação completa                    |

**RNF07**  
|           RNF07           | Sistema deve permitir customização de linguagem (português, inglês e espanhol) |
| :-----------------------: | :----------------------------------------------------------------------------: |
|            NFR            |                                                                                |
| Especificação Suplementar |                                                                                |
|        Comentários        |                             Implementação completa                             |

**RNF08**  
|           RNF08           | Sistema deve permitir customização de som (habilitar e desabilitar efeitos sonoros) |
| :-----------------------: | :---------------------------------------------------------------------------------: |
|            NFR            |                                                                                     |
| Especificação Suplementar |                                                                                     |
|        Comentários        |                               Implementação completa                                |

**RNF09**  
|           RNF09           | Sistema deve estar online todos os dias da semana, durante todo o dia |
| :-----------------------: | :-------------------------------------------------------------------: |
|            NFR            |                                                                       |
| Especificação Suplementar |                                                                       |
|        Comentários        |                        Implementação completa                         |

**RNF10**  
|           RNF10           | Sistema deve informar sobre manutenções e possíveis tempos em que o servidor estará offline via notificação |
| :-----------------------: | :---------------------------------------------------------------------------------------------------------: |
|            NFR            |                                                                                                             |
| Especificação Suplementar |                                                                                                             |
|        Comentários        |                                          Implementação inexistente                                          |

**RNF11**  
|           RNF11           | Sistema deve realizar backup automático dos dados do usuário todo dia em horário com menor acesso (a ser determinado pelo sistema) |
| :-----------------------: | :--------------------------------------------------------------------------------------------------------------------------------: |
|            NFR            |                                                                                                                                    |
| Especificação Suplementar |                                                                                                                                    |
|        Comentários        |                                                     Implementação inexistente                                                      |

**RNF12**  
|           RNF12           | Sistema deve ser compatível com Android (de versão 9.0 até atual) |
| :-----------------------: | :---------------------------------------------------------------: |
|            NFR            |                                                                   |
| Especificação Suplementar |                                                                   |
|        Comentários        |                      Implementação completa                       |

**RNF13**  
|           RNF13           | Sistema deve ser compatível com iOS (de versão 12 até atual) |
| :-----------------------: | :----------------------------------------------------------: |
|            NFR            |                                                              |
| Especificação Suplementar |                                                              |
|        Comentários        |                    Implementação completa                    |

**RNF14**  
|           RNF14           | Sistema deve ser disponível na Web |
| :-----------------------: | :--------------------------------: |
|            NFR            |                                    |
| Especificação Suplementar |                                    |
|        Comentários        |       Implementação completa       |

**RNF15**  
|           RNF15           | Sistema deve ser responsivo |
| :-----------------------: | :-------------------------: |
|            NFR            |                             |
| Especificação Suplementar |                             |
|        Comentários        |   Implementação completa    |

**RNF16**  
|           RNF16           | Sistema deve escurecer a tela em caso de inatividade maior de X minutos definido pelo usuário |
| :-----------------------: | :-------------------------------------------------------------------------------------------: |
|            NFR            |                                                                                               |
| Especificação Suplementar |                                                                                               |
|        Comentários        |                                   Implementação inexistente                                   |

**RNF17**  
|           RNF17           | Dispositivo deve bloquear tela em caso de inatividade prolongada |
| :-----------------------: | :--------------------------------------------------------------: |
|            NFR            |                                                                  |
| Especificação Suplementar |                                                                  |
|        Comentários        |                    Implementação inexistente                     |

**RNF18**  
|           RNF18           | Sistema deve guardar a última tela em que o usuário está |
| :-----------------------: | :------------------------------------------------------: |
|            NFR            |                                                          |
| Especificação Suplementar |                                                          |
|        Comentários        |                  Implementação completa                  |

**RNF19**  
|           RNF19           | Sistema deve permitir jogar partidas mesmo sem conexão de internet |
| :-----------------------: | :----------------------------------------------------------------: |
|            NFR            |                                                                    |
| Especificação Suplementar |                                                                    |
|        Comentários        |                       Implementação completa                       |

**RNF20**  
|           RNF20           | Sistema deve permitir acessar o aplicativo mesmo sem conexão de internet |
| :-----------------------: | :----------------------------------------------------------------------: |
|            NFR            |                                                                          |
| Especificação Suplementar |                                                                          |
|        Comentários        |                          Implementação completa                          |

**RNF21**  
|           RNF21           | Sistema deve ter uma taxa de atraso abaixa de 100 milisSegundos |
| :-----------------------: | :-------------------------------------------------------------: |
|            NFR            |                                                                 |
| Especificação Suplementar |                                                                 |
|        Comentários        |                     Implementação completa                      |


## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acessado em: 22/01/2023

[2] POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental. Acessado em 22/01/2023

## Histórico de Versão

| Versão | Data       | Descrição                                                                                                             | Autor(es)           | Revisor(es)   |
| ------ | ---------- | --------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------- |
| `1.0`  | 22/01/2023 | Criação do documento                                                                                                  | Lucas Macedo e Davi | Lucas Gabriel |
| `1.1`  | 23/01/2023 | Adicionando partes do artefato                                                                                        | Lucas Macedo e Davi | Lucas Gabriel |
| `1.2`  | 23/01/2023 | Adição gravação requisitos                                                                                            | Mauricio Machado    | Davi          |
| `2.0`  | 29/01/2023 | Ajustes na metodologia, modificação de todas tabelas dos requisitos funcionais e adição dos requisitos não funcionais | Lucas Gabriel       |               |
