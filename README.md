# 🍕 Pizzas Quadradas (Modelagem de Banco de Dados)

Este repositório contém o mapeamento, a documentação de requisitos e os scripts de criação de tabelas para o ecossistema de banco de dados relacional de uma pizzaria especializada em pizzas quadradas.

---

## 🎯 Objetivo

O propósito deste projeto é estruturar a arquitetura de dados necessária para gerenciar o fluxo de clientes, pedidos e produtos (pizzas), garantindo a integridade dos dados e o relacionamento correto entre as entidades através de chaves primárias e estrangeiras.

---

## 📂 Estrutura do Repositório

O projeto combina a documentação formal dos dados com os scripts de implementação prática:

### 📄 Especificação de Requisitos de Software (ERS)
Arquivos que detalham as regras de negócio, tipos de dados e restrições de cada tabela:
* `ers_table_cliente.docx` — Documentação da entidade Cliente.
* `ers_table_pedido.docx` — Documentação do fluxo de Pedidos.
* `ers_table_pizza.docx` — Documentação do catálogo de Pizzas.
* `ers_table_contem_pizzas_do_pedido.docx` — Detalhamento da relação N:N entre Pedidos e Pizzas.

### 💾 Scripts de Criação (DDL)
Arquivos `.sql` prontos para execução em um Sistema Gerenciador de Banco de Dados (SGBD):
* `create_table_cliente.sql` — Estrutura para armazenamento de dados dos clientes.
* `create_table_pedido.sql` — Registro das vendas e cabeçalhos dos pedidos.
* `create_table_pizza.sql` — Cadastro de sabores, tamanhos e preços.
* `create_table_contem_pizzas_do_pedido.sql` — Tabela associativa que vincula os itens (pizzas) a cada pedido realizado.

---

## 🛠️ Tecnologias e Conceitos

* **Linguagem:** SQL (Structured Query Language)
* **Modelagem:** Entidade-Relacionamento (MER / DER)
* **Conceitos:** Chaves Primárias (PK), Chaves Estrangeiras (FK), Restrições (Constraints) e Relacionamentos Muitos para Muitos (N:M).

---
