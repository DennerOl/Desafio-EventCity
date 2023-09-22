# Desafio-EventCity

Implementei neste projeto as funcionalidades necessárias para  os testes de integração.

------------------Competencias que foram avaliadas---------------

Desenvolvimento TDD de API Rest com Java e Spring Boot

Implementação de cenários de busca, inserção, deleção e atualização

Tratamento de exceções em API com respostas HTTP customizadas

--------------------Rotas e retorno dos testes aplicados------------------------

DELELE /cities/{id} deve retornar 404 Not Found quando id não existir

DELELE /cities/{id} deve retornar 204 No Content quando id for independente

DELETE /cities/{id} deve retornar 400 Bad Request quando id for dependente

POST /cities deve inserir recurso

GET /cities deve retornar recursos ordenados por nome

PUT /events deve atualizar recurso quando id existir

PUT /events deve retornar 404 Not Found quando id não existir

![EventCity](https://github.com/DennerOl/Desafio-EventCity/assets/124217386/a1da6be8-b769-4c64-af01-e2daece32993)

