# 📚 Sistema de Gerenciamento de Faculdade — Modelagem de Banco de Dados

Projeto de modelagem de banco de dados relacional para gerenciamento acadêmico de uma faculdade, contemplando alunos, professores, cursos, disciplinas, turmas e histórico escolar. Desenvolvido como projeto prático de estudo em modelagem de dados.

## 🎯 Objetivo

Realizar o controle centralizado de alunos, professores, cursos, disciplinas, histórico escolar e turmas, desde o levantamento de requisitos até a implementação física do banco de dados.

## 📋 Índice

1. [Regras de Negócio](docs/01-regras-negocio.md)
2. [Entidades, Atributos e Relacionamentos](docs/02-entidades-atributos-relacionamentos.md)
3. [Modelo Conceitual](docs/03-modelo-conceitual.md)
4. [Cardinalidades](docs/04-cardinalidades.md)
5. [Eliminando Relacionamentos Muitos-para-Muitos](docs/05-eliminando-relacionamentos-N-N.md)
6. [Modelo Final Completo](docs/06-modelo-final-completo.md)
7. [Modelo Lógico](docs/07-modelo-logico.md)
8. [Normalização — 1FN](docs/08-normalizacao-1FN.md)
9. [Normalização — 2FN](docs/09-normalizacao-2FN.md)
10. [Normalização — 3FN](docs/10-normalizacao-3FN.md)
11. [Dicionário de Dados](docs/11-dicionario-dados.md)
12. [Implementação e Testes](docs/12-implementacao-e-testes.md)

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


## 👤 Autor

Projeto desenvolvido por *Joelyson Aires*, com base no curso
*"Modelagem de Bancos de Dados"*,
do canal Bóson Treinamentos em Tecnologia.
