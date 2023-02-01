# Backward From

## Introdução

A rastreabilidade de requisitos é a técnica utilizada para prover relacionamentos entre requisitos, arquitetura e implementação final do sistema. Essa atividade visa acompanhar e descrever todo o ciclo de vida de um requisito, e, mais especificamente, a pré-rastreabilidade documenta o contexto a partir do qual emergem os requisitos e a pós-rastreabilidade vincula os requisitos ao desenho do sistema e sua implementação[2].

O presente artefato documenta, utilizando a técnica Backward From, os rastros entre os requisitos e seus desenhos e implementação. Optou-se pela utilização do Meta-modelo de Toranzo, aplicado à rastreabilidade de requisitos, que perpassa pelas seguintes atividades:

- Classificação dos requisitos entre quatro níveis: **ambiental, organizacional, gerencial** e **desenvolvimento**.
- Aplicação do meta-modelo, identificando os tipos de elos entre os requisitos, entre: **satisfação, recurso, responsabilidade, representação, alocado** e **agregação**

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
<div style="text-align: center">
<p>
Tabela 1: Requisitos Funcionais (Fonte: autor, 2023).
</p>
</div>

## Requisitos Não Funcionais

| Identificador | Requisito | Origem | Elos
| :-: | :-: | :-: | :-: |
| RNF01 | Sistema deve ter barra de navegação que siga padrões de UI/UX bem estabelecidos no mercado | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF01](#enf01)
| RNF02 | Usuário deve conseguir padronizar sua interface de maneira única | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF02](#enf02)
| RNF03 | Sistema deve ter no máximo 5 interações por funcionalidade | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF03](#enf03)
| RNF04 | Sistema deve ter animações simples de no máximo 300 milésimos | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF04](#enf04)
| RNF05 | Sistema deve apresentar acesso a todas as funcionalidades logo no início do app | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF05](#enf05)
| RNF07 | Sistema deve permitir customização de tema (claro e escuro) | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF07](#enf07)
| RNF08 | Sistema deve permitir customização de linguagem (português, inglês e espanhol) | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF08](#enf08)
| RNF09 | Sistema deve permitir customização de som (habilitar e desabilitar efeitos sonoros) | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF09](#enf09)
| RNF10 | Sistema deve estar online todos os dias da semana, durante todo o dia | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF10](#enf10)
| RNF11 | Sistema deve informar sobre manutenções e possíveis tempos em que o servidor estará offline via notificação |[NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF11](#enf11)
| RNF12 | Sistema deve realizar backup automático dos dados do usuário todo dia em horário com menor  acesso (a ser determinado pelo sistema) | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF12](#enf12)
| RNF13 | Sistema deve ser compatível com Android (de versão 9.0 até atual) | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF13](#enf13)
| RNF14 | Sistema deve ser compatível com iOS (de versão 12 até atual) | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF14](#enf14)
| RNF17 | Sistema deve ser disponível na Web | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF17](#enf17)
| RNF18 | Sistema deve ser responsivo | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF18](#enf18)
| RNF19 | Sistema deve escurecer a tela em caso de inatividade maior de X minutos definido pelo usuário | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF19](#enf19)
| RNF2O | Dispositivo deve bloquear tela em caso de inatividade prolongada | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF2O](#enf20)
| RNF21 | Sistema deve guardar a última tela em que o usuário está | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF21](#enf21)
| RNF22 | Sistema deve permitir jogar partidas mesmo sem conexão de internet | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF22](#enf22)
| RNF23 | Sistema deve permitir acessar o aplicativo mesmo sem conexão de internet | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF23](#enf23)
| RNF24 | Sistema deve ter uma taxa de atraso abaixa de 100 milissegundos | [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr) | [ENF24](#enf24)
<div style="text-align: center">
<p>
Tabela 2: Requisitos Não Funcionais (Fonte: autor, 2023).
</p>
</div>

## Elos Funcionais

### EF01

**Categoria:** Desenvolvimento

**Elos**: Agrega [Q04](../elicitacao/questionario.md#requisitos-elicitados)

### EF02

**Categoria:** Desenvolvimento

**Elos**: Agrega [Q10](../elicitacao/questionario.md#requisitos-elicitados)

### EF03

**Categoria:** Desenvolvimento

**Elos**: Agrega [Q04](../elicitacao/questionario.md#requisitos-elicitados) e [Q08](../elicitacao/questionario.md#requisitos-elicitados)

### EF04

**Categoria:** Desenvolvimento

**Elos**: Agrega [ST07](../elicitacao/storytelling.md#requisitos-elicitados)

### EF05

**Categoria:** Desenvolvimento

**Elos**: Agrega [INT07](../elicitacao/introspeccao.md#elicitação-de-requisitos), [Q13](../elicitacao/questionario.md#requisitos-elicitados) e [ST11](../elicitacao/storytelling.md#requisitos-elicitados)

### EF06

**Categoria:** Desenvolvimento

**Elos**: Agrega [ST06](../elicitacao/storytelling.md#requisitos-elicitados)

### EF07

**Categoria:** Desenvolvimento

**Elos**: Agrega [INT04](../elicitacao/introspeccao.md#elicitação-de-requisitos)

### EF08

**Categoria:** Desenvolvimento

**Elos**: Agrega  [GLO01](../elicitacao/glossario.md#requisitos-elicitados), [INT03](../elicitacao/introspeccao.md#elicitação-de-requisitos) e [ST04](../elicitacao/storytelling.md#requisitos-elicitados)

### EF09

**Categoria:** Desenvolvimento

**Elos**: Agrega [ENT01](../elicitacao/entrevista.md#resultados), [GLO02](../elicitacao/glossario.md#requisitos-elicitados) e [ST04](../elicitacao/storytelling.md#requisitos-elicitados)

### EF10

**Categoria:** Desenvolvimento

**Elos**: Agrega [ENT02](../elicitacao/entrevista.md#resultados) e [ST04](../elicitacao/storytelling.md#requisitos-elicitados)

### EF11

**Categoria:** Desenvolvimento

**Elos**: Agrega [ST09](../elicitacao/storytelling.md#requisitos-elicitados) e  [Q02](../elicitacao/questionario.md#requisitos-elicitados)

### EF12

**Categoria:** Desenvolvimento

**Elos**: Agrega  [GLO03](../elicitacao/glossario.md#requisitos-elicitados)

### EF13

**Categoria:** Desenvolvimento

**Elos**: Agrega  [INT08](../elicitacao/introspeccao.md#elicitação-de-requisitos)

### EF14

**Categoria:** Desenvolvimento

**Elos**: Agrega [ST13](../elicitacao/storytelling.md#requisitos-elicitados)

### EF15

**Categoria:** Desenvolvimento

**Elos**: Agrega [Q08](../elicitacao/questionario.md#requisitos-elicitados) e  [Q04](../elicitacao/questionario.md#requisitos-elicitados)

### EF16

**Categoria:** Desenvolvimento

**Elos**: Agrega [ST03](../elicitacao/storytelling.md#requisitos-elicitados)

### EF17

**Categoria:** Desenvolvimento

**Elos**: Agrega [Q09](../elicitacao/questionario.md#requisitos-elicitados)

### EF18

**Categoria:** Desenvolvimento

**Elos**: Agrega  [INT01](../elicitacao/introspeccao.md#elicitação-de-requisitos)

### EF19

**Categoria:** Desenvolvimento

**Elos**: Agrega  [INT02](../elicitacao/introspeccao.md#elicitação-de-requisitos), [ST02](../elicitacao/storytelling.md#requisitos-elicitados) e [ST05](../elicitacao/storytelling.md#requisitos-elicitados)

### EF20

**Categoria:** Desenvolvimento

**Elos**: Agrega [INT05](../elicitacao/introspeccao.md#elicitação-de-requisitos)

### EF21

**Categoria:** Desenvolvimento

**Elos**: Agrega [Q03](../elicitacao/questionario.md#requisitos-elicitados)

### EF22

**Categoria:** Desenvolvimento

**Elos**: Agrega [GLO04](../elicitacao/glossario.md#requisitos-elicitados), [INT12](../elicitacao/introspeccao.md#elicitação-de-requisitos) e [ST12](../elicitacao/storytelling.md#requisitos-elicitados)

### EF23

**Categoria:** Desenvolvimento

**Elos**: Agrega [ST13](../elicitacao/storytelling.md#requisitos-elicitados)

### EF24

**Categoria:** Desenvolvimento

**Elos**: Agrega [ST08](../elicitacao/storytelling.md#requisitos-elicitados)

### EF25

**Categoria:** Desenvolvimento

**Elos**: Agrega [Q02](../elicitacao/questionario.md#requisitos-elicitados)

### EF26

**Categoria:** Desenvolvimento

**Elos**: Agrega [Q06](../elicitacao/questionario.md#requisitos-elicitados) e [ST10](../elicitacao/storytelling.md#requisitos-elicitados)

### EF27

**Categoria:** Desenvolvimento

**Elos**: Agrega  [INT06](../elicitacao/introspeccao.md#elicitação-de-requisitos)

### EF28

**Categoria:** Desenvolvimento

**Elos**: Agrega  [GLO04](../elicitacao/glossario.md##requisitos-elicitados) e [INT15](../elicitacao/introspeccao.md#elicitação-de-requisitos)

## Elos Não Funcionais

ambiental, organizacional, gerencial e desenvolvimento.

### ENF01

**Categoria:** Organizacional

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF02

**Categoria:** Gerencial

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF03

**Categoria:** Organizacional

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF04

**Categoria:** Ambiental

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF05

**Categoria:** Gerencial

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF07

**Categoria:** Ambiental

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF08

**Categoria:** Ambiental

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF09

**Categoria:** Ambiental

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF10

**Categoria:** Gerencial

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF11

**Categoria:** Organizacional

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF12

**Categoria:** Gerencial

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF13

**Categoria:** Ambiental

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF14

**Categoria:** Ambiental

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF17

**Categoria:** Ambiental

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF18

**Categoria:** Ambiental

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF19

**Categoria:** Organizacional

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF20

**Categoria:** Gerencial

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF21

**Categoria:** Organizacional

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF22

**Categoria:** Organizacional

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF23

**Categoria:** Organizacional

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

### ENF24

**Categoria:** Organizacional

**Elos**: Agrega  [NFR](../modelagem/nfr_framework.md#requisitos-elicitados-através-do-nfr)

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 44 slides. color. Disponível no [link](https://aprender3.unb.br/pluginfile.php/1668237/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 22 jan. 2023.

[2] SAYÃO Miriam, LEITE Julio. Rastreabilidade de Requisitos. 2005, PUC-RJ.

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 22/01/2023    | Criação da introdução             |    Renan      | Nicolas Souza        |
| `1.1`  | 26/01/2023    | Inclusão dos requisitos e estrutura para preenchimento dos elos | Nicolas Souza | Lucas Macedo |
| `1.2`  | 28/01/2023    | Documentação dos elos entre os requisitos funcionais. | Nicolas Souza | Lucas Macedo |
| `1.3`  | 30/01/2023    | Documentação dos elos entre os requisitos não funcionais. | Lucas Macedo | Nicolas Souza |
