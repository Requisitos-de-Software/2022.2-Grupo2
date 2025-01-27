# Cenários

## Introdução

Cenários são descrições evolutivas de situações em um ambiente composto por um conjunto ordenado de interações entre seus participantes, realizadas por usuários ou sistemas externos [2]. Diante disso, os cenários são utilizados para descrever as situações de uso do sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos [2]. Portanto, é uma estratégia para elicitar a parte comportamental do software[1].

## Modelo de Cenário

Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste documento será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente [2], tal modelo pode ser observado a seguir na Tabela 1.

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Finalidade do cenário                                                                        |
| Contexto   | Descrição de pré-condições, local (físico) e tempo                                           |
| Recursos   | Objetos passivos com os quais os atores interagem                                            |
| Ator       | Pessoa ou estrutura organizacional                                                           |
| Episódios  | Ação realizada por um ou vários atores com participação de outros atores utilizando recursos |
| Restrições | Imposição que restrinja um episódio de um cenário                                            |
| Exceção    | Tratamento para uma situação excepcional ou de erro                                          |

<div style="text-align: center">
<p> Tabela 1: Modelo texto estruturado para descrição de cenários (Fonte: [2], 2022).</p>
</div>

## Cenários identificados

Os cenários identificados foram determinados a partir dos requisitos elicitados pelo método MoSCoW documentado na [Priorização](../elicitacao/priorizacao.md). A seguir, esses podem ser observados nas tabelas abaixo:

### C01: Jogar uma partida de xadrez contra o computador

| Elemento   | Descrição                                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | jogar uma partida de xadrez contra o computador usando o aplicativo Lichess                                                                                      |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter um dispositivo com o aplicativo Lichess instalado                                                |
| Recursos   | - Smartphone <br> - Aplicativo Lichess                                                                                                                           |
| Ator       | Jogador de xadrez                                                                                                                                                |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - O usuário acessa o menu lateral <br> - O usuário seleciona "Computador" <br> - O usuário joga contra o computador |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                   |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado                                                                                                 |

### C02: Jogar uma partida de xadrez contra outro jogador

| Elemento   | Descrição                                                                                                                                                                                                               |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | jogar uma partida de xadrez contra outro jogador usando o aplicativo Lichess                                                                                                                                            |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter acesso a internet, ter um dispositivo com o aplicativo Lichess instalado                                                                                |
| Recursos   | - Internet <br> - Smartphone <br> - Aplicativo Lichess      Lichess                                                                                                                                                     |
| Ator       | Jogadores de xadrez                                                                                                                                                                                                     |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - O usuário acessa o menu lateral <br> - O usuário seleciona "Criar partida" <br> -O usuário seleciona as configurações de jogo <br> - O usuário aguarda por um adversário |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                                                                          |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado <br> - Falta de acesso à internet  <br> - Falta de adversário                                                                                          |

### C03: Aprender xadrez com o aplicativo

| Elemento   | Descrição                                                                                                                                                                            |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Objetivo   | Aprender mais sobre o jogo xadrez                                                                                                                                                    |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter acesso a internet, ter um dispositivo com o aplicativo Lichess instalado                                             |
| Recursos   | - Internet <br> - Smartphone <br> - Aplicativo Lichess                                                                                                                               |
| Ator       | Jogador de xadrez                                                                                                                                                                    |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - O usuário acessa o menu lateral esquerdo <br> - O usuário seleciona "Estudo" <br> -O usuário seleciona um opção de tópico para estudo |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                                       |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado <br> - Falta de acesso à internet                                                                                   |

### C04: Jogar uma partida de xadrez de forma offline

| Elemento   | Descrição                                                                                                                                                      |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Jogar com alguém de forma offline                                                                                                                              |
| Contexto   | - Local: clube de xadrez <br> - Tempo: horário de funcionamento do clube de xadrez <br> - Pré-condições: ter um dispositivo com o aplicativo Lichess instalado |
| Recursos   | - Smartphone <br> - Aplicativo Lichess                                                                                                                         |
| Ator       | Jogadores de xadrez                                                                                                                                            |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - O usuário acessa o menu lateral <br> - O usuário seleciona "Jogar offline contra um amigo"                      |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                 |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado                                                                                               |

### C05: O usuário deve poder recuperar a senha

| Elemento   | Descrição                                                                                                                                                                                                                                                                                                                                           |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Recuperar a senha esquecida                                                                                                                                                                                                                                                                                                                         |
| Contexto   | - Local: em casa <br> - Tempo: durante a noite <br> - Pré-condições: ter um dispositivo com o aplicativo Lichess instalado e acesso à internet                                                                                                                                                                                                      |
| Recursos   | - Internet <br> - Smartphone <br> - Aplicativo Lichess    Lichess                                                                                                                                                                                                                                                                                   |
| Ator       | Usuário do Lichess                                                                                                                                                                                                                                                                                                                                  |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - O usuário acessa o menu lateral <br> - O usuário seleciona a opção "Entrar" <br> - O usuário seleciona a opção "Redefinir a palavra-passe" <br>- O usuário solicita um e-mail de recuperação de senha <br> - O usuário acessa e-mail recebido <br> - O usuário seleciona o link e redefine sua senha |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                                                                                                                                                                                                      |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado  <br> - Falta de acesso a internet                                                                                                                                                                                                                                                 |


