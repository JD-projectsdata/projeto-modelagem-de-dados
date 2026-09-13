
Após o levantamento das regras de negócio, o próximo passo foi identificar
as entidades do sistema, seus atributos e como elas se relacionam entre
si — ainda sem definir cardinalidades, que são tratadas na etapa seguinte.

## Entidades e Atributos

- *Departamento*: Código, Nome
- *Curso*: Código, Nome, Departamento
- *Professor*: Código, Nome, Sobrenome, Departamento, Status
- *Disciplina*: Código, Nome, Descrição, Departamento, Carga Horária,
  Número de Alunos
- *Turma*: Código, Curso, Período, Número de Alunos, Data de Início,
  Data de Fim
- *Aluno*: RA (Matrícula), Nome, Sobrenome, Endereço (Rua, Número,
  Bairro, CEP, Cidade, Estado), Telefone, CPF, Curso
- *Histórico*: Código, RA, Disciplina, Nota, Frequência, Período de
  Realização

## Relacionamentos

- Aluno está Matriculado em Curso
- Aluno Cursa Disciplina
- Aluno Realizou Disciplina (Histórico)
- Disciplina Pertence a Curso
- Professor Ministra Disciplina
- Professor Pertence a Departamento
- Departamento é Responsável por Disciplina
- Departamento Controla Curso
- Disciplina Depende de Disciplina (pré-requisito)
