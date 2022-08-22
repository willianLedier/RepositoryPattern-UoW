## Repository Pattern

> Faz a mediação entre o domínio e as camadas de mapeamento de dados usando uma interface semelhante a uma coleção para acessar objetos de domínio.
*(Martin Fowler)*

Basicamente é um objeto que faz o isolamento das entidades do domínio de seu código que acessa dados.

Prós
- Um único ponto de acesso à dados.
- Encapsulamento da lógica de acesso à dados.
- SPOF (Ponto único de falha).
- Testabilidade com mock.
- Acesso a diversas fontes de dados(api, ADO, Dapper, Entity e etc).

Contras
- Maior complexidade.

------------

## UoW(Unit of Work)
> 
Mantém uma lista de objetos de negócios afetados por uma transação e coordena a escrita a partir de alterações e a resolução de problemas de concorrência.
*(Martin Fowler)*

Uma única transação que pode envolver múltiplas operações(insert/update/delete)
