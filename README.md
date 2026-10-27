<pre>
╔═════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║                                       TESTES DE API REST COM POSTMAN                                    ║
╚═════════════════════════════════════════════════════════════════════════════════════════════════════════╝
</pre>
Coleção de requisições para praticar a validação da API do Catálogo de Livros durante os estudos de Quality Assurance (QA).

## SOBRE O PROJETO

O repositório reúne uma coleção do Postman e um arquivo de ambiente para organizar requisições, configurar variáveis e verificar as respostas da API.

## OBJETIVOS

- Organizar e executar requisições HTTP.
- Configurar URL e variáveis de ambiente.
- Validar códigos de status, estrutura JSON e dados retornados.
- Praticar verificações para operações de consulta e manipulação de dados.

## TECNOLOGIAS E FERRAMENTAS

- Postman
- API REST
- JSON

## PRÉ-REQUISITOS

- Postman instalado.
- API do Catálogo de Livros iniciada localmente e acessível.
- Valores de ambiente e credenciais configurados conforme os requisitos da API.

## COMO EXECUTAR

1. Importe o arquivo `Catálogo de Livros.postman_collection.json` no Postman.
2. Importe o arquivo `Variáveis.postman_environment.json`.
3. Selecione o ambiente importado e configure a variável `URL` para `http://localhost:3000/api/`, caso esse seja o endereço local da API.
4. Configure localmente os valores de autenticação exigidos pela API. Não salve tokens reais ou segredos em arquivos versionados.
5. Execute as requisições individualmente ou pela coleção.
6. Confira o status HTTP e o corpo de cada resposta.

## ESTRUTURA DO PROJETO

```text
atividade-API-Ebac/
├── Catálogo de Livros.postman_collection.json
├── Variáveis.postman_environment.json
└── README.md
```

## CENÁRIOS DE TESTE

A coleção contempla operações de consulta e manipulação de dados por meio de requisições HTTP. Em cada cenário, confira se o status retornado e os dados do JSON correspondem ao resultado esperado.

Nos testes de criação, atualização e exclusão, verifique também o estado final do recurso quando a API oferecer uma consulta apropriada.

## BOAS PRÁTICAS

- Manter a coleção separada do ambiente.
- Reutilizar variáveis para reduzir configurações repetidas.
- Não versionar credenciais, tokens ou segredos.
- Validar propriedades e valores JSON esperados, além de verificações genéricas de texto.
- Restaurar os dados de teste quando os cenários alterarem recursos persistentes.

## APRENDIZADOS

A atividade permite praticar testes de API REST com Postman, organização de coleções, variáveis de ambiente, autenticação e validação de respostas.

## CONSIDERAÇÕES FINAIS

A API precisa estar em execução e acessível no endereço configurado. Os cenários podem depender de dados existentes; ajuste a URL e os valores de ambiente conforme a instalação utilizada.
<pre>
╔═════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║       Atividade desenvolvida durante a formação profissionalizante em Quality Assurance (QA) pela       ║
║                     EBAC — Escola Britânica de Artes Criativas e Tecnologia                             ║
╚═════════════════════════════════════════════════════════════════════════════════════════════════════════╝
</pre>
