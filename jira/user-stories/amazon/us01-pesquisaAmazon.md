# US01-PesquisaAmazon 

## Descrição 
Como usuário 
Quero pesquisar um produto 
Para encontrar o produto de meu interesse

## Contexto
O usuário deseja pesquisar produtos pelo nome na plataforma para encontrar itens de interesse.

## Critérios de aceitação
O sistema deve permitir inserir um termo de busca.

O sistema deve exibir uma lista de produtos relacionados à busca.

O sistema não deve apresentar erro ao realizar a busca.

Os resultados devem conter informações básicas do produto (nome, preço ou imagem). 



## Subtasks 

### 🟨 QPP14 - Criar cenário de teste para buscar produto 

## Descrição
Cenário de teste de funcionalidade de busca utilizando BDD: 

Scenario: Buscar produto com sucesso
Given que o usuário acessa o site da Amazon
When ele pesquisa por Iphone 15
Then os resultados da busca devem ser exibidos

### 🟨 QPP15 - Executar teste manual de busca

## Descrição 
Executar teste manual para testar a funcionalidade de busca.

### 🟨 QPP16 - Criar automação da busca com Cypress

## Descrição 
Criar automação do teste manual utilizando Cypress, Page Object e BDD.

