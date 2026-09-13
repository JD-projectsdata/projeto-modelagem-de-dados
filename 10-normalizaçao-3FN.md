## Normalização — Terceira Forma Normal (3FN)

A Terceira Forma Normal exige que não existam dependências transitivas —
ou seja, nenhum atributo não-chave pode depender de outro atributo
não-chave; todos devem depender diretamente da chave primária.

## Resultado

Após as decomposições realizadas na 1FN e na 2FN, nenhuma tabela do
modelo apresentou dependência transitiva. Todos os atributos não-chave
passaram a depender diretamente de suas respectivas chaves primárias,
de forma que o modelo já atendia a 3FN sem necessidade de ajustes
adicionais.


## Modelo Lógico Normalizado

Abaixo, o modelo lógico completo, já refletindo todas as decomposições
aplicadas nas etapas de normalização.


![1789259264225](image/10-normalizaçao-3FN/1789259264225.png)