### C06: Selecionar a dificuldade da partida ao jogar com o computador

| Elemento   | Descrição                                                                                                                                                                                                                        |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Selecionar a dificuldade da partida contra o computador                                                                                                                                                                          |
| Contexto   | - Local: em casa <br> - Tempo: durante a noite <br> - Pré-condições: ter um dispositivo com o aplicativo Lichess instalado                                                                                                       |
| Recursos   | - Smartphone <br> - Aplicativo Lichess                                                                                                                                                                                           |
| Ator       | Jogador de xadrez                                                                                                                                                                                                                |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - O usuário acessa o menu lateral a opção "Computador" no menu lateral esquerdo <br> - O usuário seleciona o icone mais e assim configura a dificuldade desejada e inicia a partida |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                                                                                   |
| Exceção    | - Falta de energia no dispositivo <br> - Dispositivo danificado                                                                                                                                                                  |

### C07: Reportar um usuário por suspeita de trapaça

| Elemento   | Descrição                                                                                                                                                            |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Denunciar um outro jogador por suspeita de trapaça                                                                                                                   |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter um dispositivo com o aplicativo Lichess instalado e acesso à internet                                |
| Recursos   | - Internet <br> - Smartphone <br> - Aplicativo Lichess                                                                                                               |
| Ator       | Jogadores de xadrez                                                                                                                                                  |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - O usuário joga uma partida e suspeita de trapaça durante o jogo <br> - Ao final do jogo o usuário denúncia o suspeito |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                       |
| Exceção    | - Falta de energia no dispositivo <br> - Dispositivo danificado <br> - Falta de acesso à internet <br> - Falta de adversário                                         |

### C08: Visualizar uma tela de instruções durante o primeiro uso do aplicativo em uma dispositivo

| Elemento   | Descrição                                                                                                                                |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Obter informações sobre o aplicativo ao acessar ele pela primeira vez                                                                    |
| Contexto   | - Local: em casa <br> - Tempo: férias <br>  - Pré-condições: ter um dispositivo com o aplicativo Lichess instalado                       |
| Recursos   | - Smartphone <br> - Aplicativo Lichess                                                                                                   |
| Ator       | Usuário do Lichess                                                                                                                       |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - É exibido ao usuário um tutorial sobre o aplicativo e o usuário vizualiza todas as etapas |
| Restrições | - Fluxo de navegação intuitivo                                                                                                           |
| Exceção    | - Falta de energia no dispositivo <br> - Dispositivo danificado <br>                                                                     |

### C09: Personalizar a partida de acordo com o modo e tempo de jogo desejado

| Elemento   | Descrição                                                                                                                                                                                                                                                                    |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Criar uma partida personalizada                                                                                                                                                                                                                                              |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter um dispositivo com o aplicativo Lichess instalado e acesso à internet                                                                                                                                        |
| Recursos   | - Internet <br> - Smartphone <br> - Aplicativo Lichess                                                                                                                                                                                                                       |
| Ator       | Jogadores de xadrez                                                                                                                                                                                                                                                          |
| Episódios  | - O usuário acessa o aplicativo Lichess <br>  - O usuário acessa o menu lateral esquerdo <br> - O usuário seleciona "Criar uma partida" <br> -O usuário seleciona "Personalizado" e seleciona as  configurações desejadas de jogo <br> - O usuário aguarda por um adversário |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                                                                                                                               |
| Exceção    | - Falta de energia no dispositivo <br> - Dispositivo danificado <br> - Falta de acesso à internet  <br> - Falta de adversário                                                                                                                                                |

### C10: Visualizar o ranqueamento de usuários da plataforma Lichess

| Elemento   | Descrição                                                                                                                                                                     |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Criar uma partida personalizada                                                                                                                                               |
| Contexto   | - Local: em casa <br> - Tempo: férias <br> - Pré-condições: ter um dispositivo com o aplicativo Lichess instalado e acesso à internet                                         |
| Recursos   | - Internet <br> - Smartphone <br> - Aplicativo Lichess                                                                                                                        |
| Ator       | Jogadores de xadrez                                                                                                                                                           |
| Episódios  | - O usuário acessa o aplicativo Lichess <br> - O usuário acessa o menu lateral esquerdo <br> - O usuário seleciona "Jogadores" <br> - O usuário observa a tabela de liderança |
| Restrições | - Fluxo de navegação intuitivo                                                                                                                                                |
| Exceção    | - Falta de energia no dispositivo <br> - Dispositivo danificado <br> - Falta de acesso à internet <br> - Falta de jogadores suficientes para o ranqueamento                   |

## Bibliografia

[1] Slides Requisitos - aula 10. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.

[2] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 11 dez. 2022.

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es)     | Revisor(es)   |
| ------ | ---------- | -------------------- | ------------- | ------------- |
| `1.0`  | 11/12/2022 | Criação do documento | Lucas Gabriel | Nicolas Souza |
| `2.0`  | 01/02/2023 | Adição de Cenários   | Lucas Gabriel | Lucas Macedo  |