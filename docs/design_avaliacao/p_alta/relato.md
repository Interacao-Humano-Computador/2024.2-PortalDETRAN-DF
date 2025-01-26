# Relato dos Resultados - Protótipo de Alta Fidelidade

## Introdução

Esse artefato tem o objetivo de documentar o relato dos resultados obtidos pela avaliação do protótipo de alta fidelidade. Portanto, serão abordados os tópicos referidos no [Planejamento do Relato dos Resultados do Protótipo de Alta Fidelidade](./planejamento_relato.md).

## Objetivo e Escopo da Avaliação

Garantir que o aplicativo do Detran-DF ofereça a melhor experiência possível aos seus usuários. Esta avaliação tem como propósito coletar feedback de usuários reais sobre um protótipo avançado do aplicativo, a fim de identificar e corrigir quaisquer problemas de usabilidade, funcionalidade e design antes do lançamento oficial.

- A interface segue o padrão do sistema operacional?
- Foi possível testar a interação e a facilidade de uso do protótipo para identificar problemas de usabilidade?
- Foi possível avaliar a aparência e o estilo visual do protótipo, garantindo que ele atenda às expectativas e necessidades dos usuários, transmita a identidade da marca e seja estéticamente agradável?
- Foi possível verificar se todas as funcionalidades planejadas estão presentes e funcionam corretamente?
- Foi possível obter opiniões, percepções e sugestões dos usuários em relação ao protótipo?
- Foi possível identificar quaisquer problemas, erros ou áreas que precisam de ajustes no protótipo antes da implementação final?

## Método de Avaliação

Utilizamos o teste de usabilidade como metodologia principal para avaliar a interface do sistema. Seguindo as premissas de Rubin (1994) e Rubin e Chisnell (2008), um grupo de usuários-alvo realizou tarefas específicas no sistema, enquanto suas interações foram observadas e registradas. Essa abordagem permitiu identificar problemas reais de usabilidade que poderiam passar despercebidos em avaliações mais teóricas. O cronograma detalhado dos testes, incluindo data, horário e participantes, encontra-se na Tabela 1.

<center>

**Tabela 1** - Cronograma Executado.

