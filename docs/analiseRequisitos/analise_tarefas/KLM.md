
## Introdução

A técnica KLM, a mais básica dentro da família GOMS, restringe a análise a um conjunto pré-determinado de operadores primitivos. Esses operadores representam ações simples como digitar, clicar, mover o mouse, desenhar e processar informações mentalmente. Além disso, o modelo considera o tempo de resposta do sistema como um fator relevante no desempenho do usuário.[Barbosa e Silva (2011, p.198)](../referencias/klm.png). Na tabela 1 é mostrado o tempo de execução de cada ação.

**Tabela 1**
![HTA](../referencias/tabelaKLM.png)
<font size="3"><p style="text-align: center">_Fonte: BARBOSA e SILVA, 2011._<a id=anchor_1 href="#REF1"></a></p></font>

## Motivo de Escolha

A escolha de um KLM (Keystroke-Level Model) é motivada pela sua capacidade de avaliar de maneira detalhada o tempo necessário para realizar tarefas específicas, permitindo identificar ações que otimizam a interação do usuário com sistemas.Para tarefas no site do Detran, o uso do KLM oferece insights claros sobre quais ações são mais rápidas, quais exigem mais esforço cognitivo ou físico, e como melhorar a experiência geral de navegação e interação para o usuário. Nas tabelas 2 a 5 é listado os KLM's de cada tarefa.

###  Transferência de Veículo

**Tabela 2**
| Etapa                 | Descrição                                          | Tipo de Operação | Tempo Estimado (s) |
|-----------------------|--------------------------------------------------|------------------|---------------------|
| **1.1**              | Acessar o site do Detran                          | [P] Apontar      | 1.1                 |
| **1.2**              | Clicar no menu "Veículos"                         | [K] Clique       | 0.2                 |
| **1.3**              | Selecionar a opção "Transferência de veículo"     | [P] Apontar      | 1.1                 |
| **1.4**              | Preencher o formulário com dados do veículo       | [K] Digitar      | Variável (15-30)    |
| **1.5**              | Confirmar a operação                              | [K] Clique       | 0.2                 |
| **Total Aproximado** |                                                    |                  | ~20-35 segundos     |

<font size="3"><p style="text-align: center">_Autor: [Márcio Henrique](https://github.com/DeM4rcio)<a id=anchor_1 href="#REF1"></a></p></font>


>Conclusão: A ação de transferência de veículo é prática, com poucos passos claros. No entanto, o tempo pode variar significativamente devido à complexidade dos dados a serem preenchidos no formulário. Para maior eficiência, é recomendável que o usuário tenha todas as informações previamente organizadas.

---

###  Informações Veiculares

**Tabela 3**

| Etapa                 | Descrição                                          | Tipo de Operação | Tempo Estimado (s) |
|-----------------------|--------------------------------------------------|------------------|---------------------|
| **2.1**              | Acessar o site do Detran                          | [P] Apontar      | 1.1                 |
| **2.2**              | Clicar no menu "Veículos"                         | [K] Clique       | 0.2                 |
| **2.3**              | Selecionar a opção "Informações veiculares"       | [P] Apontar      | 1.1                 |
| **2.4**              | Digitar a placa do veículo                        | [K] Digitar      | 5                   |
| **2.5**              | Confirmar a consulta                              | [K] Clique       | 0.2                 |
| **Total Aproximado** |                                                    |                  | ~7-8 segundos       |

<font size="3"><p style="text-align: center">_Autor: [Márcio Henrique](https://github.com/DeM4rcio)<a id=anchor_1 href="#REF1"></a></p></font>

>Conclusão: A consulta de informações veiculares é uma das ações mais rápidas e diretas. Seu tempo reduzido e baixa complexidade tornam esta tarefa altamente eficiente, especialmente para usuários que realizam consultas frequentes.


---

### Agendamento de Serviço

**Tabela 4**

| Etapa                 | Descrição                                          | Tipo de Operação | Tempo Estimado (s) |
|-----------------------|--------------------------------------------------|------------------|---------------------|
| **3.1**              | Acessar o site do Detran                          | [P] Apontar      | 1.1                 |
| **3.2**              | Clicar no menu "Serviços"                         | [K] Clique       | 0.2                 |
| **3.3**              | Selecionar "Agendamento de serviço"               | [P] Apontar      | 1.1                 |
| **3.4**              | Preencher o formulário com dados do agendamento  | [K] Digitar      | Variável (15-30)    |
| **3.5**              | Confirmar o agendamento                           | [K] Clique       | 0.2                 |
| **Total Aproximado** |                                                    |                  | ~20-35 segundos     |

<font size="3"><p style="text-align: center">_Autor: [Márcio Henrique](https://github.com/DeM4rcio)<a id=anchor_1 href="#REF1"></a></p></font>

>Conclusão: O agendamento de serviço exige um tempo moderado devido ao preenchimento de dados específicos. Apesar disso, a organização prévia das informações e a interface amigável podem tornar o processo mais ágil. É uma solução vantajosa para evitar filas presenciais.


---

### Acesso à CNH do Usuário

**Tabela 5**

| Etapa                 | Descrição                                          | Tipo de Operação | Tempo Estimado (s) |
|-----------------------|--------------------------------------------------|------------------|---------------------|
| **4.1**              | Acessar o site do Detran                          | [P] Apontar      | 1.1                 |
| **4.2**              | Clicar no menu "CNH"                              | [K] Clique       | 0.2                 |
| **4.3**              | Selecionar "Consultar minha CNH"                  | [P] Apontar      | 1.1                 |
| **4.4**              | Digitar CPF e senha                               | [K] Digitar      | 5                   |
| **4.5**              | Confirmar o login                                 | [K] Clique       | 0.2                 |
| **Total Aproximado** |                                                    |                  | ~7-8 segundos       |

<font size="3"><p style="text-align: center">_Autor: [Márcio Henrique](https://github.com/DeM4rcio)<a id=anchor_1 href="#REF1"></a></p></font>

> Conclusão:O acesso à CNH é rápido e eficiente, desde que o usuário tenha seus dados de login disponíveis. Este processo oferece uma maneira conveniente de acessar informações pessoais sem depender de atendimento presencial.




## __Referências Bibliográficas__

> _BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011._


---
## __Histórico de versão__

| Versão |    Data    |      Descrição      |             Autor(es)                        |Revisor(es)|
|--------|------------|---------------------|----------------------------------------------|---------|
| `1.0`  | 30/11/2024 | Adição de informações da analise de tarefas. | [Márcio Henrique](https://github.com/DeM4rcio)|[Luiza Maluf](https://github.com/LuizaMaluf)|