
# Implementação e Testes

## Criação das Tabelas

Com o modelo lógico normalizado e o dicionário de dados documentado, a
etapa final da modelagem foi a implementação física do banco de dados,
traduzindo cada entidade em uma tabela SQL, com os tipos de dados,
chaves primárias, chaves estrangeiras e demais restrições definidos ao
longo do processo.

## Testes

Para validar que o banco criado reflete corretamente o modelo —
relacionamentos, restrições e integridade referencial — foram realizados
testes de inserção, consulta e atualização de dados.

## Script Completo

Todo o processo — criação das 16 tabelas (na ordem correta de
dependência entre chaves estrangeiras), inserção de dados de exemplo,
consultas de validação e testes de restrição — está reunido em um único
script:

[create_tables.sql](https://github.com/user-attachments/files/32214776/create_tables.sql)
