- [x] GET /repositories
A rota deve retornar uma lista contendo todos os repositórios cadastrados.
- [x] POST repositories
A rota deve receber title, url e techs pelo corpo da requisição e retornar um objeto com as informações do repositório criado e um status 201.
- [x] PUT /repositories:id
A rota deve receber title, url e techs pelo corpo da requisição e o id do repositório que deve ser atualizado pelo parâmetro da rota. Deve alterar apenas as informações recebidas pelo corpo da requisição e retornar esse repositório atualizado.
- [x] DELETE /repositories/:id
A rota deve receber, pelo parâmetro da rota, o id do repositório que deve ser excluído e retornar um status 204 após a exclusão.
- [x] POST /repositories/:id/like
A rota deve receber, pelo parâmetro da rota, o id do repositório que deve receber o like e retornar o repositório com a quantidade de likes atualizada.