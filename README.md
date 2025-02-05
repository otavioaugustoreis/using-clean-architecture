# Using Clean Architecture

Este repositório contém um projeto baseado na **Clean Architecture**, seguindo uma estrutura modular e bem definida para garantir a separação de responsabilidades e facilitar a manutenção do código.

---

## 📌 O que é Clean Architecture?

A **Clean Architecture** é uma abordagem arquitetural proposta por **Robert C. Martin (Uncle Bob)**, cujo objetivo é criar sistemas **independentes de frameworks, bancos de dados, interfaces de usuário ou qualquer outra dependência externa**. Isso permite que o código seja mais **testável, escalável e de fácil manutenção**.

A arquitetura é dividida em camadas concêntricas, organizadas conforme a imagem abaixo:

![image](https://github.com/user-attachments/assets/dea61eb3-2cb5-4f9a-8c61-008bc46a2466)


Cada camada tem um papel específico e não deve depender diretamente de camadas externas, garantindo a **inversão de dependências**.

---

## 🏗️ Estrutura do Projeto

O projeto segue a estrutura recomendada para Clean Architecture:

- **Class.Application:** Contém a lógica de aplicação e os **casos de uso**.
- **Clean.CrossCutting:** Contém **serviços compartilhados** e classes auxiliares.
- **Clean.Domain:** Responsável pelas **entidades e regras de negócio**.
- **Clean.Infrastructure:** Implementação de **bancos de dados e serviços externos**.

---
