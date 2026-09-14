# 📚 Sistema de Gerenciamento de Faculdade — Modelagem de Banco de Dados

Projeto de modelagem de banco de dados relacional para gerenciamento acadêmico de uma faculdade, contemplando alunos, professores, cursos, disciplinas, turmas e histórico escolar. Desenvolvido como projeto prático de estudo em modelagem de dados.

## 🎯 Objetivo

Realizar o controle centralizado de alunos, professores, cursos, disciplinas, histórico escolar e turmas, desde o levantamento de requisitos até a implementação física do banco de dados.


## 🛠️ Tecnologias utilizadas

- *SGBD:* MySQL
- *Ferramenta de diagramação:* brModelo
- *Documentação:* Markdown

## 🚀 Como executar o projeto

1. Clone este repositório
2. Crie um banco de dados no MySQL (ex: db_faculdade)
3. Execute o script [sql/create_tables.sql](sql/create_tables.sql) — ele cria as 16 tabelas do modelo (na ordem correta de dependência entre chaves estrangeiras), insere dados de exemplo e executa consultas de validação

bash
mysql -u seu_usuario -p db_faculdade < sql/create_tables.sql

## 📁 Estrutura do projeto

```text
projeto-modelagem-faculdade/
│
├── README.md
├── docs/
│   ├── 01-regras-negocio.md
│   ├── 02-entidades-atributos-relacionamentos.md
│   ├── 03-modelo-conceitual.md
│   ├── 04-cardinalidades.md
│   ├── 05-eliminando-relacionamentos-N-N.md
│   ├── 06-modelo-final-completo.md
│   ├── 07-modelo-logico.md
│   ├── 08-normalizacao-1FN.md
│   ├── 09-normalizacao-2FN.md
│   ├── 10-normalizacao-3FN.md
│   ├── 11-dicionario-dados.md
│   └── 12-implementacao-e-testes.md
├── sql/
│   └── create_tables.sql
└── .gitignore
---

👤 Autor
Projeto desenvolvido por Joelyson Aires, com base no
Curso Completo de Modelagem de Dados, do canal Bóson Treinamentos em Tecnologia.


