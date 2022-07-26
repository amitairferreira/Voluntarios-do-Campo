
<br>

<div align="center">
<img src="https://user-images.githubusercontent.com/100969789/180617783-179be0e9-db51-450e-9aeb-e667bb9e9c0a.png" width="350px" />
</div>


> Iniciativa que visa conectar produtores da agricultura familiar e profissionais voluntários.



<p align="justify">
  <a>
     <img src="http://img.shields.io/static/v1?label=status&message=Em%20Desenvolvimento&color=pink&style?style=flat"/>
     <img src="https://img.shields.io/github/last-commit/amitairferreira/voluntarios-do-campo?color=pink"/>
     <img src="https://img.shields.io/badge/version-1.0.0-pink"/>
  </a>
</p>


## **Sumário**

* [Desafio](#desafio)
* [Proposta](#proposta)
* [Link Apresentação](#link)
* [Funcionalidades](#funcionalidades)
* [Tecnologias Utilizadas](#tecnologias)
* [Bibliotecas Aplicadas](#bibliotecas)
* [Arquitetura MVC](#arquitetura)
* [Instruções](#instruções)
* [Rotas](#rotas)
* [Manipulação das rotas](#manipulação)

---

<div id='desafio'/>

## 💻 Desafio

<p align="justify">Segundo dados do MAPA(ministério da agricultura pecuária e abastecimento) a agricultura Familiar é a principal responsável pela produção dos alimentos que são disponibilizados para o consumo da população brasileira. Toda essa produção é oriunda de pequenos sistemas agrícolas constituídos de produtores rurais, comunidades tradicionais, assentados da reforma agrária, silvicultores e aquicultores.
<p align="justify">O censo Agrícola do IBGE indica que a agricultura familiar é a base econômica de 90% dos municípios brasileiros com até 20 mil habitantes, com uma produção diversificada de grãos, proteínas animal e vegetal, frutas, verduras e legumes. 
<p align="justify">Embora evidente a importância da agricultura familiar para o pais, a falta de assistência técnica se mostra como agente contraditório para o desenvolvimento no campo, visto que o acompanhamento profissional paralelo a experiência cotidiana do produtor tornaria possível a criação de sistema agrícolas sustentáveis e lucrativos.
<p align="justify">Contudo, os orgãos públicos responsáveis por oferecer assistência técnica agrícola não atende de forma eficaz a essa população e a pricipal justificativa apontada é o reduzido tamanho do corpo técnico dessas instituições, o que impossibilita orientação individualizada aos agricultores.
<br>

---
  
<div id='proposta'/>

## 💡 Proposta  

<p align="justify">O projeto é uma API que permite a listagem de pequenos produtores da agricultura familiar, bem como listagem de profissionais da agropecuária como agrônomos, zootecnistas, veterinários e técnicos agrícolas. O cadastro é realizado de forma clara e intuitiva, permitindo que pessoas de qualquer grau de escolaridade tenha acesso de forma simples.
<p align="justify">Ao realizar o cadastro, o produtor e profissional informam dados como endereço, principais atividades desenvolvidas e áreas de atuação. O produtor poderá pesquisar o técnico por profissão e cidade, será possível ainda, troca de mensagens entre ambos, possibilitando contato direto e dessa forma reduzindo a distância entre agricultura familiar e todo o acompanhamento técnico nescessário.

---

<div id='link'/>

## 📝 Link Apresentação

- [Apresentação]()

---
<div id='funcionalidades'/>

## ⚙️ Funcionalidades

- Cadastro, login, atualização e exclusão de usuários
- Cadastro de produtores rurais da agricultura familiar
- Listar todos os produtores cadastrados
- Listar produtores por estado e/ou cidade
- Pesquisar um produtor específico por Id
- Atualizar cadastro do produtor
- Deletar cadastro do produtor
- Cadastrar profissional voluntário
- Listar todos os profissionais cadastrados
- Listar profissionais por cidade e/ou profissão
- Pesquisar um profissional específico por Id
- Atualizar cadastro do profissional
- Deletar cadastro do profissional
- Troca de mensagens entre produtor e profissional

---

<div id='tecnologias'/>

## 🛠 Tecnologias Utilizadas

Na construção deste projeto foram utilizadas as seguintes tecnologias:

<p  align="justify">
<a  href="https://www.javascript.com/"><img  alt="Java Script"  src="https://img.shields.io/badge/JavaScript-pink">
<a  href="https://git-scm.com/"><img  alt="Git version"  src="https://img.shields.io/badge/Git/GitHub-pink">
<a  href="https://nodejs.org/pt-br/"><img  alt="Node version"  src="https://img.shields.io/badge/NodeJS-pink">
<a  href="https://www.mongodb.com/cloud/atlas"><img  alt="Node version"  src="https://img.shields.io/badge/MongoDB%20Atlas-pink">
<a  href="https://www.postman.com/"><img  alt="Postman"  src="https://img.shields.io/badge/Postman-pink">
<a  href="https://code.visualstudio.com/"><img  alt="VsCode"  src="https://img.shields.io/badge/VSCode-pink">
<a  href="https://dashboard.heroku.com/apps"><img  alt="Heroku"  src="https://img.shields.io/badge/Heroku-pink">
</a>

---
  
<div id='bibliotecas'/>
  
## 🚀 Bibliotecas Aplicadas
  
Foram aplicadas as seguintes bibliotecas neste projeto:
  
<p  align="justify">
<a  href="https://expressjs.com/pt-br/"><img  alt="Express version"  src="https://img.shields.io/badge/express-4.17.1-pink">
<a  href="https://www.npmjs.com/package/nodemon"><img  alt="Nodemon version"  src="https://img.shields.io/badge/nodemon-2.0.6-pink">
<a  href="https://www.npmjs.com/package/dotenv-safe"><img  alt="Dotenv-safe version"  src="https://img.shields.io/badge/dotenv-8.2.0-pink">
<a  href="https://mongoosejs.com/"><img  alt="Mongoose version"  src="https://img.shields.io/badge/mongoose-5.10.17-pink">
<a  href="https://www.npmjs.com/package/cors"><img  alt="npm version"  src="https://img.shields.io/badge/cors-2.8.5-pink">
<a  href="https://www.npmjs.com/"><img  alt="npm version"  src="https://img.shields.io/badge/npm-6.14.6-pink">
<a  href="https://www.npmjs.com/package/bcryptjs"><img  alt="Bcrypt version"  src="https://img.shields.io/badge/bcrypt-5.0.0-pink">
<a  href="https://www.npmjs.com/package/jsonwebtoken"><img  alt="Jsonwebtoken version"  src="https://img.shields.io/badge/jsonwebtoken-8.5.1-pink"></a>

 ---
  
<div id='arquitetura'/>
  
## 📁 Arquitetura MVC

```
  
📁 voluntarios-do-campo
  |
  |- 📁 src
  |   |
  |   |- 📁 controller
  |         |- 📑 farmerController.js
  |         |- 📑 messageController.js
  |         |- 📑 professionalController.js
  |         |- 📑 userController.js
  |
  |   |- 📁 database
  |         |- 📑 mongoConfig.js
  |
  |   |- 📁 helpers
  |         |- 📑 hashPassword.js
  |
  |   |- 📁 middlewares
  |         |- 📑 auth.js
  |
  |   |- 📁  models
  |         |- 📑 farmerSchema.js
  |         |- 📑 messageSchema.js
  |         |- 📑 professionalSchema.js
  |         |- 📑 userSchema.js
  |
  |   |- 📁 routes
  |         |- 📑 farmerRoutes.js
  |         |- 📑 indexRoutes.js
  |         |- 📑 messageRoutes.js
  |         |- 📑 professionalRoutes.js
  |         |- 📑 userRoutes.js
  |
  |   |- 📑 app.js
  |
  |
  |- 📑 .env
  |- 📑 .env.example
  |- 📑 .gitignore
  |- 📑 package-lock.json
  |- 📑 package.json
  |- 📑 procfile
  |- 📑 README.md
  |- 📑 server.js
  
  ```

 ---
  
<div id='instruções'/>
  
## 📎 Instruções

Para a instalação do projeto, siga o seguinte passo a passo:
  
No terminal, clone o repositório
  
>git clone https://github.com/amitairferreira/voluntarios-do-campo.git
  
Entre na pasta do projeto
  
>cd voluntarios-do-campo

Instale as dependências
  
>npm install

Na pasta raiz do projeto renomeie .env.example para .env e adicione as variáveis. Em seguida, execute o servidor no terminal
  
>npm run dev

O servidor iniciará e exibirá a seguinte mensagem:
  
>Servidor rodando na porta: PORT
  
>Banco conectado (:

---
  
<div id='rotas'/>
  
## ⚙️ Rotas

>Local: http://localhost:8080

>Heroku: https://voluntarios-do-campo.herokuapp.com/

> Utilize o [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/download/) para testar os endpoints da API localmente.

---
  
<div id='manipulação'/>
  
## 🔃 Manipulação das rotas

| Método HTTP  | Endpoint                     | Descrição                            |
| ------------ | ---------------------------- | ------------------------------------ |
| GET          | `http://localhost:8080/`     |  Mensagem de apresentação            |

<br>
  
 ### Rotas dos usuários: 
  
| Método HTTP  | Endpoint                     | Descrição                                   |
| ------------ | ---------------------------- | --------------------------------------------| 
| POST         | `user/create`                |  Cadastra novo usuário                      |
| GET          | `user/all`                   |  Retorna todos os usuários cadastrados      |
| POST         | `user/login`                 | Realiza o login do usuário                  |
| PATCH        | `user/update/:id`            | Atualiza email e/ou senha do usuário        |
| DELETE       | `user/delete/:id`            | Exclui usuário                              |

<br>
  
### Rotas para produtoes:
  
| Método HTTP  | Endpoint                     | Descrição                                   |
| ------------ | ---------------------------- | --------------------------------------------| 
| POST         | `farmer/create`              |  Cadastra novo  produtor                    |
| GET          | `farmer/all`                 |  Retorna todos os produtores cadastrados    |
| GET          | `farmer/byStateCity`         | Pesquisa produtor por estado e/ou por cidade| 
| GET          | `farmer/byId/:id`            | Pesquisa um produtor específico             |
| PATCH        | `farmer/update/:id`          | Atualiza dados do produtor                  |
| DELETE       |  `farmer/delete/:id`         | Deleta cadastro do produtor                 |
  
<br>  

### Rotas para profissionais:
  
| Método HTTP  | Endpoint                       | Descrição                                           |
| ------------ | ----------------------------   | ----------------------------------------------------| 
| POST         | `professional/create`          | Cadastra novo profissional                          |
| GET          | `professional/all`             | Retorna todos os profissionais cadastrados          |
| GET          | `professional/byCityProfession`| Pesquisa profissional por cidade e/ou por profissão | 
| GET          | `professional/byId/:id`        | Pesquisa um profissional específico                 |
| PATCH        | `professional/update/:id`      | Atualiza dados do profissional                      |
| DELETE       |  `professional/delete/:id`     | Deleta cadastro do profissional                     |
