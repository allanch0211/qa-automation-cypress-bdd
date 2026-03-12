# 🧪 Projeto de Automação de Testes | QA Portfolio

Este repositório contém meus estudos e práticas em **Automação de Testes Web e API**, com foco em qualidade de software, organização de projeto e boas práticas utilizadas no mercado de QA.

O objetivo do projeto é consolidar conhecimentos em:

- Testes Funcionais
- Testes Regressivos
- BDD (Behavior Driven Development)
- Automação Web
- Testes de API

Este projeto representa minha evolução prática na área de **Quality Assurance**.

---

# 🚀 Tecnologias Utilizadas

### Automação Web
- Cypress
- Cucumber (BDD) – `@badeball/cypress-cucumber-preprocessor`
- Page Object Model (POM)
- Custom Commands
- JavaScript

### Testes de API
- Postman
- Test Scripts (JavaScript)

### Relatórios
- Allure Reports

### Ferramentas
- Git
- GitHub

---

# 🧠 Conceitos Aplicados

✔ Testes Funcionais  
✔ Testes Negativos  
✔ Fluxos End-to-End (E2E)  
✔ Testes de API REST  
✔ Estrutura baseada em Page Object  
✔ Organização por Features (BDD)  
✔ Validação de respostas JSON  
✔ Versionamento com Git Flow

---

# 📂 Estrutura do Projeto


cypress/
┣ e2e/
┃ ┗ features/
┃ ┣ SauceDemo/
┃ ┗ Amazon/

support/
┣ pages/
┣ step_definitions/
┣ commands/

fixtures/

postman/
┣ collections/
┃ ┣ books-api-tests.json
┃ ┣ fakestore-api-tests.json
┃ ┗ reqres-api-tests.json.json


---

# 📸 Evidências de Execução

## ✅ Execução dos Testes Web (Cypress)

![image alt](https://github.com/allanch0211/TesteGitHub/blob/51b4fce4313f77e5c31db110958734d17cf49feb/docs/images/cypress-run.png)

---

## 📊 Relatório Allure

![image alt](https://github.com/allanch0211/TesteGitHub/blob/51b4fce4313f77e5c31db110958734d17cf49feb/docs/images/allure-overview.png)

---

## 📁 Estrutura do Projeto

![image alt](https://github.com/allanch0211/TesteGitHub/blob/51b4fce4313f77e5c31db110958734d17cf49feb/docs/images/project-structure.png)

---

## 🧪 Exemplo de Cenário BDD

![image alt](https://github.com/allanch0211/TesteGitHub/blob/51b4fce4313f77e5c31db110958734d17cf49feb/docs/images/bdd-feature.png)

---

# 🧪 Automação Web

## Cenários Automatizados

### 🛒 SauceDemo

- Login válido
- Login inválido
- Usuário bloqueado
- Adição de produto ao carrinho
- Checkout com sucesso
- Validação de campos obrigatórios

### 🔍 Amazon

- Pesquisa de produto
- Validação de resultados
- Validação de comportamento da busca

---

# 🌐 Testes de API

Os testes de API foram desenvolvidos utilizando **Postman** para validar endpoints REST e garantir a integridade das respostas da aplicação.

Foram utilizadas APIs públicas para simular cenários reais de testes.

---

## APIs utilizadas

### ReqRes API
Utilizada para simular operações de usuários e praticar testes de endpoints REST como:

- Listagem de usuários
- Criação de usuário
- Atualização de usuário
- Exclusão de usuário

### Books API
Utilizada para validar endpoints de consulta de livros, permitindo testar:

- Estrutura de resposta JSON
- Campos obrigatórios
- Listagem de dados

### FakeStore API
API pública de e-commerce utilizada para validar:

- Listagem de produtos
- Estrutura de resposta da API
- Tipos de dados retornados

---

## 🧪 Validações aplicadas nos testes de API

✔ Status Code das respostas HTTP  
✔ Estrutura do JSON retornado pela API  
✔ Presença de campos obrigatórios  
✔ Tipos de dados corretos nas propriedades  
✔ Tempo de resposta da API

---

# 📸 Evidências de Testes de API

### Execução da Collection no Postman

![image alt](docs/images/postman-collection-run.png.png)

---

### Exemplo de Request com Testes Automatizados

![image alt](docs/images/postman-test-example.png.png)

---

### Estrutura da Collection

![image alt](docs/images/postman-collection-structure.png.png)

---


🔁 Estratégia de Testes

Os testes foram estruturados para:

Validar regras de negócio

Cobrir cenários positivos e negativos

Servir como base para regressão

Garantir robustez evitando validações frágeis



---

## 📊 Relatórios (Allure)

### Gerar relatório


npx allure generate allure-results --clean


### Abrir relatório


npx allure open


---

# ▶️ Como Executar o Projeto

### Clonar repositório


git clone <url-do-repositorio>


### Instalar dependências


npm install


---

## Executar testes Web

### Modo interativo


npx cypress open


### Modo headless


npx cypress run


---

# 🔄 Versionamento

Fluxo adotado:

- Desenvolvimento na branch `testes`
- Validação local
- Pull Request para `main`
- Branch `main` sempre estável

---

# 📈 Próximos Passos

- Integração dos testes de API com Newman
- Integração com CI/CD
- Ampliação da suíte de regressão
- Inclusão de cenários derivados de testes exploratórios

---

# 👨‍💻 Sobre

Sou um **QA em evolução**, focado em construir uma base sólida em:

- Qualidade de Software
- Automação de Testes
- Boas práticas de mercado

Este repositório representa minha jornada prática de aprendizado e aprimoramento contínuo.