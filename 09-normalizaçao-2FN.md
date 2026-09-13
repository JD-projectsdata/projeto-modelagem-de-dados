## Normalização — Segunda Forma Normal (2FN)

A Segunda Forma Normal exige que todo atributo não-chave dependa
integralmente da chave primária, eliminando dependências parciais.

## Resolvendo Telefone

Os campos de telefone criados na 1FN foram extraídos da tabela Aluno e
passaram a compor uma entidade própria, Telefones_Aluno. Para
qualificar cada registro, foi criada também a entidade Tipo_Telefone,
que armazena os tipos possíveis de telefone — residencial, celular, ou
qualquer outro que venha a existir — sem limitar o modelo a categorias
fixas.

![Tabela Telefones_Aluno](tabela-Telefones_Aluno-2fn.png)

![Tabela Tipo_Telefone](tabela-Tipo_Telefone-2fn.png)


## Resolvendo Endereço

Da mesma forma, os campos de endereço foram extraídos da tabela Aluno e
passaram a compor a entidade Endereco_Aluno. Foi criada também a
entidade Tipo_Logradouro — não estritamente obrigatória, mas
adotada para qualificar o tipo de logradouro (rua, avenida, etc.) de
forma estruturada, em vez de um texto livre.

![Tabela Endereco_Aluno](tabela-endereco_aluno-2fn.png)
