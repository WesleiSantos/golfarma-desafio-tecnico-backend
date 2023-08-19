# Desafio backend Golfarma
Primeiramente, obrigado por querer fazer parte da empresa Golfarma. Os detalhes do teste estão descritos abaixo:

## Antes de começar:
- Crie um repositório no github desafio-tecnico-golfarma-SEU_NOME;
- Faça seus commits no seu repositório;
- Envie o link do seu repositório em resposta ao email que lhe encaminhou o teste;
- Dê uma olhada nos Materiais úteis.
- Fique à vontade para perguntar qualquer dúvida;
- Boa sorte!

## Requisitos e diferenciais:
- Sua solução deve ser implementada usando o framework Laravel;
- Utilização de docker para configuração de ambiente será um diferencial;
- Teste unitário ou integração serão um diferencial;

## Desafio - Sistema de Gerenciamento de Pedidos
- Crie uma estrutura de dados simples para representar um pedido. Cada pedido deve ter campos como "ID do Pedido", "Cliente", "Total" e "Status".
- Implemente as seguintes rotas para realizar operações CRUD:
  - Criar Pedido (Create): Uma rota que permita criar um novo pedido. A rota deve aceitar informações como "Cliente", "Total" e "Status" como parâmetros de entrada.
  - Listar Pedidos (Read): Uma rota que liste todos os pedidos existentes. Ao acessar essa rota, a API deve retornar uma lista com as informações básicas de cada pedido.
  - Detalhes do Pedido (Read): Uma rota que exiba os detalhes de um pedido específico com base no ID do pedido.
  - Atualizar Pedido (Update): Uma rota que permita atualizar as informações de um pedido existente. A rota deve aceitar o ID do pedido como parâmetro de entrada e permitir a atualização de campos como "Cliente", "Total" e "Status".
  - Deletar Pedido (Delete): Uma rota que permita excluir um pedido com base no ID do pedido.
- A API deve ser capaz de lidar com requisições HTTP para as operações CRUD (Create, Read, Update, Delete) dos pedidos.
- Os pedidos podem ser armazenadas em memória ou em um banco de dados simples (MySQL, por exemplo).
- Este serviço deve ser RESTFul.
- Teste a API utilizando ferramentas como o Postman ou Insomnia para garantir que todas as funcionalidades estejam funcionando corretamente.
- Documente as rotas, os parâmetros esperados e os formatos de resposta no seu arquivo README.md.

  ## Avaliação
  - Funcionalidade Completa
  - Documentação
  - Código limpo e organizado (nomenclatura, etc)
  - Manutenibilidade do Código
  - Tratamento de erros
  - Histórico de commits do git

