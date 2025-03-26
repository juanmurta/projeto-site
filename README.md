# FakePinterest - Aplicação Web  

## Descrição  
Este projeto é uma aplicação web inspirada no Pinterest, desenvolvida com **Flask**. Permite que os usuários criem contas, façam login, façam upload de imagens e visualizem um feed com as imagens postadas por outros usuários.  

## Funcionalidades Principais  
- **Página Inicial (`/`)**:  
  - Permite que usuários façam login na plataforma.  
- **Criação de Conta (`/criarconta`)**:  
  - Permite que novos usuários se cadastrem na plataforma.  
  - As senhas são armazenadas de forma segura com hash.  
- **Perfil do Usuário (`/perfil/<id_usuario>`)**:  
  - Permite que os usuários visualizem seus próprios perfis e adicionem fotos.  
  - Outros usuários podem visualizar perfis, mas sem acesso ao upload de imagens.  
- **Feed de Imagens (`/feed`)**:  
  - Exibe imagens postadas por todos os usuários em ordem cronológica.  
- **Logout (`/logout`)**:  
  - Permite que o usuário saia da plataforma.  

## Como Contribuir  
1. Faça um fork do repositório.  
2. Crie um branch para suas alterações.  
3. Commit suas mudanças.  
4. Faça push para o branch.  
5. Abra um Pull Request.  

Para mais detalhes sobre como contribuir, veja a [documentação oficial do GitHub sobre Pull Requests](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests).  