| Avaliador                                    | Usuário                                              | Data       | Início-Fim  | Local         |
| -------------------------------------------- | ---------------------------------------------------- | ---------- | ----------- | ------------- |
| [Márcio Henrique](https://github.com/DeM4rcio) | <span style = "color: black">Eduardo</span>  | 23/01/2025 | 16:30-16:45 | Presencial |
| [Márcio Henrique](https://github.com/DeM4rcio) | <span style = "color: orange">Rayssa</span>    | 23/01/2025 | 16:10-16:25 | Presencial |

Fonte: [Márcio Henrique](https://github.com/DeM4rcio) .

</center>

### Local

Os testes ocorreram de forma presencial, aos que foram realizadas pelo Márcio foram feitas fora das dependências da FCTE.
### Ferramentas

As ferramentas utilizadas foram as seguintes:

- Um notebook com webcam e microfone;
- Um smartphone utilizado para capturar áudios;
- Um papel contem o script a ser seguido pelos usuarios;
- Um papel contendo as tarefas e perguntas a serem respondidas.

### Tarefas

As tarefas realizadas pelos os usuarios foram as seguintes:

- Trasferência de veículos;


### Descrição dos Testes

Antes de se iniciar os testes em si foi apresentado ao usuário um _script_ contendo as ações que o entrevistado deveria realizar dentro do sistema. O entrevistado também foi orientado a reproduzir as ações que estava executando em voz alta. A figura 1 apresenta o _script_ seguido pelos usuários.

<center>

**Figura 1** - _Script_ seguido pelos usuários.

![Imagem do Script Utiizado](../../assets/design-avaliacao-desenvolvimento/script.png){ width="500" }

_Fonte: [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

O teste teve início com a apresentação ao usuário o termo de consentimento para que pudesse ser confirmado a sua participação e autorizado o prosseguimento do teste. Logo após, foi autorizado que o usuário realizasse as tarefas. 

### Protótipo de Alta Fidelidade

O Protótipo de Alta Fidelidade utilizado nos testes é apresentado a seguir. É importante salientar que o protótipo apresentado pode não ser o exato modelo utilizado nos testes, pois o protótipo sofre alterações e correções com o tempo.

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/proto/GEa9juWMtQmy4fyHLa6cTU/html.to.design-%E2%80%94-by-%E2%80%B9div%E2%80%BARIOTS-%E2%80%94-Import-websites-to-Figma-designs-(web%2Chtml%2Ccss)-(Community)?node-id=0-1&t=T5NaYKvtkJLs12ai-1" allowfullscreen></iframe>

### Teste Piloto

O vídeo 1 a seguir mostra o teste piloto realizado antes dos testes.

<center>

Vídeo 1 - Teste Piloto

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=TtG0XDYMJrY"></iframe>

_<font size="3">_Autor: [Márcio Henrique](https://github.com/DeM4rcio), 2025._</p></font>_

</center>

## Seleção dos Participantes

O número de participantes foi de 6 pessoas, sendo dois avaliadores em que ficaram responsáveis por, gravação do áudio e vídeo e quatro usuários. A escolha desse número de usuários foi baseada na recomendação de Krug (2010, p. 157) para testes de usabilidade. Além disso, os usuários foram escolhidos levando em conta as características definidas no [perfil de usuário](../../analiseRequisitos/personas.md), sendo elas: idade entre 20 e 35 anos, experiência e afinidade com tecnologia. A tabela 1 apresenta os participantes da avaliação e suas respectivas funções.

</center>

## Problemas e Dificuldades Encontradas

A princípio, os testes ocorreram sem muitos problemas. Foi encontrado três problemas, um em uma funcionalidade e os outros dois ligados a interface da aplicação.

Em relação ao problema de funcionalidade a entrevistada **Rayssa** alegou que no final da página de transferência de veículos, quando há a conlusão da solicitação, não foi possivel voltar a página inicial. Já em interface houve duas dificuldades em usuário entender que dentro do contexto da transferência todas essas ações são visâo do vendedor e não do comprado; Outro ponto foi a dificuldade de enteder a etapa de validação da identidade.

<center>

**Tabela 3** - Problema 1: Função de Redirecionamento.

| Item de Análise                      | Descrição                                                        |
| ------------------------------------ | ---------------------------------------------------------------- |
| Local:                               | Tela de conclusão do solicitação de transferência.                                       |
| Contexto:                            | O usuário finaliza a transferência e ao final deseja acessar outro serviço do portal. |
| Causa:                               | Não redirecionamento para a página inicial.               |
| Ação Realizada pelo Usuário:         | Clique no botão "Voltar ao menu inicial".                                   |
| Resposta do Sistema Esperada:        | Redirecionamento na tela inicla.               |
| Resposta do Aprsentada pelo Sistema: | Não foi redirecionado.         |
| Fatores de Usabilidade Prejudicados: | Eficácia e Eficiência.                                |

_Autor: [Márcio Henrique](https://github.com/DeM4rcio), 2025._

</center>

Sobre o problema de interface, a usuária **Rayssa** alegou que não ficou clara na seção do qr code, é uma etapa de verificação de identidade, achou que ficou pouco claro e tendendo a scannear o qr sem reconhecer a etapa em que se encontra. As tabelas 4 e 5 a seguir apresenta as avaliações dos problemas.

<center>

**Tabela 4** - Problema 2: Detalhes sobre a validação de Identidade.

| Item de Análise                      | Descrição                                                         |
| ------------------------------------ | ----------------------------------------------------------------- |
| Local:                               | Modal de verificação de identidade.                                           |
| Contexto:                            | O usuário entra na página com a intenção de trasnferir um veículo. |
| Causa:                               | As informações não deixa claro a ação desejada do usuário.                             |
| Ação Realizada pelo Usuário:         | Visualizou as etapas de identificação.                                     |
| Resposta do Sistema Esperada:        | Entendimento claro da etapa.                        |
| Resposta do Aprsentada pelo Sistema: | A etapa não foi bem especificado.               |
| Fatores de Usabilidade Prejudicados: | Eficácia, Eficiência e Segurança.                                 |

_Fonte: [Marcio Henrique](https://github.com/DeM4rcio), 2025._

</center>

<center>

**Tabela 5** - Problema 3: Clareza em qual "personagem" o usuário se aplica.

| Item de Análise                      | Descrição                                                                  |
| ------------------------------------ | -------------------------------------------------------------------------- |
| Local:                               | Página inicial.                                                    |
| Contexto:                            | O usuário entra na página de pedidos com a intenção de realizar uma tranferência. |
| Causa:                               | Não existe uma indicação de que quem irá realizar a transferência é o vendedor.                                  |
| Ação Realizada pelo Usuário:         | Visualizou o botão na página.                                              |
| Resposta do Sistema Esperada:        | Apresentação de forma clara quem será o responsável pela transferência.                 |
| Resposta do Aprsentada pelo Sistema: | Não possui apresentação.                                           |
| Fatores de Usabilidade Prejudicados: | Eficácia, Eficiência e Segurança.                                          |

_Fonte: [Márcio Henrique](https://github.com/DeM4rcio), 2025._

</center>

## Sugestões de Melhoria

Tendo em vista os problemas elicitados no tópico anterior, ficam as seguintes sugestões de correção:

- Incluir a funcionalidade de redirecionamento para a página inicial;
- Alterar o design do modal de identificação do usuário;
- Criar uma seção de ajuda para entende de quem é a responsabilidade de realizar a transferência.

## Feedback dos Usuários

### Teste 1 - Eduardo

O usuário não encontrou muitas dificuldades na realização das tarefas. A tarefa de Tranferência foi realizada com apenas 6 clique e 1 scroll down da página.

Somado a isso, foi observado uma atitude confiante na realização das tarefas de Transferência. E concluído sem nenhuma dificuldade.

### Teste 2 - Rayssa

O usuário não encontrou muitas dificuldades na realização das tarefas. A tarefa de Tranferência foi realizada com apenas 6 clique e 1 scroll down da página.

Outrossim, o design e a visualização tanto das etapas de identificação e no final da transferência, a usuária teve uma leve dificuldade em entender os passos reralizados e demorando mais que o normal para a mudança de telas. Somado a isso, foi observado uma mudança significativa nas expressões faciais sendo elas de demonstração de não muita confiança nas ações sendo realizadas.


## Análise e Interpretação dos Usuários

Analisando os comportamentos dos usuários, percebemos que a maioria possui um nível de produtividade parecido, sendo que tarefas foram concluídas com quantidades de cliques similares. É possível notar também que há um problema crítico em relação ao botão de cancelamento, pois todos os usuários reclamaram do design pouco chamativo dele e na tela de confirmação de compra que não possui uma clareza no que está sendo realizado.

Contextualizando com as perguntas-objetivos, podemos respondê-las da seguinte maneira:

- A interface segue o padrão do sistema operacional?

Sim, não houve reclamações referente a isso.

- Foi possível testar a interação e a facilidade de uso do protótipo para identificar problemas de usabilidade?

Sim, foi possível identificar problemas de ao atingir as metas de usabilidade propostos para o projeto.

- Foi possível avaliar a aparência e o estilo visual do protótipo, garantindo que ele atenda às expectativas e necessidades dos usuários, transmita a identidade da marca e seja estéticamente agradável?

Sim, os usuários demonstraram seus pontos de vista dissonantes  em relação a aparência das escritasm mostrada em modais e tela geral do sistema.
 
- Foi possível verificar se todas as funcionalidades planejadas estão presentes e funcionam corretamente?

Sim, foi identificado que uma das funcionalidades previstas ainda não está totalmente implementada.

- Foi possível obter opiniões, percepções e sugestões dos usuários em relação ao protótipo?

Sim, os usuários apresentaram opiniões que serviram de objetivos para o reprojeto.

- Foi possível identificar quaisquer problemas, erros ou áreas que precisam de ajustes no protótipo antes da implementação final?

Sim, foi observado problemas que deverão ser corrigidos no reprojeto.

## Sumário dos Principais Resultados

Desse modo, em relação às metas de usabilidade priorizadas é perceptível que o sistema consegue fornecer um boa eficiência aos usuários em determinadas situações, sendo que a maioria das tarefas foram realizadas com menos de 5 cliques. Mas, ainda há problemas em relação aos elementos de interações na interface.

Em relação a segurança, o sistema ainda não fornece uma boa segurança aos usuário principalmente na tela de confirmação de transferência não é claro oque o usuário realizou e se foi atinjido com sucesso, porém houve uma melhora com o usuário tendo que confirmar suas intenções ao realizar ações críticas.


<center>

**Vídeo 2 - Teste 1: Eduardo**
<iframe width="560" height="315" src="https://www.youtube.com/watch?v=uhaEsxBrThs"></iframe>

_<font size="3">Autor: [Márcio Henrique](https://github.com/DeM4rcio), 2025.</p></font>_

</center>

<center>

**Vídeo 3 - Teste 2: Rayssa**

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=PVwn1hXtPuc"></iframe>


_<font size="3">Autor: [Márcio Henrique](https://github.com/DeM4rcio), 2025.</p></font>_

</center>


## Planejamento do Reprojeto

Para o reprojeto, as correções devem ser realizadas seguindo a lista de sugestão de correção apresentada anteriormente. O responsável por cada correção deve submetê-las para o time no intuito de se revisar as correções feitas, checando se elas são suficientes e se foi introduzido novos erros ou não. A tabela 6 a seguir apresenta o cronograma do reprojeto.


## Referências Bibliográficas

> KRUG, Steve. Don’t Make Me Think, Revisited. New Riders, 2014.

> RUBIN, J. **Handbook of Usability Testing.** New York: John Wiley & Sons, 1994.

> RUBIN, J.; CHINSNELL, D. **Handbook of Usability Testing: How to Plan, Design, and Conduct Effective Tests, 2ed.** Indianapolis: Wiley Publishing, Inc., 2008.

## Histórico de Versões

| Versão  | Data       | Descrição                                                                                                                                      | Autor(es)                                        | Revisor(es)                                      |
| ------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`   | 25/01/2023 | Criação da página e entrevistas do márcio.                                                                                                                             | [Márcio Henrique](https://github.com/DeM4rcio)      | [luiza maluf](https://github.com/LuizaMaluf) |
