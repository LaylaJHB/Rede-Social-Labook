# Rede Social Labook

---

##  🕵Sobre

Esse projeto apresenta o back-end de uma rede social para o bootcamp de formação em Web Full-Stack da Labenu




---
##  🔠Conteúdos

<!--ts-->
   * [Sobre](#sobre)
   * [Autor](#autor)
   * [Status](#status-do-projeto)
   * [Objetivo do Projeto](#objetivo-do-projeto)
   * [Requisitos de Funcionalidade](#requisitos-de-funcionalidade)
   * [Concepção do Projeto](#concepção-do-projeto)
   * [Link para Acessar](#link-para-acessar)
   * [Rodando o Projeto](#rodando-o-projeto)
   * [Sobre a Licença](#sobre-a-licença)
<!--te-->


---
## 🧭Status do Projeto

 - ⏳ Feito

---

##  🎯Objetivo do Projeto

Este é um projeto de Back-end cujo principal objetivo é desenvolver as principais funcionalidades de uma rede social em Typescript.

## ☑Requisitos de Funcionalidade


- [✅] Cadastrar novo usuário na rede social com senha criptografada
- [✅] Puxar os dados de todos os usuários cadastrados na rede
- [✅] Criar nova postagem na rede social
- [✅] Buscar uma postagem por id
- [✅] Ver todo o feed da rede social
- [✅] Fazer amizade
- [✅] Desfazer amizade

---

## 💡Concepção do Projeto

Para esse projeto são modelados três entidades : **Usuário (USER), Amigo (FRIEND)** e **Postagem (TASK)**.  Cada uma com as seguintes caracteristicas:

→ User (labook_users) -  id, name, email, password;

→ Friend (labook_friends) - id, id_user, id_friend ;

→ Postagem (labook_tasks) - id, photo, description, type, created_at, author_id.

![image](https://github.com/LaylaJHB/Rede-Social-Labook/assets/99913142/52624218-a5d5-4ed4-907f-14131883b054)





---

## ☑️Próximos passos

- Clean Code - alterar o nome _Task_ para _Post_

---

## 🔗Link para Acessar

- **Link da Documentação no Postman:** 
    - https://documenter.getpostman.com/view/22349688/2s93CLtZd3

- **Link do Deploy no Render:** 
   
     - Pegar todos os usuários cadastrados: https://labook-rede-social.onrender.com/user/getAll
     - Criar/Cadastrar novo usuário: https://labook-rede-social.onrender.com/user/create
     - Criar nova Postagem: https://labook-rede-social.onrender.com/task/create

---


## 🛰Rodando o Projeto

Para Rodar o projeto, siga as seguintes etapas :

- Clone esse repositório
- Rode o comando `npm install` para instalar as dependências do projeto
- Adicione os dados de conexão do seu Banco de Dados em um arquivo `.env` com as seguintes variáveis:

    * `DB_HOST = `
    * `DB_USER = `
    * `DB_PASS = `
    * `DB_NAME = `
    * `PORT = 3306`

- Rode o comando `npm run migrations` para criar as tabelas do projeto em seu banco de Dados
- Rode o comando `npm start` no terminal para iniciar o projeto


---

##  👩Autor 

- Layla Janaína Hissa Borges

---

## 📝Sobre a Licença

Este projeto esta sobe a licença [MIT](./LICENSE).
git
