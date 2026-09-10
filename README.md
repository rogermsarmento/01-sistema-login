# 🔐 Sistema de Login

Projeto desenvolvido na disciplina de **Programação Orientada a Objetos (POO)**.

O sistema implementa uma interface gráfica de autenticação utilizando **Java Swing**. Após a autenticação, o usuário é direcionado para uma tela de seleção dos programas desenvolvidos pela equipe.

## 🎯 Objetivo

Desenvolver um sistema simples de login que permita:

* autenticar o usuário;
* acessar a tela de seleção;
* selecionar um dos programas disponíveis;
* retornar da tela de seleção para a tela de login.

## 🔑 Autenticação

Nesta versão, a autenticação utiliza credenciais fixas para fins didáticos:

* **Usuário:** `root`
* **Senha:** `toor`

A validação é realizada utilizando uma estrutura condicional `if`.

## 🖥️ Telas

O sistema possui inicialmente duas telas:

### Tela de Login

Responsável por receber o usuário e a senha e realizar a autenticação.

### Tela de Seleção

Apresentada após uma autenticação válida. Permite selecionar:

* Agenda de Contatos;
* Projeto Livre;
* Voltar para a Tela de Login.

A integração com a **Agenda de Contatos** e o **Projeto Livre** será realizada posteriormente.

## 🛠️ Tecnologias

* Java
* Java Swing
* Apache NetBeans
* Git
* GitHub

## 🌿 Desenvolvimento colaborativo

O desenvolvimento utiliza branches específicas para cada funcionalidade:

```text
main
│
├── feature/tela-login
│
└── feature/tela-selecao
```

As funcionalidades desenvolvidas nas branches deverão ser integradas à `main` por meio de **Pull Requests**.

## 📂 Estrutura básica

```text
sistema-login/
│
├── README.md
├── LICENSE
├── .gitignore
├── src/
├── resources/
├── docs/
└── support/
```

## 👥 Equipe

Projeto desenvolvido pela equipe **[NOME DA STARTUP]**.

### Integrantes

* [Nome do integrante 1]
* [Nome do integrante 2]
* [Nome do integrante 3]
* [Nome do integrante 4]

## 📚 Disciplina

**Programação Orientada a Objetos — POO**
**Instituto Federal de Educação, Ciência e Tecnologia do Ceará — IFCE**
**2026.2**
