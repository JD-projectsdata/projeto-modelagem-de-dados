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

<img width="214" height="172" alt="telefones_aluno" src="https://github.com/user-attachments/assets/b9498bde-c104-44ea-945e-7d352c9e5084" />



<img width="143" height="92" alt="tipo_telefone" src="https://github.com/user-attachments/assets/88386bf4-0317-4f1a-b0a8-d4fcd979b49d" />



## Resolvendo Endereço

Da mesma forma, os campos de endereço foram extraídos da tabela Aluno e
passaram a compor a entidade Endereco_Aluno. Foi criada também a
entidade Tipo_Logradouro — não estritamente obrigatória, mas
adotada para qualificar o tipo de logradouro (rua, avenida, etc.) de
forma estruturada, em vez de um texto livre.


<img width="154" height="171" alt="endereco_aluno" src="https://github.com/user-attachments/assets/f7aa9768-0197-4ec8-b2e1-4e0d6d376f34" />
<img width="212" height="109" alt="tipo_logradouro" src="https://github.com/user-attachments/assets/7de85912-d050-4de3-8a2d-2a0b04889b12" />
