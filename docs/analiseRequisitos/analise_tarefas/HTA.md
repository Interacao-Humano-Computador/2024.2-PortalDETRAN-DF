# __Análise Hierarquica de Tarefas__

## __Introdução__

Uma **análise de tarefas** é utilizada para se ter um entendimento sobre qual é o tra-
balho dos usuários, como eles o realizam e por quê.
Em IHC, a análise de tarefas pode ser utilizada nas três atividades habituais: para
análise da situação atual (apoiada ou não por um sistema computacional), para o
(re)design de um sistema computacional ou para a avaliação do resultado de uma
intervenção que inclua a introdução de um (novo) sistema computacional. [Barbosa e Silva (2011, p.191)](../referencias/analise_tarefas.png)

## __HTA – Hierarchical Task AnalysisHTA__

Portando devido as complexidades de certas tarefas e não repetitivas, é utilizado uma abstração do conceito de análise de tarefas.
Chamado de A Análise Hierárquica de Tarefas (HTA – Hierarchical Task Analysis), Ela ajuda a relacionar o que
as pessoas fazem (ou se recomenda que façam), por que o fazem, e quais as consequências caso não o façam corretamente. Ela pode ser representada por uma tabela, ou por um diagrama, com a notação conforme a figura 1.
<center>

**Figura 1**
![HTA](../referencias/diagrama_tarefas.png)
<font size="3"><p style="text-align: center">_Fonte: BARBOSA e SILVA, 2011._<a id=anchor_1 href="#REF1"></a></p></font>
</center>

## __Análise de tarefas__

Dentro das tarefas com método HTA,  foram escolhidos o acesso ao CNH do usuário, Agendar um serviço e transfência veícular.

### __Acesso ao CNH do usuário__


Nessa tarefa, o usuário possui o objetivo de acessar os dados de sua CNH . A figura 2 apresenta o diagrama HTA relativa a tarefa, já a tabela 1 representa o mesmo HTA em tabela.

<center>


<font size="3"><b>Figura 2</b> - Diagrama HTA de consulta CNH.</font>

![Notação diagrama HTA](../../assets/analise_tarefas/visualizarCNH.png)


