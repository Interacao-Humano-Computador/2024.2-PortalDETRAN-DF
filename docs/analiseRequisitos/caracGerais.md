# __Características Gerais__

## __Introdução__

Tendo em vista o fluxo do [Processo de Design](../planejamento/processoDesign.md#engenharia-de-usabilidade-de-mayhew) escolhido para orientar esse projeto, é importante tratar das características da plataforma a fim de se fazer uma análise completa dos requsitos. 

Este artefato tem como propósito destacar as características principais da plataforma, mapeando os fluxos mais utilizados pelos usuários e os percursos seguidos para alcançar seus objetivos. Também busca identificar e avaliar fatores que possam dificultar ou gerar insatisfação durante a navegação, categorizados aqui como limitações e barreiras.


## __Metodologia__

A metodologia adotada neste artefato é a Inspeção, uma abordagem que, conforme descrito por [Barbosa e Silva (2011, p.301 e p.303)](referencias/metdCaracPlata.png), permite o avaliador realizar uma análise detalhada da interface sem a necessidade direta de envolvimento dos usuários durante o processo inicial.

A Inspeção envolve o exame minucioso de aspectos-chave da plataforma, como usabilidade, acessibilidade e eficiência, baseando-se em critérios e diretrizes previamente estabelecidos. Esse método é amplamente utilizado para identificar problemas de interação, barreiras de uso e oportunidades de melhoria antes mesmo de realizar testes com usuários reais.


## __Aspectos Inspecionados__

### __Estrutura e Organização da Informação__

- __*Pontos Positivos:*__

    - O menu principal está localizado no topo da página, com opções claras como Veículos, Agendamentos, Infrações, entre outros.

    - Há uso de ícones e textos para auxiliar a navegação, especialmente em consultas frequentemente realizadas pelos usuários.
    
    - A página inicial apresenta informações importantes de forma destacada, como notificações e comunicados.

- __*Limites e Entraves:*__

    - Falta um mecanismo de busca eficiente para ajudar os usuários a encontrar informações diretamente, sem navegar por várias seções.
        
    - Informações úteis, como horários de atendimento presencial ou telefones de contato, não estão centralizadas de forma clara na página inicial.

    - Os nomes das subseções de "Consultas", "Emissão", "Tansferência/inclusão" são muito sintetizados, o que não deixa explícito para o usuário qual exata consulta ele pode utilizar.

### __Navegabilidade e Fluxos de Uso__

- __*Pontos Positivos:*__
        
    - O site é responsivo e adapta-se bem a dispositivos móveis, o que é essencial considerando o perfil de muitos usuários.
        
    - Os fluxos para agendamentos e consultas estão relativamente bem definidos.

- __*Limites e Entraves:*__
        
    - O usuário pode apresentar dificuldade em navegar pelas funcionalidaes uma vez que não existe, como  por exemplo, uma página de consultas com todas as consultas e uma especificação de cada uma.

    - O usuário precisa estar logado para ter acesso a certos tipos de informações, sendo que existe a possibilidade dele não saber o que o título da consulta significa.

    - Os termos utilizdos nas "Consultas" não são intuitivos para novos usuários como por exemplo, _"Veículo - Débito", "Veículo - SNG", "Veículo - Km", "Veículo - Nada consta"_.

    - Os formulários possuem campos a serem preenchidos, contudo os campos possuem a orientação "Selecionar" sendo que não há opções a serem selecioandas.

    - A página de login não possui a possibilidade de recuperação de senha e nem de "Esqueci minha senha".


### __Consistência e Design__

- __*Pontos Positivos:*__

    - A identidade visual é consistente com a proposta institucional, utilizando cores que remetem à identidade do DETRAN.
        
    - Ícones e textos apresentam uma linguagem formal e institucional, adequada ao público-alvo.

- __*Limites e Entraves:*__
        
    - A interface carece de contrastes adequados em algumas seções, dificultando a leitura para pessoas com deficiências visuais ou baixa visão.

    - O layout pode ser percebido como antiquado e pouco atrativo em comparação com padrões modernos e até mesmo muito simples.

### __Acessibilidade__

- __*Pontos Positivos:*__
        
    - O site possui uma estrutura com a fonte dos textos de tamanho adequado, podendo facilitar a leitura para pessoas com dificuldades.

    
- __*Limites e Entraves:*__
        
    - Não foi identificado suporte robusto para leitores de tela, o que pode limitar o acesso para pessoas com deficiências visuais.

    - Não há uma opção de tema de alto contraste ou modo noturno, que poderia beneficiar pessoas com baixa visão ou sensibilidade à luz.

    - O conteúdo textual utiliza linguagem técnica ou burocrática em algumas seções, o que pode dificultar a compreensão para certos tipos de usuários.


### __Funcionalidades e Conteúdo__

- __*Pontos Positivos:*__

    - O portal oferece integração com serviços digitais, como emissão de boletos e consulta de infrações.

    - A página inicial exibe atalhos para funcionalidades importantes, como "Consulta CNH" e "Autorização para estacionamento".

- __*Limites e Entraves:*__
        
    - O portal não apresenta tutoriais ou guias interativos para ajudar usuários iniciantes a realizar tarefas mais complexas.

    - Maior parte das funcionalidades e acesso aos conteúdos são bloqueados ao usuário, sendo liberadas para quando ocorrer o login.


## __Referências Bibliográficas__

>_BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011._

---

## __Histórico de versão__

| Versão |    Data    |      Descrição      |             Autor(es)                        | Revisores |
|--------|------------|---------------------|----------------------------------------------|-----------|
| `1.0`  | 01/12/2024 | Descrição das características Gerais do Projeto. | [Luiza Maluf](https://github.com/LuizaMaluf) |  |