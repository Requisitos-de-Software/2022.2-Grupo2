# Backward From

## Introdução

A técnica de pós-rastreabilidade Backward From é o processo de rastrear os requisitos de volta até sua origem. Isso inclui identificar qual é o objetivo do requisito, quem o solicitou, quais são os requisitos relacionados e como eles se relacionam entre si. Esta técnica é importante porque permite entender a origem e o contexto dos requisitos, o que pode ser útil para tomar decisões sobre como implementá-los e garantir que eles estejam alinhados com as necessidades do negócio. O Backward From também é importante para garantir que os requisitos estejam completos e coerentes. É usado para identificar requisitos que possam estar faltando ou que possam ser redundantes, e para verificar se os requisitos são consistentes com as necessidades do negócio e com os requisitos relacionados.

## Requisitos Funcionais

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

| Identificador | Requisito | Origem | Elos
| :-: | :-: | :-: | :-: |
| RF01 | Deve existir um sistema de recompensas para incentivar os jogadores | [Q04](../elicitacao/questionario.md#requisitos-elicitados) | [EF01](#ef01)
| RF02 | Deve existir uma apresentação inicial do aplicativo para o usuário no primeiro acesso | [Q10](../elicitacao/questionario.md#requisitos-elicitados) | [EF02](#ef02)
| RF03 | Deve haver uma classificação, em termos de nível, dos jogadores. | [Q04](../elicitacao/questionario.md#requisitos-elicitados)<br/> [Q08](../elicitacao/questionario.md#requisitos-elicitados) | [EF03](#ef03)
| RF04 | Deve ser possível adicionar outros jogadores | [ST07](../elicitacao/storytelling.md#requisitos-elicitados) | [EF04](#ef04)
| RF05 | Deve ser possível aprender movimentos de xadrez por meio de tutoriais | [INT07](../elicitacao/introspeccao.md#elicitação-de-requisitos)<br/> [Q13](../elicitacao/questionario.md#requisitos-elicitados)<br/> [ST11](../elicitacao/storytelling.md#requisitos-elicitados) | [EF05](#ef05)
| RF06 | Deve ser possível assistir partidas de outras pessoas | [ST06](../elicitacao/storytelling.md#requisitos-elicitados) | [EF06](#ef06)
| RF07 | Deve ser possível configurar a dificuldade da partida contra o computador | [INT04](../elicitacao/introspeccao.md#elicitação-de-requisitos) | [EF07](#ef07)
| RF08 | Deve ser possível configurar a modalidade de jogo ao iniciar uma partida. | [GLO01](../elicitacao/glossario.md#requisitos-elicitados)<br/> [INT03](../elicitacao/introspeccao.md#elicitação-de-requisitos)<br/> [ST04](../elicitacao/storytelling.md#requisitos-elicitados) | [EF08](#ef08)
| RF09 | Deve ser possível configurar o tempo de duração da partida e incremento ao iniciar uma partida. | [ENT01](../elicitacao/entrevista.md#resultados)<br/> [GLO02](../elicitacao/glossario.md#requisitos-elicitados)<br/> [ST04](../elicitacao/storytelling.md#requisitos-elicitados) | [EF09](#ef09)
| RF10 | Deve ser possível configurar um estilo de jogo para o robô, baseado em jogadores famosos, nas partidas contra o computador. | [ENT02](../elicitacao/entrevista.md#resultados)<br/> [ST04](../elicitacao/storytelling.md#requisitos-elicitados) | [EF10](#ef10)
| RF11 | Deve ser possível consultar as estatísticas das partidas anteriores | [ST09](../elicitacao/storytelling.md#requisitos-elicitados)<br/> [Q02](../elicitacao/questionario.md#requisitos-elicitados) | [EF11](#ef11)
| RF12 | Deve ser possível consultar as regras da modalidade de jogo em andamento. | [GLO03](../elicitacao/glossario.md#requisitos-elicitados) | [EF12](#ef12)
| RF13 | Deve ser possível consultar um tutorial de uso do aplicativo | [INT08](../elicitacao/introspeccao.md#elicitação-de-requisitos) | [EF13](#ef13)
| RF14 | Deve ser possível elaborar tutoriais para outros jogadores | [ST13](../elicitacao/storytelling.md#requisitos-elicitados) | [EF14](#ef14)
| RF15 | Deve ser possível escolher o nível do oponente ao iniciar uma partida contra outro jogador | [Q08](../elicitacao/questionario.md#requisitos-elicitados)<br/> [Q04](../elicitacao/questionario.md#requisitos-elicitados) | [EF15](#ef15)
| RF16 | Deve ser possível jogar partidas não ranqueadas | [ST03](../elicitacao/storytelling.md#requisitos-elicitados) | [EF16](#ef16)
| RF17 | Deve ser possível jogar partidas online sem criar uma conta | [Q09](../elicitacao/questionario.md#requisitos-elicitados) | [EF17](#ef17)
| RF18 | Deve ser possível jogar uma partida de xadrez contra o computador | [INT01](../elicitacao/introspeccao.md#elicitação-de-requisitos) | [EF18](#ef18)
| RF19 | Deve ser possível jogar uma partida de xadrez contra outro jogador aleatório ou escolhido. | [INT02](../elicitacao/introspeccao.md#elicitação-de-requisitos)<br/> [ST02](../elicitacao/storytelling.md#requisitos-elicitados)<br/> [ST05](../elicitacao/storytelling.md#requisitos-elicitados) | [EF19](#ef19)
| RF20 | Deve ser possível pausar uma partida contra o computador | [INT05](../elicitacao/introspeccao.md#elicitação-de-requisitos) | [EF20](#ef20)
| RF21 | Deve ser possível receber notificações sobre torneios ao vivo | [Q03](../elicitacao/questionario.md#requisitos-elicitados) | [EF21](#ef21)
| RF22 | Deve ser possível resolver quebra cabeças elaborados por outros jogadores. | [GLO04](../elicitacao/glossario.md#requisitos-elicitados)<br/> [INT12](../elicitacao/introspeccao.md#elicitação-de-requisitos)<br/> [ST12](../elicitacao/storytelling.md#requisitos-elicitados) | [EF22](#ef22)
| RF23 | Deve ser possível resolver tutoriais elaborados por outros jogadores | [ST13](../elicitacao/storytelling.md#requisitos-elicitados) | [EF23](#ef23)
| RF24 | Deve ser possível trocar mensagens com outros jogadores | [ST08](../elicitacao/storytelling.md#requisitos-elicitados) | [EF24](#ef24)
| RF25 | Deve ser possível visualizar dados sobre os quebra-cabeças concluídos | [Q02](../elicitacao/questionario.md#requisitos-elicitados) | [EF25](#ef25)
| RF26 | Deve ser possível visualizar e filtrar o ranqueamento de jogadores | [Q06](../elicitacao/questionario.md#requisitos-elicitados)<br/> [ST10](../elicitacao/storytelling.md#requisitos-elicitados) | [EF26](#ef26)
| RF27 | Não deve ser possível pausar uma partida contra outro jogador | [INT06](../elicitacao/introspeccao.md#elicitação-de-requisitos) | [EF27](#ef27)
| RF28 | Deve ser possível criar quebra cabeça para outros jogadores resolverem. | [GLO04](../elicitacao/glossario.md#requisitos-elicitados)<br/> [INT15](../elicitacao/introspeccao.md#elicitação-de-requisitos) | [EF28](#ef28)

## Requisitos Não Funcionais

## Elos Funcionais

### EF01

**Categoria:**
**Elos:**

### EF02

**Categoria:**
**Elos:**

### EF03

**Categoria:**
**Elos:**

### EF04

**Categoria:**
**Elos:**

### EF05

**Categoria:**
**Elos:**

### EF06

**Categoria:**
**Elos:**

### EF07

**Categoria:**
**Elos:**

### EF08

**Categoria:**
**Elos:**

### EF09

**Categoria:**
**Elos:**

### EF10

**Categoria:**
**Elos:**

### EF11

**Categoria:**
**Elos:**

### EF12

**Categoria:**
**Elos:**

### EF13

**Categoria:**
**Elos:**

### EF14

**Categoria:**
**Elos:**

### EF15

**Categoria:**
**Elos:**

### EF16

**Categoria:**
**Elos:**

### EF17

**Categoria:**
**Elos:**

### EF18

**Categoria:**
**Elos:**

### EF19

**Categoria:**
**Elos:**

### EF20

**Categoria:**
**Elos:**

### EF21

**Categoria:**
**Elos:**

### EF22

**Categoria:**
**Elos:**

### EF23

**Categoria:**
**Elos:**

### EF24

**Categoria:**
**Elos:**

### EF25

**Categoria:**
**Elos:**

### EF26

**Categoria:**
**Elos:**

### EF27

**Categoria:**
**Elos:**

### EF28

**Categoria:**
**Elos:**

## Elos Não Funcionais

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 44 slides. color. Disponível no [link](https://aprender3.unb.br/pluginfile.php/1668237/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 22 jan. 2023.

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 22/01/2023    |  Criação do documento              |    Renan      | Nicolas Souza        |
| `1.1`  | 26/01/2023    |  Inclusão dos requisitos funcionais e estrutura para preenchimento dos elos | Nicolas |
