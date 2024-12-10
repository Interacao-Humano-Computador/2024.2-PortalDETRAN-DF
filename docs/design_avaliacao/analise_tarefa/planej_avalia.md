# Planejamento da Avaliação da Análise de Tarefas

## Introdução

A fim de garantir que o sistema Detran Digital atenda às necessidades dos usuários, realizaremos uma avaliação contínua e evolutiva acerca do processo de desenvolvimento. Iniciaremos pela análise de tarefas, conduziremos entrevistas com usuários reais para validar as informações coletadas e identificar oportunidades de melhoria. Essa abordagem iterativa nos permitirá construir um sistema mais robusto e intuitivo (dentro do contexto da disciplina).

## Metodologia

Para realizar esse planejamento será utilizado o framework DECIDE, onde cada letra da palavra é uma etapa a ser realizada no planejamento. A tabela 1 a seguir apresenta o significado de cada letra.

<center>

**Tabela 1** - Letras da palavra DECIDE com os seus significados.

| Letra |                          Definição                           |
| :---: | :----------------------------------------------------------: |
|   D   |            Determinar os objetivos da avaliação.             |
|   E   |   Explorar perguntas a serem respondidas com a avaliação.    |
|   C   |     Escolher os métodos de avaliação a serem utilizados.     |
|   I   | Identificar e administrar as questões práticas da avaliação. |
|   D   |          Decidir como lidar com as questões éticas.          |
|   E   |          Avaliar, interpretar e apresentar os dados          |

**Fonte** - BARBOSA e SILVA (2011).

</center>

## D - Objetivos

Os objetivos desta avaliação é verificar se os artefatos produzidos na [análise de tarefas](../../analiseRequisitos/analise_tarefas/HTA.md) estão em conformidade com os padrões exigidos para esse artefato estão sendo seguidos e se existe algum design alternativo para aplicação. Sendo assim, a avaliação será utilizada para se elicitar ideias e problemas não identificados na produção do artefato de Análise de Tarefas e que deverão ser implementados em uma nova versão do artefato.

<a id="met1"></a>

## E - Explorar Perguntas Respondidas com a Avaliação

Com base no objetivo da avaliação foram preparadas perguntas baseadas nos seguintes tópicos:
- verificar a conformidade com um padrão;
- comparar ideias e alternativas de design.
As perguntas selecionadas tem o intuito de serem respondidas com essa avaliação e foram feitas com base no as perguntas selecionadas foram as seguintes:

- Os diagramas HTA's possuem as notações corretas, legendas e a representação em tabela?
- Os diagramas representam tarefas condizentes com as funcionalidades esperadas para o site?
- A técnica KLM enquadra todas as etapas que condizem no HTA?
- As entrevistas permitem que sejam realizadas melhorias nas tarefas elucidadas pelo artefato de Análise de Tarefas?

## C - Escolher os Métodos de Avaliação

Para a realização da avaliação, utilizar-se-á de uma adaptação dos métodos de investigação, com o uso de entrevistas e observação com usuários com base em um questionário como roteiro.

A escolha se dá pelo fato de ser um método investigativo que permite coletar muitas informações, além de ser flexível permite fazer perguntas que aprofundam ainda mais os objetivos a serem alcançados pelos usuários. Ademais, tal entrevista deve ser estritamente **gravada** e **documentada**.

## I - Identificar Questões Práticas da Avaliação

### Recrutamento

O processo se inicia pelo recrutamento das pessoas entrevistadas, essas pessoas deverão ter as características elucidadas pelo [perfil de usuário](../../../../analise-de-requisitos/perfil-usuario) e pelas [personas](../../../../analise-de-requisitos/personas). Serão entrevistados os 2 integrantes do grupo, a fim de garantir a coleta de perspectivas diversas e um contato real com os usuários.

### Preparação

Os entrevistadores seguirão o roteiro de perguntas para conduzir as entrevistas, anotando as respostas dos usuários. As entrevistas devem incluir uma das atividades definidas na análise de tarefas, e os entrevistadores podem solicitar o compartilhamento de tela para observação direta das ações do usuário. Cada entrevista pode ser conduzida por um único entrevistador ou por uma dupla, com cada membro assumindo uma tarefa específica.

