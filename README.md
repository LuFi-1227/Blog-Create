# Blog-Create
Trabalho extra de Engenharia de Software

## requisitos blog
- publicar um artigos
    somente um usuario logado pode publicar artigos

- remover artigo
    um usuario só remove seus proprios artigos

- artigo em rascunho
    antes de ser publicado um artigo pode ficar em um 
    status de rascunho, nesse caso somente o dono do 
    artigo tem acesso a ele

- lista publica de artigos
    a pagina inicial do blog lista todos os artigos 
    de todos os autores
    - deve ser paginado

- detalhe de um artigo
    - artigo publicado pode ser acessado por qualquer pessoa
    mesmo sem login
    - artigo em rascunho deve ser acessado somente pelo dono

- comentarios em um artigo
    somente usuario logado pode comentar ou apagar seu comentario
    - deve ser paginado

- login
    usar sessão

- gerenciamento de senha
    não salvar senha "limpa" no banco de dados

- redefinição de senha
    enviar email com link de redefinição
    usar gmail para envio de emails

- signup
    permitir que uma pessoa crie sua conta publicamente

##

- ambiente de desenvolvimento usando docker para tudo

- colocar no github

- usar somente php e html

## ordem
    - signup
    - criar post
    - listar posts na home
    - editar post
    - deletar post
    - ver um post
    - deixar post como rascunho
    - adicionar comentario em um post
    - remover comentario de um post
    - editar comentario em um post
    - recuperar senha
