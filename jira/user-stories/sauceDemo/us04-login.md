## US02 - Login SauceDemo

## Descrição 
Como usuário 
Quero preencher os campos de login
Para finalizar a autenticação no sistema

## Contexto
Este cenário envolve a funcionalidade de login no site do SauceDemo. O foco é garantir que o sistema autentique usuários corretamente.

## Critérios de aceitação
O sistema deve permitir login com credenciais válidas.

O sistema deve apresentar erro com credenciais inválidas.

O sistema deve impedir login com credenciais bloqueadas.

O sistema deve redirecionar o usuário autenticado para a página inicial.

O sistema não deve permitir acesso sem autenticação.



## Subtasks 

### 🟨 QPP19 - Criar cenário de teste para realizar login 

## Descrição
Cenários de teste de funcionalidade de login utilizando BDD: 

Scenario: Login com credenciais validas
Scenario: Login com credenciais invalidas
Scenario: Login com usuario bloqueado

### 🟨 QPP20 - Executar testes manuais de login 

## Descrição
Execução de testes manuais de login válido, inválido e bloqueado para testar as funcionalidades de login.

### 🟨 QPP 21 - Criar automação do teste com Cypress

## Descrição
Criar automação dos testes manuais com Cypress utillizando BDD e Custom Commands.