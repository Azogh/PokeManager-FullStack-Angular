# 🐉 PokeManager: Angular & Firebase CRUD System

[![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)](https://angular.io/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📝 Descrição / Description

O **PokeManager** é uma aplicação web robusta desenvolvida para a disciplina de **Programação Orientada a Objetos II (POO2)**. O sistema demonstra a implementação de um ciclo completo de **CRUD** integrado ao **Firebase**, além do consumo dinâmico da **PokéAPI** para geração e catalogação de dados.

> *A Full Stack Angular application designed to manage a Pokémon database. It features a complete CRUD workflow, Firebase authentication, and real-time data persistence, leveraging the PokéAPI for dynamic content.*

---

## ✨ Funcionalidades / Features

* **⚡ Integração com PokéAPI:** Geração aleatória de Pokémon através de requisições HTTP assíncronas.
* **💾 Persistência Real-time:** Operações de Criar, Ler, Atualizar e Excluir (CRUD) integradas ao Firebase Firestore.
* **🔐 Autenticação & Segurança:** Controle de acesso e proteção de rotas utilizando **Firebase Authentication**.
* **🎨 UI/UX com Angular Material:** Interface moderna, responsiva e padronizada.
* **🛠️ Custom Pipes:** Transformação de dados customizada para melhor legibilidade (Data Formatting).

---

## 🛠️ Tecnologias / Tech Stack

* **Framework:** Angular (v13+ ou conforme sua versão)
* **Backend as a Service:** Firebase (Auth & Firestore)
* **UI Library:** Angular Material
* **External API:** [PokéAPI](https://pokeapi.co/)

---

## 🚀 Como Executar / Setup & Installation

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/Azogh/PokeManager-FullStack-Angular.git](https://github.com/Azogh/PokeManager-FullStack-Angular.git)
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    ```

3.  **Configuração do Firebase:**
    * Crie um projeto no [Firebase Console](https://console.firebase.google.com/).
    * Adicione suas credenciais no arquivo `src/environments/environment.ts`.

4.  **Inicie o servidor de desenvolvimento:**
    ```bash
    ng serve
    ```
    Acesse em: `http://localhost:4200`

---

## 📐 Estrutura Arquitetural

O projeto segue os princípios de **Clean Code** e a estrutura modular do Angular:
* `src/app/core`: Serviços de autenticação e guards de rotas.
* `src/app/shared`: Pipes customizados e componentes reutilizáveis.
* `src/app/features`: Módulos de cadastro e listagem de Pokémon.

---

## 👨‍💻 Autor
**Andre Gustavo Ozga** *Estudante de Sistemas de Informação | Cybersecurity & Software Engineering*

---
