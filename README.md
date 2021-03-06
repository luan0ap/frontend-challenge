# Pré-requisitos

Não é permitido o uso de nenhuma biblioteca ou framework externo. Tudo será feito com [Vanilla.js](http://vanilla-js.com/).

Não utilize nenhuma biblioteca de CSS externa, mas você pode utilizar qualquer metodologia de arquitetura de código.

Se preferir, o uso de Sass é liberado, contanto que seu uso seja justificável.

O uso de ferramentas de teste é liberado.

O objetivo desse teste é avaliar:
- organização;
- semântica;
- uso e abuso das features das linguagens (HTML, CSS e JS);
- uso de patterns;
- performance do código;
- testes de JavaScript.

# Teste

Você precisará criar um servidor, em Node.JS, pra servir o `fields.json`, que está na raiz do projeto, como uma API.

O formulário a ser renderizado é o de pedidos, da forma que é exibido [aqui](https://www.getninjas.com.br/moda-e-beleza/cabeleireiros). Através do `fields.json` você precisará montar os campos na view.

# Informações adicionais

- É necessário exibir a mensagem "este campo é requerido" para os marcados como `required: true`;
- Campos do tipo `enumerable` são `select`;
- O formulário não precisa fazer `POST`;
- Temos uma cultura de testes unitários e de integração. Uma dessas formas, pelo menos, é essencial pra esse teste;
- Se quiser, faça uma rota no Node.js pra exibir o formulário num HTML.
