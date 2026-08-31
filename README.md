# FoodCampus
Projeto dedicada à atividade referente ao dia 25/08 - Do Problema ao Primeiro Backlog

## Problema Identificado
A falta de um sistema de controle nos pontos de alimentação da universidade gera um grande gargalo na organização interna e na interação com os clientes. Os alunos não sabem quais produtos estão disponíveis nem podem pedir e pagar com antecedência. Consequentemente, isso gera filas e longas esperas, a cantina não consegue prever os pedidos para adiantar o preparo e os estudantes não sabem quando o pedido está pronto.

## Objetivo(S)
Agilizar a operação e reduzir os gargalos, tanto para os funcionários da cantina quanto para os clientes. Reduzindo tempos de espera, facilitando processo de pedidos, pagamentos, e acompanhamento por parte do cliente, e melhorar a organização interna da cantina.

## Principais Usuários
### Funcionários:
Os principais usuários identificados seriam os atendentes: Jureuma e Jonathan e os cozinheiros, responsáveis por preparar todos os pedidos dos universitários: Ricardo, Paloma e Luciana.\
O dono do estabelecimento Ronaldo Gaucho, o gerente Valdir dos Santos, e o chefe de cozinha Paulo Machado.
### Clientes:
Os universitários frequentantes são os que estudam em blocos próximos à cantina.\
Os trabalhadores que fazem algum curso da faculdade.

## Histórias dos usuários
-> Queria, como universitário, não precisar ficar esperando na fila durante todo o intervalo... \
-> Como trabalhador e universitário, gostaria de ter mais tempo para comer no intervalo sem ter que esperar muito tempo na fila.\
-> Como funcionário, gostaria de aprimorar a agilidade de atendimento com alguma aplicação como o Ifood para evitar enfrentar uma fila enorme.\
-> Como gerente do estabelecimento, gostaria que tivesse mais uma cantina próxima para dividir movimento.\
-> Como chefe do estabelecimento, gostaria de ter uma base para conseguir analisar os produtos que mais saem e controlar os gastos de forma mais precisa.\
-> Como guarda do campus, com o movimento que gera na cantina, é impossível prestar atenção em tudo. Gostaria que o movimento diminuísse.\
-> Como atendente, ficaria mais fácil se tivesse um sistema onde os universitário consigam realizar seus pedidos sem precisar formar uma fila gigantesca e desorganizada. De forma que possam vir com o número do pedido para retirada.

## Histórias com Critério de Aceitação

"Como trabalhador e universitário, gostaria de ter mais tempo para comer no intervalo sem ter que esperar muito tempo na fila.:"\
Critério de Aceitação:\
- Sabendo que o estudante possui o aplicativo aberto antes do horário do intervalo, quando ele selecionar seus itens do cardápio e escolher um horário de retirada, então o sistema deve confirmar o pagamento e agendar a preparação do pedido para o horário solicitado.\
"Como atendente, ficaria mais fácil se tivesse um sistema onde os universitários consigam realizar seus pedidos de forma que possam vir com o número do pedido para retirada.:"
Critério de Aceitação:\
 - Agora que o atendente finalizou a preparação de um lanche no sistema, quando ele clicar em "Marcar como Pronto", o número do pedido deve aparecer no painel digital de chamadas da cantina, estilo BK\


## Histórias em Atividade Técnica
"Queria, como universitário, não precisar ficar esperando na fila durante todo o intervalo...":\
-Criar estrutura/model da entidade Fila e FichaDeAtendimento.\
-Criar migration para a tabela de senhas/fichas no banco de dados.\
-Criar endpoint para solicitação de senha/entrar na fila virtual via app.\
-Criar interface simples para o estudante pegar a senha e acompanhar a chamada.\
-Integrar frontend com o endpoint de fila virtual.\
-Criar testes da lógica de geração e ordenação de senhas.

"Como trabalhador e universitário, gostaria de ter mais tempo para comer no intervalo sem ter que esperar muito tempo na fila.":\
-Criar estrutura/model da entidade PedidoAgendado (com horário fixo de retirada e combo do lanche).\
-Criar migration da tabela de pedidos agendados no banco de dados.\
-Criar endpoint para agendar a refeição para o horário exato do intervalo.\
-Criar interface de visualização do cardápio express e seleção do horário do intervalo.\
-Integrar frontend com o endpoint de agendamento de refeições.\
-Criar testes das validações de horário e disponibilidade de preparo.

## MVP Identificado
**Objetivo:**Um cardápio digital com formatos de agendamento online
Um software com funcionalidades operacionais que funcionem de forma online com agendamentos via celular ou totem, com pagamento antecipado, facilitando defesa contra possíveis "fraudes" e também viabilidade para criar um login 
guardando possíveis pedidos anteriores que gostaria de repetir novamente, ou usuário "convidado" que envie uma cópia via contato direto com o cliente (Whatsapp, E-mail, SMS, etc). 
Scrum Master - Leonardo Portaluppi

## Labels

## Integrantes
### Scrum Master
Leonardo Portaluppi Ferreira - 2034186
### Demais participantes
-> Pedro Henrique Francisco do Nascimento - 2080759\
-> Luana Portellinha Marino - 2034925\
-> Raissa Kaori Kawakami - 2040357\
-> João Celso da Silva Nogueira dos Santos - 2031553\
-> Kendy Hashimoto - 2033463

[Link GitHub Projects](https://github.com/users/gup3323/projects/3)
