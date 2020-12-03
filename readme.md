# Validação de CPF e CNPJ

- Este pacote não faz a verificação de autenticidade do documento informado.
- Apenas verifica se o mesmo condiz com os padrões brasileiros.

```shell
    npm i validating-br-documents
```

```js
    import {validateCNPJ, validateCPF} from 'validating-br-documents';
```

- validateCNPJ(): Essa função validará o CNPJ;
- validateCPF(): Essa função validara o CPF;