<font size="3"><p style="text-align: center">Autor: [Kaio Enzo](https://github.com/kaioenzo).</p></font>



<font size="3"><p style="text-align: center"><b>Tabela 1</b> - HTA de visualização de pedidos.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0.Visualizar CNH   |                                                                                                                                                                                                         |
|      1.Cadastro      | **input**: dados de cadastro.<br>**feedback**: usuário redirecionado para a página de confirmação de email.<br> **plano**: confirmar conta e depois fazer login.                                        |
|     1.1.Confirmar perfil     | **feedback**: após confirmar o email o usuário é liberado para fazer login.                                                                                                                             |
|       1.2.login        | **input**: dados de login.<br>**feedback**: usuário redirecionado para a página dos serviços mais acessados.<br> **plano**: abrir área de CNH. <br>|
| 2.Acesso a CNH | **input**: apertar na opção de consulta CNH.<br>**feedback**: usuário redirecionado para a página listando a pontuação da carteira<br>                                                                                   |

<font size="3">Autor: [Kaio Enzo](https://github.com/kaioenzo).</font>

</center>

### __Agendamento de serviço__


Nessa tarefa, o usuário possui o objetivo de solicitar um agendamento dos serviços prestados pelo Detran . A figura 3 apresenta o diagrama HTA relativa a tarefa, já a tabela 2 representa o mesmo HTA em tabela.

<center>


<font size="3"><b>Figura 3</b> - Diagrama HTA de agendamento de serviço.</font>

![Notação diagrama HTA](hta-luiza2.jpeg)


<font size="3"><p style="text-align: center">Autor: [Luiza Maluf](https://github.com/LuizaMaluf).</p></font>



<font size="3"><p style="text-align: center"><b>Tabela 2</b> - HTA de visualização de pedidos.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------ |
|  0. Realizar o agendamento  |                                                                                                                                                                                                         |
|  1. Acessar o site do Detran  | **input**: Abrir o navegador e digitar a URL do portal<br>**feedback**: Página inicail do DETRAN-DF<br> **plano**: Continuar para a navegação do agendamento. |
|  2. Navegar para área de agendamento | **input**: Identificar o menu ou ícone de "Serviços" e selecionar "Agendamento".<br>**feedback**: Página de agendamento é exibida com opções de serviços.<br>**Plano**: Selecionar o serviço desejado. |
|  3. Escolher o serviço desejado | **input**: Clicar no serviço relevante na lista apresentada.<br>**feedback**: Detalhes do serviço e botão para continuar são exibidos.<br>**Plano**: Avançar para o preenchimento dos dados.|
|  4. Preencher os dados solicitados | **input**: Inserir nome, CPF, e-mail, telefone e outros dados exigidos.<br>**feedback**: Campos preenchidos são validados em tempo real.<br>**Plano**: Concluir o preenchimento e continuar para a escolha da data.|
|  5. Selecionar a data e horário disponíveis | **input**: Escolher uma data no calendário e selecionar o horário disponível.**feedback**: Indicação de horário reservado para o usuário.<br>**Plano**: Prosseguir para a confirmação.|
|  6. Confirmar o agendamento | **input**: Revisar os dados, clicar em "Agendar".<br>**feedback**: Mensagem de sucesso com número de protocolo e instruções adicionais.<br>**Plano**: Finalizar o processo e, se necessário, armazenar o comprovante.|

<font size="3">Autor: [Luiza Maluf](https://github.com/LuizaMaluf).</font>

</center>


### __Transferência de veículo__


Nessa tarefa, o usuário possui o objetivo de transferir veículo  . A figura 5 apresenta o diagrama HTA relativa a tarefa, já a tabela 4 representa o mesmo HTA em tabela.

<center>


<font size="3"><b>Figura 5</b> - Diagrama HTA de tranferencia veicular.</font>

![Notação diagrama HTA](../../assets/analise_tarefas/transferencia_draw.png)


<font size="3"><p style="text-align: center">Autor: [Márcio Henrique](https://github.com/DeM4rcio).</p></font>



<font size="3"><p style="text-align: center"><b>Tabela 3</b> - HTA de visualização de pedidos.</p></font>

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  0.Visualizar CNH   |                                                                                                                                                                                                         |
|      1.Cadastro      | **input**: dados de cadastro.<br>**feedback**: usuário redirecionado para a página de confirmação de email.<br> **plano**: confirmar conta e depois fazer login.                                        |
|     1.1.Confirmar perfil     | **feedback**: após confirmar o email o usuário é liberado para fazer login.                                                                                                                             |
|       1.2.login        | **input**: dados de login.<br>**feedback**: usuário redirecionado para a página dos serviços mais acessados.<br> **plano**: abrir área de veiculos. <br>|
| 2.Veículos | **input**: apertar na opção de veículo débitos ou opção de veículo restrição.<br>**feedback**: usuário redirecionado para a página esclhida<br> **plano** opção única de veículos                                                                         |
| 3.1.Solicitação de tranferência|**input**: dados da placa e RENAVAM no veículo<br> |


<font size="3">Autor: [Márcio Henrique](https://github.com/DeM4rcio).</font>

</center>



## __Bibliografia__

> RIBEIRO, Bruno; GOBBI, Lucas. Aspectos éticos. Repositório do Grupo Branco Central do Brasil da disciplina Interação Humano-Computador da Universidade de Brasília, 2023. _Disponível em: <https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/analise_requisitos/analise_tarefas?id=an%c3%a1lise-hier%c3%a1rquica-de-tarefas>. Acesso em: 28/11/2024_

## __Referências Bibliográficas__

> _BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011._


---
## __Histórico de versão__

| Versão |    Data    |      Descrição      |             Autor(es)                        |Revisor(es)|
|--------|------------|---------------------|----------------------------------------------|---------|
| `1.0`  | 30/11/2024 | Adição de informações da analise de tarefas. | [Márcio Henrique](https://github.com/DeM4rcio)|[Luiza Maluf](https://github.com/LuizaMaluf)| 
| '2.0'  | 20/11/2024 | Correção do HTA do agendamento de serviço | [Luiza Maluf](https://github.com/LuizaMaluf)|[Márcio Henrique](https://github.com/DeM4rcio)|
| ´2.1'  | [Márcio Henrique](https://github.com/DeM4rcio)| [Luiza Maluf](https://github.com/LuizaMaluf)|
