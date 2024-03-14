# Projeto Eshop Microservices

Este repositório contém um projeto de microservices para uma aplicação de comércio eletrônico (e-shop). Cada microservice desempenha um papel específico na arquitetura geral da aplicação.

## Estrutura do Projeto

- **BuildingBlocks**: Módulo responsável por fornecer blocos de construção reutilizáveis para os microservices.

  - **Messaging**: Implementação de mensageria para comunicação entre os microservices.
  - **CQRS**: Implementação do padrão CQRS (Command Query Responsibility Segregation).
  - **Exceptions**: Definição de exceções personalizadas para tratamento de erros.
  - **Pagination**: Funcionalidade de paginação para listagens de recursos.

- **Services**: Microservices individuais que compõem a aplicação.

  - **Basket.API**: Serviço responsável por gerenciar o carrinho de compras dos usuários.
  - **Catalog.API**: Serviço responsável por gerenciar o catálogo de produtos da loja.
  - **Discount.Grpc**: Serviço gRPC responsável por aplicar descontos nos produtos.

- **Ordering**: Microservice para gerenciamento de pedidos.
  - **Ordering.API**: Serviço responsável por expor endpoints relacionados aos pedidos.
  - **Ordering.Application**: Lógica de aplicação relacionada aos pedidos.
  - **Ordering.Domain**: Definições de domínio relacionadas aos pedidos.
  - **Ordering.Infrastructure**: Implementação de infraestrutura para o serviço de pedidos.

## Como Utilizar

Para utilizar este projeto, siga estas etapas:

1. Clone ou faça o download deste repositório.
2. Importe cada microservice em sua IDE preferida.
3. Certifique-se de ter todas as dependências necessárias configuradas em seu ambiente de desenvolvimento.
4. Execute cada microservice individualmente ou utilize ferramentas de orquestração como Docker e Kubernetes para implantar e gerenciar os microservices.

## Contribuições

Contribuições para este projeto são bem-vindas! Se você tiver sugestões, melhorias ou correções a fazer, sinta-se à vontade para abrir uma issue ou enviar um pull request.
