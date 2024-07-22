# teste-pratico
Projeto criado para avaliação técnica.

Este projeto é um sistema de controle de compras desenvolvido em Java com Spring Boot. Ele permite gerenciar compras, identificar a maior compra do ano, listar clientes fiéis e recomendar produtos.

Funcionalidades
Listar Compras

Java Versão 17
Spring Boot

Endpoint: GET /compras
Descrição: Retorna uma lista de todas as compras registradas.
Maior Compra do Ano

Endpoint: GET /compras/maior-compra/{ano}
Descrição: Retorna a maior compra registrada no ano especificado.
Parâmetro: ano (int) - O ano para o qual deseja consultar a maior compra.
Listar Clientes Fiéis

Endpoint: GET /compras/clientes-fieis
Descrição: Retorna uma lista de clientes fiéis, aqueles que mais compraram.
Recomendação de Produto

Endpoint: GET /compras/recomendacao/{cpf}/{tipo}
Descrição: Retorna uma recomendação de produto com base no CPF do cliente e no tipo de produto.
Parâmetros:
cpf (String) - O CPF do cliente.
tipo (String) - O tipo de produto para recomendação.

Rodando o projeto.
Abra o arquivo na IDE Spring Tool Suite4.
Inicie o projeto Run As Spring Boot App.
Utilizando o Postman na porta http 8080.
Realize testes com method GET para consultas nos Mocks e obter os retornos das informações solicitadas.
