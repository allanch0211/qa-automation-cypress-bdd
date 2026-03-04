# 🧪 Projeto de Automação de Testes - QA em Evolução

Este repositório contém meus estudos e práticas em **Automação de Testes utilizando Cypress**, com foco em qualidade de software, boas práticas e organização profissional de projeto.

O objetivo é consolidar conhecimentos em:

- Testes Funcionais  
- Testes Regressivos  
- BDD  
- Automação Web  

E evoluir progressivamente para **Testes de API**.

---

## 🚀 Tecnologias Utilizadas

- Cypress  
- Cucumber (BDD) – @badeball/cypress-cucumber-preprocessor  
- Page Object Model (POM)  
- Custom Commands  
- Allure Reports  
- JavaScript  
- Git & GitHub  

---

## 🧠 Conceitos Aplicados

- ✔ Testes Funcionais  
- ✔ Testes Negativos  
- ✔ Fluxos End-to-End (E2E)  
- ✔ Estrutura baseada em Page Object  
- ✔ Organização por Features (BDD)  
- ✔ Suíte reutilizável para Regressão  
- ✔ Versionamento com Git Flow (branch `testes` → `main`)  

---

## 📂 Estrutura do Projeto


cypress/
┣ e2e/
┃ ┗ features/
┃ ┣ SauceDemo/
┃ ┗ Amazon/
┣ support/
┃ ┣ pages/
┃ ┣ step_definitions/
┃ ┗ commands/
┣ fixtures/


---

# 📸 Evidências de Execução

## ✅ Execução dos Testes (Cypress)

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

## 🔹 Organização Interna

### Features
Arquivos `.feature` escritos em Gherkin, representando cenários de negócio.

### Step Definitions
Implementação dos passos descritos nos cenários BDD.

### Page Object
Separação de responsabilidades para manter organização, legibilidade e reutilização de código.

---

## 🧪 Cenários Automatizados

### 🛒 SauceDemo

- Login válido  
- Login inválido  
- Usuário bloqueado  
- Adição de produto ao carrinho  
- Checkout com sucesso  
- Tentativa de checkout sem preenchimento de campos obrigatórios  

### 🔍 Amazon

- Pesquisa de produto  
- Validação de exibição de resultados  
- Validação de comportamento da busca  

---

## 🔁 Estratégia de Testes

Os testes foram estruturados para:

- Validar regras de negócio (Teste Funcional)  
- Cobrir cenários positivos e negativos  
- Servir como base para regressão após alterações no sistema  
- Garantir robustez evitando validações frágeis (ex: dependência de estoque ou nomes fixos)  

---

## 📊 Relatórios (Allure)

### Gerar relatório:


npx allure generate allure-results --clean


### Abrir relatório:


npx allure open


---

## ▶️ Como Executar o Projeto

### Clonar o repositório:


git clone <url-do-repositorio>


### Instalar dependências:


npm install


### Executar testes

#### 🔹 Modo interativo:


npx cypress open


#### 🔹 Modo headless:


npx cypress run


---

## 🔄 Versionamento

Fluxo adotado:

- Desenvolvimento realizado na branch `testes`  
- Validação local  
- Pull Request para `main`  
- Branch `main` sempre estável  

---

## 📈 Próximos Passos

- Implementação de Testes de API  
- Ampliação da suíte de regressão  
- Inclusão de cenários exploratórios derivados de testes manuais  
- Integração futura com CI/CD  

---

## 👨‍💻 Sobre

Sou um QA em evolução, focado em construir uma base sólida em qualidade de software, automação e boas práticas de mercado.

Este repositório representa minha jornada prática de aprendizado e aprimoramento contínuo.
