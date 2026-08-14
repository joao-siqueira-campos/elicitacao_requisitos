HISTORIAS DE USUARIO

1. ACOMPANHAR PEDIDO

Como usuario, desejo acompanhar o status do pedido, a fim de saber o andamento da entrega

Criterios de aceitacao

Dado que o pedido foi realizado
Quando o usuario acessar o acompanhamento
Entao o sistema devera mostrar o status do pedido

Dado que o pedido esta em andamento
Quando o status for atualizado
Entao o sistema devera mostrar a nova situacao

Dado que o pedido foi entregue
Quando o usuario consultar o acompanhamento
Entao o sistema devera informar que foi entregue


2. ITEM INDISPONIVEL

Como restaurante desejo informar que um item esta indisponivel a fim de evitar novos pedidos desse produto

Criterios de aceitacao

Dado que o item esta disponivel
Quando o restaurante marcar como indisponivel
Entao o sistema devera impedir novos pedidos

Dado que o item esta indisponivel
Quando o usuario visualizar o cardapio
Entao o sistema devera informar sua indisponibilidade

Dado que o item voltou a estar disponivel
Quando o restaurante alterar o status
Entao o sistema devera permitir novos pedidos


3. REPORTAR PROBLEMA

Como entregador desejo registrar problemas durante a entrega a fim de comunicar a ocorrencia.

Criterios de aceitacao

Dado que existe uma entrega em andamento
Quando o entregador acessar o registro de problemas
Entao o sistema devera permitir selecionar o tipo de problema

Dado que o problema foi selecionado
Quando o entregador confirmar
Entao o sistema devera registrar a ocorrencia

Dado que a ocorrencia foi registrada
Quando o registro for concluido
Entao o sistema devera exibir uma confirmacao


