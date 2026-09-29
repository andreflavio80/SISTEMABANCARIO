# 🏦 Sistema Bancário - INF101

## 📚 Informações do Projeto

**Aluno:** Andre Flavio Corcini de Abreu
**Matrícula:** 27880
**Disciplina:** INF101 - Programação de Computadores I
**Instituição:** Centro Universitário de Viçosa – UNIVIÇOSA
**Etapa:** 1
**Linguagem:** C++

---

## 📌 Sobre o Projeto

Este projeto consiste na implementação da **Etapa 1 de um Sistema de Registro e Gestão de Contas Bancárias**, desenvolvido em C++.

O objetivo é aplicar os fundamentos da programação, utilizando variáveis, estruturas de controle, `switch`, `do while`, condicionais e arrays para permitir o cadastro e gerenciamento de até **5 contas bancárias**.

---

## ⚙️ Funcionalidades

O sistema possui um menu com as seguintes opções:

1. **Cadastrar conta**
2. **Consultar conta**
3. **Verificar saldo**
4. **Alterar tipo da conta**
5. **Ativar/Desativar conta**
6. **Sair**

---

## 🏦 Dados da Conta

Cada conta possui os seguintes dados:

* **Número da conta**
* **Nome do titular**
* **CPF**
* **Tipo da conta**

  * 1 - Corrente
  * 2 - Poupança
* **Saldo**
* **Status da conta**

  * Ativa
  * Inativa

---

## 🔒 Validações

O programa realiza algumas validações básicas:

* O número da conta deve ser maior que zero.
* O saldo inicial não pode ser negativo.
* O tipo da conta deve ser `1` ou `2`.
* Operações que dependem de uma conta ativa verificam o status da conta.
* O sistema permite cadastrar no máximo **5 contas**.

---

## 💻 Tecnologias Utilizadas

* C++
* `iostream`
* `string`
* Estruturas `if/else`
* Estrutura `switch`
* Estrutura `do while`
* Estrutura `for`
* Arrays

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone URL_DO_SEU_REPOSITORIO
```

### 2. Acesse a pasta do projeto

```bash
cd sistema-bancario
```

### 3. Compile o programa

Utilizando o compilador g++:

```bash
g++ main.cpp -o banco
```

### 4. Execute

No Windows:

```bash
banco.exe
```

No Linux/Mac:

```bash
./banco
```

---

## 📋 Exemplo do Menu

```text
***************************************
**       BANCO INF101 - ABREU        **
***************************************
1 - Cadastrar conta
2 - Consultar conta
3 - Verificar saldo
4 - Alterar tipo da conta
5 - Ativar/Desativar conta
6 - Sair

Escolha uma opcao:
```

---

## 🎯 Objetivo da Etapa

A primeira etapa tem como objetivo consolidar os fundamentos da linguagem C++, preparando o sistema para sua evolução nas próximas etapas do projeto.

Nesta etapa, o sistema trabalha com o cadastro e gerenciamento das contas bancárias e utiliza arrays para possibilitar o armazenamento de até cinco contas.

---

## 👨‍💻 Autor

**Andre Flavio Corcini de Abreu**
**Matrícula: 27880**

---

## 📅 Entrega

**Data:** 30/09/2026

**Disciplina:** INF101 - Programação de Computadores I