### Custos

A realização das entrevistas não irá gerar custos, isso porque todas as ferramentas que seram utilizadas são de acesso gratuito:

- [Microsoft Teams, Discord e Google Meet](../../planejamento/ferramentas.md);
- Perguntas para serem respondidas com a avaliação;
- Perguntas para serem respondidas na entrevista;
- Termo de Consentimento#met3;
- Teste Piloto;
- Diagrama HTA de cada Tarefa selecionada.

Vale resaltar que os equipamentos necessários serão quaisquer dispositivos com acesso a internet, aos aplicativos de comunicação e a um navegador de internet que os envolvidos possuírem.

### Prazos

Em relação aos prazos, as entrevistas estão documentadas na tabela 2, sendo apresentado um cronograma com seus tópicos e logo abaixo a tabela 2 com as entrevistas:

- Entrevistador;
- Entrevistado;
- Horário de início e fim;
- data que ocorreu a entrevista.

<center>

**Tabela 2** - Cronograma da entrevista.

| Entrevistador(es) | Entrevistado(s) | Horário de Início | Horário de Fim |    Data    |    Local     |
| :----------------: | :-------------: | :---------------: | :------------: | :--------: | :----------: |
|  [Márcio Henrique](https://github.com/DeM4rcio)  |   Bruno Bragança     |       16:40       |     16:45      | 20/12/2024 | Plataforma Google Meet |
|  [Luiza Maluf](https://github.com/LuizaMaluf) |    Lucas Gama    |       20:40       |     20:50      | 20/12/2024 | Plataforma Google Meets |


**Fonte** - _[Autores](../../index.md)_
</center>

<a id="met2"></a>

### Roteiro de Perguntas

Na entrevista estarão disponíveis capturas de tela para que o usuário possa ver a tarefa da qual o entrevistador estará comentando e a tabela com o seu fluxo. A tabela 3 a seguir mostra o roteiro de perguntas a serem realizadas na entrevista. Essas perguntas foram baseadas nas perguntas a serem [repondidas na avaliação](#met1).

<center>

**Tabela 3** - Roteiro de perguntas da entrevista.

| **Número** | **Pergunta**                                                                                          | **Resposta Possíveis**                                                                                      |
|:-----------:|:----------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------:|
| **1**      | Qual o seu nome?                                                                                      | Resposta Discursiva                                                                                        |
| **2**      | Qual seu grau de experiência com tecnologias?                                                        | Resposta Discursiva                                                                                        |
| **3**      | Como você iniciaria o processo no sistema do Detran?                                                 | [ ] Acessar o site/app do Detran e fazer login <br> [ ] Outro, como? <br> ⚠️ Informar para usar a conta Gov.br. |
| **4**      | Como você escolheria o serviço desejado (transferência ou agendamento)?                              | [ ] Selecionar o serviço na lista disponível <br> [ ] Outro, como?                                         |
| **5**      | Como você confirmaria os dados apresentados (veículo ou serviço)?                                     | [ ] Revisar e confirmar no sistema <br> [ ] Outro, como?                                                   |
| **6**      | Como você realizaria a autenticação digital?                                                         | [ ] Utilizar Gov.br para autenticação <br> [ ] Outro, como?                                                |
| **7**      | Como você selecionaria a data e horário de um agendamento?                                           | [ ] Escolher data e horário no calendário do sistema <br> [ ] Outro, como?                                 |
| **8**      | Como você efetuaria o pagamento das taxas necessárias?                                               | [ ] Gerar boleto/PIX e pagar pelo sistema <br> [ ] Outro, como?                                            |
| **9**      | Como você confirmaria a finalização do processo (transferência ou agendamento)?                     | [ ] Confirmar e baixar o documento digital <br> [ ] Outro, como?                                           |
| **10**     | Como você acessaria a central de ajuda em caso de dúvidas?                                           | [ ] Clicar em "Central de Ajuda" no site/app <br> [ ] Outro, como?                                         |
| **11**     | A sequência de processos apresentada está clara para você? Se não, por quê?                         | Resposta Discursiva <br> ⚠️ Mostrar a tarefa ao usuário e explicá-la.                                       |
| **12**     | Se houvesse um problema, você saberia como cancelar ou reagendar um serviço?                         | [ ] Sim, pelo painel de agendamentos <br> [ ] Outro, como?                                                 |
| **13**     | Observando os processos, há algo que você considera difícil ou confuso?                              | Resposta Discursiva                                                                                        |
| **14**     | Os processos refletem sua experiência real?                                                          | Resposta Fechada (Sim/Não)                                                                                 |
| **15**     | Você teria alguma sugestão de melhoria para os processos apresentados?                               | Resposta Discursiva                                                                                        |
| **16**     | Você tem alguma sugestão de melhoria para a interface do sistema (site/app)?                         | Resposta Discursiva                                                                                        |


**Autor** - [Márcio Henrique](https://github.com/DeM4rcio).

</center>

### Execução do roteiro

Nota se que as perguntas de 4 a 9.1 deverão ser realizadas de acordo com cada entrevista, se a entrevista é sobre o cancelamento de compra realiza a pergunta 6 e 6.1, por exemplo. As perguntas 10 e 11 deverão ser realizadas pelos entrevistadores responsáveis pela tarefa de Busca de Evento e Acessar a Central de Ajuda respectivamente. No mais, as outras perguntas devem ser realizadas por todos os entrevistadores.

## D - Lidando com as Questões Éticas



Será utilizado o termo de consentimentoproduzido na seção de [aspectos éticos](../../analiseRequisitos/aspEticos.md), a fim de se obter dos participantes a autorização para que sejam realizadas as atividades necessárias à produção desse artefato e garantir que os participantes sejam respeitados durante e após a atividade.

## E - Avaliar, Interpretar e Apresentar os Dados

Após a coleta de dados, estes serão analisados criticamente, considerando o contexto e a confiabilidade, a fim de verificar sua representatividade da população de usuários

A documentação dos dados incluirá o registro de problemas e dificuldades encontradas pelos usuários durante a interação com o site, como questões de usabilidade, funcionalidades ausentes e problemas de desempenho. Serão anotadas descrições detalhadas dos problemas, sua classificação, sugestões de melhoria e o feedback dos usuários. Ao final de cada entrevista, serão registradas observações gerais sobre o processo.

Os dados analisados serão compartilhados com a equipe de desenvolvimento para embasar as próximas etapas do projeto.




## Bibliografia

> RIBEIRO, Clara; SANTANA, Natan Tavares. Planejamento da avaliação da Análise de tarefas. Repositório do Grupo Agência Virtual Neoenergia Brasília da disciplina de Interação Humano Computador da Universidade de Brasília, 2022. Disponível em: <<https://interacao-humano-computador.github.io/2022.1-AgenciaVirtualNeoenergia/design%2C_avalia%C3%A7%C3%A3o%2C_desenvolvimento/n%C3%ADvel%201/an%C3%A1lise_de_tarefas/planejamento_tarefas/>>. Acesso em: 09 dezembro 2024.

> GABRIEL, Lucas; SOUZA, Nicolas. Planejamento da avaliação da Análise de tarefas. Repositório do Grupo Lichess da disciplina de Interação Humano Computador da Universidade de Brasília, 2022. Disponível em: <<https://interacao-humano-computador.github.io/2022.2-Lichess/design_avaliacao_desenvolvimento/nivel_1/analise_tarefas/planejamento_avaliacao/>>. Acesso em: 09 dezembro 2024.



## Referências Bibliográficas

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versões

| Versão | Data       | Descrição                                                                      | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------------------------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 09/12/2024 | Criação da página.                                    | [Márcio Henrique](https://github.com/DeM4rcio) | [Luiza Maluf](https://github.com/LuizaMaluf)   |