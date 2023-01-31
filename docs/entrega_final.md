# Entrega Final

## Introdução

Durante o segundo semestre de 2022, o grupo 2 da disciplina Requisitos de Software, da Universidade de Brasília/FGA, estudou, e documentou, os Requisitos de Software do aplicativo de celular [Lichess](https://lichess.org). O presente artefato tem como principal objetivo sintetizar o processo desenvolvido ao longo do processo, desde as etapas de planejamento aos resultados alcançados.

## Planejamento

Antes do início do projeto, a equipe de trabalho reuniu-se presencialmente, durante a aula de Requisitos de Software, para definir as ferramentas de comunicação e horários das reuniões semanais. Então, durante as primeiras reuniões, foram definidas a [metodologia de trabalho](planejamento/metodologias.md), o [cronograma](planejamento/cronograma.md#cronograma) e as [ferramentas](planejamento/ferramentas.md#ferramentas) utilizadas durante o projeto. Além disso, cada integrante fez o [Rich Picture](planejamento/aplicativo_selecionado.md#aplicativos-analisados), que serviu de base para a definição do [aplicativo escolhido](planejamento/aplicativo_selecionado.md#aplicativo-definido-pela-equipe).

A Tabela 1 sintetiza os artefatos referentes ao planejamento da equipe, que elaborados ao longo do semestre. Na tabela 2 sintetiza as ferramentas utilizadas durante o projeto.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Rich Picture](prerastreabilidade/richpicture.md) | Renan Lacerda | Davi Silva |
[Aplicativo Selecionado](planejamento/aplicativo_selecionado.md) | Lucas Gabriel | Maurício |
[Cronograma](planejamento/cronograma.md) | Mauricio Machado | Nicolas Souza |
[Cronograma Realizado](planejamento/cronograma_realizado.md)| Mauricio Machado | Nicolas Souza |
[Ferramentas](planejamento/ferramentas.md) | Lucas Macedo | Nicolas e Lucas Gabriel |
[Metodologias](planejamento/metodologias.md) | Davi Silva e Nicolas Souza  | Mauricio Machado |
[Ata da Reunião (01/11/2022)](atas/ata_01_11.md)  | Davi Silva    | Renan Rodrigues Lacerda |
[Ata da Reunião (10/11/2022)](atas/ata_10_11.md)| Lucas Macedo  | Nicolas Souza |
[Ata da Reunião (15/11/2022)](atas/ata_15_11.md)| Lucas Gabriel  | Maurício Machado |
[Ata da Reunião (22/11/2022)](atas/ata_22_11.md)| Davi Silva  | Lucas Gabriel |
[Ata da Reunião (29/11/2022)](atas/ata_29_11.md) | Lucas Gabriel |    Davi Silva|
[Ata da Reunião (06/12/2022)](atas/ata_06_12.md) | Mauricio Machado |   Nicolas Souza  |
[Ata da Reunião (13/12/2022)](atas/ata_13_12.md) | Nicolas Souza | Davi Silva  |
[Ata da Reunião (20/12/2022)](atas/ata_20_12.md) | Lucas Gabriel |    Davi Silva|
[Ata da Reunião (03/01/2023)](atas/ata_03_01_2023.md) | Lucas Macedo  | Lucas Gabriel |
[Ata da Reunião (18/01/2023)](atas/ata_18_01.md) | Nicolas Souza | Lucas Macedo   |
[Ata da Reunião (25/01/2023)](atas/ata_25_01.md) | Davi Silva | Lucas Gabriel |

<div style="text-align: center">
<p> Tabela 1: Síntese dos artefatos de Planejamento (Fonte: autor, 2023).</p>
</div>

</center>

<!-- @TODO: cronograma planejado e executado, em uma mesma tabela -->

## Ferramentas

<center>
  
|        Ferramentas        |    Em qual etapa foi utilizado    |                                        Motivo pelo qual foi utilizado                                         |
| :-----------------------: | :-------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
|          GitHub           |      Durante todo o projeto       |                   Repositório utilizado, versionamento do projeto, criação da documentação.                   |
|         Telegram          |      Durante todo o projeto       |                                     Principal meio de comunicação do time                                     |
|     Google planilhas      | Ficou em desuso depois da etapa 3 |                  Onde foi desenvolvido a primeira versão do cronograma planejado e realizado                  |
|      Microsoft Teams      |      Durante todo o projeto       | Local onde foram salvados os vídeos de reunião, apresentações de ponto de controle e entrevistas com usuários |
|          Youtube          |      Durante todo o projeto       |                 Local armazenado os vídeos gravados das reuniões, apresentações e entrevistas                 |
|    Visual Studio Code     |      Durante todo o projeto       |                        Editor de texto gratuito usado para a construção dos artefatos                         |
|           Miro            |         Usado na etapa 1          |                                 Criação das imagens do artefato rich picture                                  |
|        Lucid Chart        |         Usado na etapa 3          |                                      Criação da artefato de Casos de Uso                                      |
| This Person Doesn't Exist |         Usado na etapa 2          |                                    Coletado as fotos das personas criadas                                     |
| Google forms | Usado na etapa 2 | Usado para criar o formulário responsável para  caracterizar o perfil de usuário  |

<div style="text-align: center">
<p> Tabela 2: Síntese do artefato de Ferramentas (Fonte: autor, 2023).</p>
</div>
</center>

## Execução do Projeto

De acordo com o SWEBOK [3], a área de conhecimento de Requisitos de Software é responsável pela gerência dos requisitos, por meio das atividades de **elicitação, análise, especificação** e **validação** destes. Requisitos de Software expressam necessidades e restrições presentes em um produto de software, por meio de combinações complexas de dados proveniente de diversas fontes, dentre elas recursos humanos e o contexto do sistema. Requisitos também possuem atributos, como a [prioridade](elicitacao/priorizacao.md) e identificação única, representada no projeto pelos IDs dos requisitos.

### Elicitação e Priorização

A elicitação de requisitos diz respeito à da etapa de concepção dos requisitos de um software e à forma como o engenheiro de software pode coletá-los. Essa atividade envolve a identificação dos _stakeholders_ e a criação de relacionamentos entre a equipe de desenvolvimento e o cliente, atividade que foi feita por meio de uma [entrevista](elicitacao/entrevista.md) e um [questionário](elicitacao/questionario.md), elementos essenciais para a elaboração do [perfil do usuário](elicitacao/personas.md#perfil-do-usuario) e, em seguida, a elaboração das [personas](elicitacao/personas.md) do projeto. Os requisitos podem vir de diversas fontes, como por exemplo os objetivos do software, domínio de conhecimento, stakeholders, regras de negócio e o ambiente em que o sistema está inserido. A etapa de [elicitação](elicitacao/tecnicas_planejadas.md) utilizou diferentes [técnicas de elicitação](elicitacao/tecnicas_planejadas.md#tecnicas-de-elicitacao) para explorar as fontes citadas anteriormente. Após a elicitação, os requisitos foram [priorizados](elicitacao/priorizacao.md) por meio de três [técnicas](elicitacao/priorizacao.md#tecnicas-utilizadas) diferentes. A Tabela 2 sintetiza os artefatos elaborados durante a etapa de elicitação e priorização.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Planejamento - Elicitação](elicitacao/tecnicas_planejadas.md) | Nicolas Souza  | Maurício Machado |
[Brainstorming](elicitacao/brainstorming.md) | Davi Silva | Lucas Macedo, Maurício e Nicolas |
[Entrevista](elicitacao/entrevista.md) | Lucas Gabriel | Mauricio Machado |
[Glossário](elicitacao/glossario.md)           | Nicolas Souza |       Mauricio Machado        |
[Introspecção](elicitacao/introspeccao.md)              | Nicolas Souza |  Lucas Macedo |
[Questionário](elicitacao/questionario.md) | Mauricio |   Lucas Macedo    |
[Priorização](elicitacao/priorizacao.md) | Renan | Lucas Macedo |
<div style="text-align: center">
<p>
Tabela 2: Síntese dos artefatos produzidos durante a etapa de elicitação (Fonte: autor, 2023).
</p>
</div>
</center>

### Modelagem

A etapa de modelagem do projeto englobou as atividades de **análise** e **especificação** dos requisitos. A análise de requisitos foi essencial para resolver os conflitos entre requisitos, haja vista que foram utilizadas várias fontes e técnicas durante a elicitação. Além disso, durante a análise, os requisitos de sistema foram transformados em requisitos de software [funcionais](modelagem/agil/backlog.md#requisitos-elicitados) e [não funcionais](modelagem/nfr_framework.md#requisitos-elicitados-atraves-do-nfr) verificáveis.

A especificação dos requisitos contou com a produção de documentos revisáveis, avaliáveis e aprováveis, que posteriormente foram [validados](./#validacao) com a equipe de desenvolvimento do [Lichess](https://lichess.org). A Tabela 3 sintetiza os artefatos produzidos durante a etapa de modelagem.

<center>

| Artefato | Autor(es) | Revisor(es) |
| :-: | :-: | :-: |
[Casos de uso](modelagem/casos_de_uso.md)   | Lucas Macedo  |  Nicolas Souza   |
[Cenários](modelagem/cenarios.md)| Lucas Gabriel | Nicolas Souza |
[Especificação Suplementar](modelagem/especificacao_suplementar.md)| Davi Silva| Nicolas Souza |
[Léxico](modelagem/lexico.md)  | Maurício Machado| Nicolas Souza  |
[NFR Framework](modelagem/nfr_framework.md)| Maurício Machado | Nicolas Souza |
[Backlog](modelagem/agil/backlog.md)  | Nicolas Souza |  Lucas Macedo |
[Histórias de Usuário](modelagem/agil/us.md)  | Nicolas Souza | Lucas Macedo |

<div style="text-align: center">
<p>
Tabela 3: Síntese dos artefatos produzidos durante a etapa de modelagem. (Fonte: autor, 2023).
</p>
</div>
</center>

### Pós-Rastreabilidade

## Técnicas Utilizadas

### Tabela dos Artefatos com seus respectivos autores, revisores e técnicas utilizadas

<center>

|          Etapa           |                                       Artefato                                        |        Técnica         |                          Autor(es)                          |                     Revisor(es)                      |
| :----------------------: | :-----------------------------------------------------------------------------------: | :--------------------: | :---------------------------------------------------------: | :--------------------------------------------------: |
|       Planejamento       |                       [Cronograma](planejamento/cronograma.md)                        |         SCRUM          |                      Mauricio Machado                       |                    Nicolas Souza                     |
|       Planejamento       |                      [Ferramentas](planejamento/ferramentas.md)                       |      Não Listada       |                 Lucas Macedo, Nicolas Souza                 |                    Lucas Gabriel                     |
|       Planejamento       |                     [Metodologias](planejamento/metodologias.md)                      |         SCRUM          |                 Davi Silva e Nicolas Souza                  |                   Maurício Machado                   |
|   Pré-Rastreabilidade    |                    [Rich Pictures](analise-grupo2/richpicture.md)                     |      Rich Picture      |                        Renan Lacerda                        |                      Davi Silva                      |
| Elicitação e Priorização |               [Técnicas Planejadas](elicitacao/tecnicas_planejadas.md)                |         SCRUM          |                        Nicolas Souza                        |                   Maurício Machado                   |
| Elicitação e Priorização |                      [StoryTelling](elicitacao/storytelling.md)                       |      Role-Playing      |                        Lucas Macedo                         |                       Nicolas                        |
| Elicitação e Priorização |                          [Personas](elicitacao/personas.md)                           |      Questionário      |                          Mauricio                           |                     Lucas Macedo                     |
| Elicitação e Priorização |                      [Questionário](elicitacao/questionario.md)                       |      Questionário      |                          Mauricio                           |                     Lucas Macedo                     |
| Elicitação e Priorização |                      [Introspecção](elicitacao/introspeccao.md)                       |      Introspecção      |                           Nicolas                           |                         Davi                         |
| Elicitação e Priorização |                         [Glossário](elicitacao/glossario.md)                          |      Introspecção      |                           Nicolas                           |                    Lucas Gabriel                     |
| Elicitação e Priorização |                        [Entrevista](elicitacao/entrevista.md)                         |       Entrevista       |                        Lucas Gabriel                        |                       Mauricio                       |
| Elicitação e Priorização |                     [Brainstorming](elicitacao/brainstorming.md)                      |       Brainstorm       |                         Davi Silva                          |                    Lucas Gabriel                     |
| Elicitação e Priorização |                          [Moscow](elicitacao/priorizacao.md)                          |         MoSCoW         |                       Renan, Maurício                       |                     Lucas Macedo                     |
| Elicitação e Priorização |                    [First Things First](elicitacao/priorizacao.md)                    |          FtF           |                       Renan, Maurício                       |                     Lucas Macedo                     |
| Elicitação e Priorização |                  [Escala de Três Níveis](elicitacao/priorizacao.md)                   | Escala de Três Níveis  |                       Renan, Maurício                       |                     Lucas Macedo                     |
|        Modelagem         |                             [Léxico](modelagem/lexico.md)                             |         Léxico         |                          Maurício                           |                       Nicolas                        |
|        Modelagem         |                           [NFR](modelagem/nfr_framework.md)                           |     NFR Framework      |                          Mauricio                           |                       Nicolas                        |
|        Modelagem         |                       [Casos de Uso](modelagem/casos_de_uso.md)                       |      Diagrama UML      |                    Nicolas, Lucas Macedo                    |                Lucas Macedo, Nicolas                 |
|        Modelagem         |          [Especificação Suplementar](modelagem/especificacao_suplementar.md)          |         FURPS+         |                         Davi Silva                          |                       Nicolas                        |
|      Modelagem Ágil      |                     [Histórias de Usuário](modelagem/agil/us.md)                      |  Histórias de Usuário  |                           Nicolas                           |                     Lucas Macedo                     |
|      Modelagem Ágil      |                         [Backlog](modelagem/agil/backlog.md)                          |    Product Backlog     |                           Nicolas                           |                     Lucas Macedo                     |
|         Análise          |             [Verificação: BackLog](analise-grupo3/verificacao/backlog.md)             |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |          [Verificação: Brainstorm](analise-grupo3/verificacao/brainstorm.md)          |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |       [Verificação: Rich Picture](verificacao/../analise-grupo2/richpicture.md)       |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |                   [Verificação: Léxicos](analise-grupo2/lexicos.md)                   |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |                 [Verificação: Glossário](analise-grupo2/glossario.md)                 |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |              [Verificação: Introspecção](analise-grupo2/introspeccao.md)              |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |              [Verificação: Questionário](analise-grupo2/questionario.md)              |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |                  [Verificação: Personas](analise-grupo2/personas.md)                  |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |              [Verificação: StoryTelling](analise-grupo2/storytelling.md)              |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |                [Verificação: Entrevista](analise-grupo2/entrevista.md)                |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |               [Verificação: Priorização](analise-grupo2/priorizacao.md)               |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |                  [Verificação: NFR Framework](analise-grupo2/nfr.md)                  |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |              [Verificação: Casos de Uso](analise-grupo2/casos-de-uso.md)              |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |                [Verificação: NFR Cenário](analise-grupo2/cenarios.md)                 |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          | [Verificação: Especificação Suplementar](analise-grupo2/especificacao-suplementar.md) |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |      [Verificação: Histórias de Usuário](analise-grupo2/historias-de-usuario.md)      |        Inspeção        |                           Nicolas                           |                       Mauricio                       |
|         Análise          |  [Validação: Comprovação Informal](analise-grupo2/validacao/comprovacao_informal.md)  |     Envio de Email     |                        Lucas Gabriel                        |                     Lucas Macedo                     |
|   Pós-rastreabilidade    |                    [Backward From](posrastreabilidade/backward.md)                    | Meta-modelo de Toranzo |                       Renan, Nicolas                        |                      Davi Silva                      |
|   Pós-rastreabilidade    |                  [Forward From](posrastreabilidade/forward_from.md)                   |      Forward From      |         Lucas Macedo, Davi, Mauricio, Lucas Gabriel         |                       Nicolas                        |
|          Todas           |                           [Apresentações](apresentacoes.md)                           |        Gravação        | Nicolas, Davi, Mauricio, Lucas Gabriel, Lucas Macedo, Renan | Nicolas, Davi, Mauricio, Lucas Gabriel, Lucas Macedo |

<div style="text-align: center">
<p>
Tabela 5: Síntese das técnicas utilizadas (Fonte: autor, 2023).
</p>
</div>

</center>

## Verificação e Validação dos Artefatos

A etapa de validação de requisitos contempla o processo de análise do documento de requisitos para garantir que ele defina o software esperado pelos usuários. Os documentos elaborados na etapa de especificação passam por uma etapa de verificação e validação, para garantir que o engenheiro de software tenha entendido os requisitos. Além disso, é importante verificar se o documento elaborado está de acordo com os padrões exigidos pelos _stakeholders_, como por exemplo uma padronização de documentos em uma empresa, é consistente, completo e de fácil entendimento. [3]

A verificação foi feita por meio da inspeção, com base na proposta de Fagan [2], utilizando um checklist de erros mais comuns que podem ser identificados em projetos, tomando como base os projetos anteriores da disciplina de [Requisitos de Software](https://github.com/Requisitos-de-Software), os critérios do Plano de Ensino [1], a bibliografia da disciplina e os feedbacks dos monitores. A Tabela 7 sintetiza os responsáveis pela elaboração dos checklists para cada artefato, nos artefatos de planejamento, e execução das verificações, nos artefatos de resultados. A validação foi feita por meio da comunicação informal, via email, com as equipes de desenvolvimento dos aplicativos a serem validados.

<center>

|                                                Artefato                                                |      Autor(es)      |  Revisor(es)  |
| :----------------------------------------------------------------------------------------------------: | :-----------------: | :-----------: |
|         [Verificação (Grupo 2) - Planejamento da verificação](analise-grupo2/planejamento.md)          |    Nicolas Souza    |   Maurício    |
|                      [Verificação (Grupo 2) - Backlog](analise-grupo2/backlog.md)                      |    Nicolas Souza    |   Maurício    |
|                [Verificação (Grupo 2) - Brainstorming](analise-grupo2/brainstorming.md)                |    Nicolas Souza    |   Maurício    |
|                 [Verificação (Grupo 2) - Casos de uso](analise-grupo2/casos-de-uso.md)                 |    Nicolas Souza    |   Maurício    |
|                     [Verificação (Grupo 2) - Cenários](analise-grupo2/cenarios.md)                     |    Nicolas Souza    |   Maurício    |
|                   [Verificação (Grupo 2) - Entrevista](analise-grupo2/entrevista.md)                   |    Nicolas Souza    |   Maurício    |
|    [Verificação (Grupo 2) - Especificação Suplementar](analise-grupo2/especificacao-suplementar.md)    |    Nicolas Souza    |   Maurício    |
|                    [Verificação (Grupo 2) - Glossário](analise-grupo2/glossario.md)                    |    Nicolas Souza    |   Maurício    |
|         [Verificação (Grupo 2) - Histórias de usuário](analise-grupo2/historias-de-usuario.md)         |    Nicolas Souza    |   Maurício    |
|                 [Verificação (Grupo 2) - Introspecção](analise-grupo2/introspeccao.md)                 |    Nicolas Souza    |   Maurício    |
|                      [Verificação (Grupo 2) - Léxicos](analise-grupo2/lexicos.md)                      |    Nicolas Souza    |   Maurício    |
|                     [Verificação (Grupo 2) - NFR Framework](analise-grupo2/nfr.md)                     |    Nicolas Souza    |   Maurício    |
|                     [Verificação (Grupo 2) - Personas](analise-grupo2/personas.md)                     |    Nicolas Souza    |   Maurício    |
|                  [Verificação (Grupo 2) - Priorizacao](analise-grupo2/priorizacao.md)                  |    Nicolas Souza    |   Maurício    |
|                 [Verificação (Grupo 2) - Questionário](analise-grupo2/questionario.md)                 |    Nicolas Souza    |   Maurício    |
|                  [Verificação (Grupo 2) - Richpicture](analise-grupo2/richpicture.md)                  |    Nicolas Souza    |   Maurício    |
|                 [Verificação (Grupo 2) - Storytelling](analise-grupo2/storytelling.md)                 |    Nicolas Souza    |   Maurício    |
|                [Validacao (Grupo 2)](analise-grupo2/validacao/comprovacao_informal.md)                 |    Lucas Gabriel    | Lucas Macedo  |
|                [Verificação (Grupo 3) - backlog](analise-grupo3/verificacao/backlog.md)                |     Davi Silva      | Lucas Macedo  |
|             [Verificação (Grupo 3) - brainstorm](analise-grupo3/verificacao/brainstorm.md)             |     Davi Silva      | Lucas Macedo  |
|           [Verificação (Grupo 3) - casos-de-uso](analise-grupo3/verificacao/casos-de-uso.md)           |     Davi Silva      | Lucas Macedo  |
|               [Verificação (Grupo 3) - cenarios](analise-grupo3/verificacao/cenarios.md)               |    Lucas Gabriel    |     Davi      |
|             [Verificação (Grupo 3) - entrevista](analise-grupo3/verificacao/entrevista.md)             |    Lucas Gabriel    |     Davi      |
|      [Verificação (Grupo 3) - especificacao_sup](analise-grupo3/verificacao/especificacao_sup.md)      |    Lucas Macedo     |     Davi      |
|   [Verificação (Grupo 3) - historias-de-usuario](analise-grupo3/verificacao/historias-de-usuario.md)   |    Lucas Macedo     |     Davi      |
|           [Verificação (Grupo 3) - introspeccao](analise-grupo3/verificacao/introspeccao.md)           |    Lucas Gabriel    | Nicolas Souza |
|                 [Verificação (Grupo 3) - lexico](analise-grupo3/verificacao/lexico.md)                 |     Davi Silva      | Lucas Macedo  |
|          [Verificação (Grupo 3) - nfr-framework](analise-grupo3/verificacao/nfr-framework.md)          |     Davi Silva      | Lucas Macedo  |
|         [Verificação (Grupo 3) - perfil-usuario](analise-grupo3/verificacao/perfil-usuario.md)         |    Lucas Gabriel    |     Davi      |
|                [Verificação (Grupo 3) - persona](analise-grupo3/verificacao/persona.md)                |    Lucas Gabriel    |     Davi      |
|            [Verificação (Grupo 3) - priorizacao](analise-grupo3/verificacao/priorizacao.md)            |    Lucas Macedo     |     Davi      |
| [Verificação (Grupo 3) - tecnicas-de-elicitacao](analise-grupo3/verificacao/tecnicas-de-elicitacao.md) |    Lucas Macedo     |     Davi      |
|                     [Validação (Grupo 3)](analise-grupo3/validacao/comunicacao.md)                     | Davi e Lucas Macedo | Lucas Gabriel |

<div style="text-align: center">
<p>
Tabela 6: Síntese dos artefatos de Verificação (Fonte: autor, 2023).
</p>
</div>

</center>

## Apresentações

Durante a execução do projeto o grupo fez seis entregas parciais, cujas informações estão sintetizadas na Tabela 8.
<center>

|                              Apresentação                              | Participantes                                                      |
| :--------------------------------------------------------------------: | :----------------------------------------------------------------- |
| [Apresentação <br/> Ponto de Controle 1](https://youtu.be/kKjhGvfKOa8) | Davi, Lucas Gabriel, Lucas Macedo, <br/> Maurício, Nicolas e Renan |
| [Apresentação <br/> Ponto de Controle 2](https://youtu.be/EC1_G0WkAuQ) | Davi, Lucas Gabriel, Lucas Macedo, <br/>Nicolas e Renan            |
| [Apresentação <br/> Ponto de Controle 3](https://youtu.be/QE5hB1XCDKk) | Davi, Lucas Gabriel, Lucas Macedo, <br/>Maurício e Nicolas         |
| [Apresentação <br/> Ponto de Controle 4](https://youtu.be/sQir_kGXXD0) | Davi, Lucas Gabriel, Lucas Macedo, <br/>Maurício e Nicolas         |
| [Apresentação <br/> Ponto de Controle 5](https://youtu.be/jOMvNtkMdbk) | Davi, Lucas Macedo e Lucas Gabriel                                 |
| [Apresentação <br/> Ponto de Controle 6](https://youtu.be/FUAAh6tfyfA) | Nicolas                                                            |

<div style="text-align: center">
<p>
Tabela 7: Síntese das apresentações (Fonte: autor, 2023)
</p>
</div>
</center>

## Resultados Alcançados

<!-- @TODO: incluir os resultados alcançados com a execução do projeto, as facilidades e dificuldades  -->

## Bibliografia

[1] Plano de Ensino da disciplina Requisitos de Software.<br/>
[2] Gerência e Qualidade de Software - Aula 06 - Técnica de revisão – UNIVESP<br/>
[3] Bourque and R.E. Fairley, eds., Guide to the Software Engineering Body of Knowledge, Version 3.0, IEEE Computer Society, 2014; www.swebok.org.

<!-- @TODO: antes da versão final, numerar as tabelas corretamente -->
## Histórico de Versão

| Versão | Data       | Descrição                                                                | Autor(es)     | Revisor(es)   |
| ------ | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------- |
| `1.0`  | 30/01/2023 | Criação da versão inicial do documento contendo introdução, execução do projeto, sínteses do planejamento, da verificação e validação e das gravações, e estrutura para inserção das demais seções. | Nicolas Souza | Lucas Macedo  |
| `1.1`  | 30/01/2023 | Adição da síntese de ferramentas                                         | Lucas Macedo  | Nicolas Souza |
| `1.2`  | 31/01/2023 | Adição da síntese das técnicas utilizadas                                | Davi Silva    | Nicolas Souza              |
