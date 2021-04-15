# Desafio Nexaas para desenvolvedor(a) em .NET C#

Ficamos felizes que você tenha chegado nesta etapa do processo seletivo para desenvolvedor(a) em .NET C#. Nosso desafio é a construção de uma API Rest, obrigatoriamente você deve implementar uma solução com .NET C#.

Crie uma API Rest que faça o gerenciamento de estoque de uma loja. As entidades devem ser: 
- Product: informações de produto (id, nome e preço de custo, por exemplo)
- Store: Informações sobre a loja (id, nome e endereço, por exemplo)
- StockItem: Deve relacionar uma loja a um produto e armazenar a quantidade de itens em estoque

![image](https://user-images.githubusercontent.com/1817569/114481805-bc0c5500-9bdb-11eb-9be3-058739c8757c.png)

As operações devem ser:
- Cadastrar, alterar, excluir e pesquisar produto (apenas por ID) 
- Cadastrar, alterar, excluir e pesquisar loja (apenas por ID) 
- Criar estoque de um produto em uma loja (relacionar loja e produto e inserir uma quantidade inicial de itens)
- Adicionar itens de um produto ao estoque
- Retirar itens de um produto do estoque

O que você deve nos entregar:
- Código fonte no Github com documentação no readme ou wiki sobre como rodar localmente a aplicação
- Utilize banco relacional (preferencialmente PostgreSQL)
- Utilize .NET CORE;
- Aplicação rodando no Azure ou qualquer outro cloud provider
- Documentação de como utilizar os endpoints
- A aplicação Server Side (API) deve ser protegida por um TOKEN
- Configurações de banco devem ficar no web.config/appsettings.json
* ASP.NET CORE > 2.0
* POO
* SOLID
* Clear Code
* Utilização correta de git (utilizar branch diferente da master para desenvolvimento)
* Não esquecer de enviar os scripts de banco 

O que vamos avaliar:
- Solução adotada, principalmente a questão de adicionar e retirar itens do estoque (imagine um cenário de concorrência)
- Cobertura de testes e a qualidade dos testes
- Qualidade de código
- Conceitos avançados de orientação a objetos 
- Estrutura do banco de dados (índices, chave estrangeiras, chaves únicas… use um banco relacional e todo seu poder)
- Verbos e status code dos endpoints (utilize os padrões HTTP)
- Como os erros são tratados
