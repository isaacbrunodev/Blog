# Criando um Blog seguindo a documentação oficial do rails 7.0
# README
![GIF Blog Rails](GIF-RC.gif.gif)
![GIG Blog Rails](GIF-2.gif.gif)



# Blog em Rails - Exemplo de aplicação rails usando os princípios básicos do MVC (Model, View, Controller), CRUD e utilizando  do design RESTful.

Este é um projeto de blog desenvolvido em Ruby on Rails, seguindo a arquitetura Modelo-Visão-Controlador (MVC). O aplicativo permite a criação, leitura, atualização e exclusão (CRUD) de artigos. Os artigos são armazenados em um banco de dados, e a autenticação de usuários é necessária para editar os artigos.

## Instalação

1. Clone este repositório.
2. Execute `bundle install` para instalar as dependências.
3. Configure as informações do banco de dados em `config/database.yml`.
4. Execute as migrações com `rake db:migrate`.
5. Inicie o servidor com `rails server`.

Para acessar a interface de administração, crie uma conta de usuário e faça login.

## Funcionalidades

- **Criação**: Crie novos artigos com título e conteúdo.
- **Leitura**: Visualize a lista de artigos existentes.
- **Atualização**: Edite ou atualize artigos previamente criados.
- **Exclusão**: Remova artigos do blog.
- **Comentários**: Adcione e remova comentários dos artigos.
- **Autenticação**: Somente usuários autenticados podem editar artigos.

Este aplicativo é um exemplo simples que demonstra o uso do Rails para construir um aplicativo web completo seguindo a arquitetura MVC e a implementação das operações CRUD.



