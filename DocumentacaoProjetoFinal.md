# Rosy - Aplicação web de salão de beleza

_Krishna Eduardo e Gabriel Varysco_

Documentação do projeto final na unidade curricular Projeto de Desenvolvimento II do curso Análise e Desenvolvimento de Sistemas do Centro Universitário Senac-RS.

## Resumo do Projeto

Para resolver a inconveniência que um salão de beleza enfrenta ao realizar todo o atendimento, verificação de disponibilidade e agendamento pelo WhatsApp — perdendo muito tempo, tanto do cliente, que precisa esperar até ser respondido, quanto da pessoa que trabalha no salão, que precisa responder e depois esperar a resposta do cliente, verificar a agenda etc. Para isso desenvolvemos uma aplicação WEB, onde as pessoas podem verificar os horários disponíveis e realizar o agendamento, caso necessário.

## Definição do Problema

Um salão de beleza estava tendo os seguintes problemas:

* Complexidade de lidar com constantes mensagens no WhatsApp sobre a disponibilidade de horários.
* Perda de horários de clientes que agendavam e não compareciam.
* Dificuldade de visualização do fluxo de agendamentos que ocorreram durante o mês.

Para isso, a aplicação web (site) foi desenvolvida, resolvendo os problemas das seguintes maneiras:

* Eliminamos completamente a necessidade do cliente ter que chamar no WhatsApp e do colaborador ter que responder, checar horário e agendar. 
Com um sistema onde a pessoa apenas precisa entrar no site, ver a hora que deseja e fazer o agendamento.

* Também eliminamos a perda de horários e dinheiro com clientes que agendavam e não compareciam.
Colocando um valor simbólico para fazer o agendamento, que será descontado do valor total do serviço utilizado na hora (tendo um tempo para cancelamento com reembolso do valor).

* Facilitamos a visualização do fluxo de agendamentos e de receita no período que for escolhido para ser visualizado.
Com gráficos e estatísticas para facilitar o entendimento de algumas métricas, tais como: quantos agendamentos foram realizados em determinado período de tempo, estimativa de receita gerada e valores gerados apenas dos agendamentos.

## Objetivos

O objetivo geral é transferir o fluxo de usuários que fazem o agendamento pelo WhatsApp para que comecem a utilizar o site. Também esperamos as seguintes coisas:

* Melhorar a experiência do cliente. 
* Reduzir o trabalho desnecessário dos colaboradores do salão de beleza, automatizando processos.
* Facilitar a visualização dos agendamentos do dia.
* Ajudar a ter um controle financeiro melhor.

## Stack Tecnológico

Front-End:

* React
Ótima biblioteca para desenvolvimento de interfaces, sem ter um nível de complexidade alto e com várias ferramentas e bibliotecas para auxiliar no desenvolvimento.

* Typescript/JavaScript 
É a linguagem mais utilizada no desenvolvimento web, tendo uma curva de aprendizado muito suave.

* TailwindCSS
Traz vários benefícios, como desenvolvimento rápido, fácil implementação de responsividade, facilidade de customização, entre outros.

Back-End:

* Next.js (Criação de API)
* Supabase (postgreSQL)

## Descrição da Solução

Ao abordar os problemas do salão de beleza, nós desenvolvemos as seguintes soluções:

* Auto-atendimento
  Transferindo o fluxo de usuários para o site, melhoraremos a qualidade do atendimento e o tempo de resposta do cliente, mostrando a ele a qualquer momento todos os horários e profissionais disponíveis em um calendário interativo e simples, melhorando a experiência do
  cliente.

* Taxa de agendamento
  Aplicamos também uma taxa de agendamento, que será descontada na hora do pagamento no local de atendimento, assim eliminando a perda de dinheiro e horários com clientes que faziam agendamentos e não compareciam ou desmarcavam horas antes. Caso o cliente cancele o agendamento com antecedencia, terá seu dinheiro reembolsado sem custos adicionais.

* Visualização de agendamentos
  Com uma interface fácil e simples de ser acessada e monitorada, facilitamos a visualização do fluxo de agendamentos e de receita mensal do salão, com gráficos e estatísticas que podem facilitar a visualização de métricas como quantidade de agendamentos, estimativa de receita e lucro gerado com agendamentos efetivados.

## Arquitetura

Para o desenvolvimento da arquitetura seguimos os princípios do Clean Code e as melhores práticas de desenvolvimento, sempre com o objetivo de proporcionar a melhor experiência para o usuário.

## Conclusões

Para o funcionamento completo da aplicação web (site), é essencial a participação de clientes ativos.

O projeto atingiu com sucesso seu objetivo no escopo do MVP, permitindo o agendamento de serviços, escolha de profissionais e aplicação da taxa de agendamento. 
A solução foi validada por meio da avaliação da cliente (proprietaria do salão de beleza).

### Ideias Futuras
* Desenvolvimento e inclusão de um chatbot para a ajuda e apoio de usuários com dificuldade e dúvidas de como utilizar a aplicação.
* Aplicativo mobile
* Programa de fidelidade

## Referências Bibliográficas

* MARTIN, Robert C. Código limpo: habilidades práticas do Agile software. 1. ed. São Paulo: Alta Books, 2009.
* https://ui.shadcn.com/docs
* https://react.dev/

