# 🐞 BUG02 - Sistema permite finalizar compra sem preencher dados obrigatórios 

## 📌 Descrição
O sistema permite que os usuários finalizem a compra sem preencher dados obrigatórios. Isso pode levar a problemas de processamento de pedidos.

## ✅ Comportamento esperado
O sistema deve impedir a finalização do checkout. Deve exibir uma mensagem de erro informando quais campos obrigatórios estão faltando.

## ❌ Comportamento atual
O sistema permite a finalização da compra mesmo quando os campos obrigatórios não estão preenchidos.

## 🔁 Passos para reproduzir
Acessar a aplicação SauceDemo

Realizar login com usuário válido

Adicionar um produto ao carrinho

Acessar o carrinho

Iniciar o processo de checkout

Não preencher os campos obrigatórios (ex: First Name, Last Name, Postal Code)

Tentar finalizar a compra

## ⚠️ Severidade
Alta

## 🎯 Prioridade
Alta

## 🔗 Relacionado à User Story
US03 - Checkout