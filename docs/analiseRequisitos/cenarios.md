## Introdução

Segundo [(Barbosa e Silva, 2011, p.138 e p.139)](referencias/aspEticos01.png), cenário é uma história sobre pessoas realizando uma atividade, de forma textual ou pictórica. Os cenários podem ser utilizados em diversas etapas do processo, com diferentes objetivos. Os cenários podem ser utilizados para descrever situações atuais, futuras ou desejadas, e podem ser utilizados para descrever o contexto de uso, as tarefas, as metas, as necessidades e os problemas dos usuários. No geral, cada cenário representa um ator principal e um objetivo principal.

## Metodologia

Escolhemos a representação de cenários por meio de texto estruturado, utilizando linguagem natural semi-estruturada para melhor entendimento e organização das informações.
A tabela a seguir apresenta a estrutura adotada para a descrição dos cenários:

<center>
Tabela 1: Estrutura de descrição de cenários

| **Elemento** | **Descrição** |
|--------------|---------------|
| Identificador | Código único para identificar o cenário. |
| Contexto |	Descrição de pré-condições, local (físico) e tempo |
| Recursos |	Objetos passivos com os quais os atores interagem |
| Ator |	Pessoa ou estrutura organizacional |
| Episódios |	Ação realizada por um ou vários atores com participação de outros atores utilizando recursos |
| Restrições |	Imposição que restrinja um episódio de um cenário |
| Exceção |	Tratamento para uma situação excepcional ou de erro |

Fonte: Adaptado de [Lucas Gabriel, 2022.]( https://github.com/lucasgabriel-2)	
</center>


## Cenários identificado

Utilizando a estrutura definida no documento, seguem três cenários para as tarefas de Acesso à CNH, Agendamento de serviço e Transferência de veículo:

**Cenário 1: Acesso à CNH Digital**

Tabela 2: Cenário 1: Acesso à CNH Digital

| Elemento      | Descrição                                                                                                                               |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Identificador | CNH-01                                                                                                                                  |
| Contexto      | Usuário em casa, à noite, deseja acessar sua CNH digital pelo celular.                                                                       |
| Recursos      | Smartphone com acesso à internet, aplicativo do DETRAN-DF instalado.                                                                     |
| Ator          | Usuário do portal DETRAN-DF.                                                                                                              |
| Episódios     | 1. Usuário abre o aplicativo do DETRAN-DF.<br>2. Usuário clica em "Entrar".<br>3. Usuário insere CPF e senha.<br>4. Usuário acessa a CNH digital. |
| Restrições    | O usuário precisa ter cadastro no portal do DETRAN-DF e a CNH digital emitida.                                                            |
| Exceção      | Senha incorreta: o sistema exibe mensagem de erro e permite que o usuário tente novamente ou recupere a senha.                            |

<font size="3"><p style="text-align: center">Autor: [Kaio Enzo](https://github.com/kaioenzo).</p></font>

**Cenário 2: Agendamento de Serviço**

Tabela 3: Cenário 2: Agendamento de Serviço

| Elemento      | Descrição                                                                                                                                                           |
|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Identificador | AG-01                                                                                                                                                             |
| Contexto      | Usuário no trabalho, durante o horário de almoço, deseja agendar a renovação da sua CNH.                                                                               |
| Recursos      | Computador com acesso à internet, navegador web.                                                                                                                     |
| Ator          | Usuário do portal DETRAN-DF.                                                                                                                                         |
| Episódios     | 1. Usuário acessa o portal do DETRAN-DF.<br>2. Usuário clica em "Serviços".<br>3. Usuário seleciona "Renovação de CNH".<br>4. Usuário escolhe data e hora disponíveis.<br>5. Usuário confirma o agendamento. |
| Restrições    | O usuário precisa ter cadastro no portal do DETRAN-DF e atender aos pré-requisitos para a renovação da CNH.                                                          |
| Exceção      | Não há horários disponíveis: o sistema exibe mensagem informando a indisponibilidade e sugere outras datas ou unidades de atendimento.                               |

<font size="3"><p style="text-align: center">_Autor: [Luiza Maluf](https://github.com/LuizaMaluf)<a id=anchor_1 href="#REF1"></a></p></font>


**Cenário 3: Transferência de Veículo**

Table 4: Cenário 3: Transferência de Veículo

| Elemento      | Descrição                                                                                                                                                                                              |
|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Identificador | TV-01                                                                                                                                                                                                 |
| Contexto      | Usuário em casa, à noite, deseja iniciar o processo de transferência de seu veículo para um novo proprietário.                                                                                             |
| Recursos      | Computador com acesso à internet, navegador web, documentos do veículo e do novo proprietário.                                                                                                           |
| Ator          | Usuário do portal DETRAN-DF (vendedor do veículo).                                                                                                                                                     |
| Episódios     | 1. Usuário acessa o portal do DETRAN-DF.<br>2. Usuário clica em "Veículos".<br>3. Usuário seleciona "Transferência de Veículo".<br>4. Usuário preenche os dados do veículo e do novo proprietário.<br>5. Usuário inicia a solicitação de transferência. |
| Restrições    | O usuário precisa ter cadastro no portal do DETRAN-DF, possuir os documentos necessários e o veículo deve estar em situação regular.                                                                      |
| Exceção      | Dados inconsistentes: o sistema exibe mensagem de erro indicando os campos com informações incorretas ou incompletas.                                                                                      |

<font size="3"><p style="text-align: center">_Autor: [Márcio Henrique](https://github.com/DeM4rcio)<a id=anchor_1 href="#REF1"></a></p></font>


## __Bibliografia__

> Gabriel, Lucas; Cenários. Repositório do Grupo Linchess da disciplina Interação Humano-Computador da Universidade de Brasília, 2022. _Disponível em: <https://interacao-humano-computador.github.io/2022.2-Lichess/analise_requisitos/cenarios/>. Acesso em: 03/12/2024_

## __Referências Bibliográficas__

> _BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011._


---
## __Histórico de versão__

| Versão |    Data    |      Descrição      |             Autor(es)                        |Revisor(es)|
|--------|------------|---------------------|----------------------------------------------|---------|
| `1.0`  | 03/12/2024 | Criação do document | [Kaio Enzo](https://github.com/kaioenzo)||
