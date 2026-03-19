## US03 - Checkout SauceDemo 

## Descrição 
Como usuário autenticado
Quero finalizar a compra
Para adquirir os produtos selecionados

## Contexto

Esse cenário refere-se ao processo de finalização de compras no sistema SauceDemo. É necessário que o usuário esteja autenticado e possua produtos no carrinho.

## Critérios de aceitação
O usuário deve estar autenticado para acessar o checkout.

O sistema deve permitir a finalização da compra quando todos os dados obrigatórios forem preenchidos corretamente.

O sistema deve exibir mensagem de erro ao tentar finalizar o checkout com dados obrigatórios ausentes.

O sistema deve impedir a finalização da compra sem autenticação.

O sistema deve exibir confirmação de pedido após finalização com sucesso.

## Subtasks 

### 🟨 QPP29 - Criar cenário de teste para o checkout 

## Descrição
Cenário de teste da funcionalidade do checkout utilizando BDD: 

Scenario: Checkout válido do usuário
Scenario: Checkout inválido do usuário


### 🟨 QPP30 - Executar testes manuais do checkout 

## Descrição 
Executar testes manuais válido e inválido para testar as funcionalidades de checkout.


### 🟨 QPP31 - Criar automação do checkout com Cypress

## Descrição 
Criar automação do checkout utilizando Cypress, BDD e Custom Commands.