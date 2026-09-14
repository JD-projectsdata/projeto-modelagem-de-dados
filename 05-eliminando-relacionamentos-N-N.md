
# Eliminando Relacionamentos Muitos-para-Muitos

Ao calcular as cardinalidades, alguns relacionamentos ficaram definidos
como muitos-para-muitos (N:N) — por exemplo, entre Curso e Disciplina,
entre Professor e Disciplina, e entre Aluno e Disciplina. Bancos de dados
relacionais não implementam esse tipo de relacionamento diretamente,
então cada um foi resolvido através da criação de uma entidade
associativa, que armazena as chaves das duas entidades originais.

<img width="1110" height="635" alt="eliminando-relacionamentos-N-N" src="https://github.com/user-attachments/assets/c0bea1dc-36a1-477e-b711-e957bf6874ea" />


As entidades associativas criadas foram:

- *Curso_Disciplina*: resolve o relacionamento entre Curso e Disciplina
- *Disc_Hist*: resolve o relacionamento entre Disciplina e Histórico
- *Prof_Disciplina*: resolve o relacionamento entre Professor e Disciplina
- *Aluno_Disc*: resolve o relacionamento entre Aluno e Disciplina
