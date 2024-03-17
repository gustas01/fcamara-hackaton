# Orange Portfólio - Back End

![Static Badge](https://img.shields.io/badge/release%20date-february-orange)
![Static Badge](https://img.shields.io/badge/squad%204-orange)
![Static Badge](https://img.shields.io/badge/orange%20juice-orange)
![Static Badge](https://img.shields.io/badge/fcamara-orange)

<h1 align="center">
   <a href="https://orange-portfolio-swagger.onrender.com/api"><img alt="Banner orange portfolio" title="Quiz sobre Baleias" src="https://github.com/Squad-4-Hackathon-FCamara/Back-End/assets/50846424/91e76f8f-1216-4a92-a51c-67fab77dd134"/></a>
</h1>

---

## 💻 Sobre
Backend do Orange Portfolio, um MVP desenvolvido pelo Squad 4 da 5ª edição do Programa de Formação da [Orange Juice](https://tech.orangejuice.com.br/orangejuice) em parceria com a [FCamara](https://fcamara.com/), desempenha um papel crucial ao fornecer os serviços e funcionalidades necessários para suportar a operação e a interação dos usuários na plataforma, sendo ele a base que sustenta toda a experiência do usuário, garantindo um funcionamento suave e eficaz da aplicação.

---

## 🛠️ Tecnologias utilizadas
<a href="https://nestjs.com/"><img alt="NESTJS" src="https://img.shields.io/badge/nestjs-ff5522?style=for-the-badge&logo=nestjs&logoColor=white"></a>
<a href="https://www.typescriptlang.org/"><img alt="TYPESCRIPT" src="https://img.shields.io/badge/typescript-ff5522?style=for-the-badge&logo=typescript&logoColor=white"></a>
<a href="https://typeorm.io/"><img alt="TYPEORM" src="https://img.shields.io/badge/typeorm-ff5522?style=for-the-badge&logo=type-orm&logoColor=white"></a>
<a href="https://www.postgresql.org/"><img alt="POSTGRE" src="https://img.shields.io/badge/postgresql-ff5522?style=for-the-badge&logo=postgresql&logoColor=white"></a>
<a href="https://swagger.io/"><img alt="SWAGGER" src="https://img.shields.io/badge/swagger-ff5522?style=for-the-badge&logo=swagger&logoColor=white"></a>

---

### ⚙️ Funcionalidades

- [x] Cadastro de usuário
- [x] Login com o Google
- [x] Login com email e senha
- [x] Cadastro de Projetos
- [x] Edição de projetos
- [x] Exclusão de projetos
- [x] Descoberta de novos projetos
- [x] Filtragem projetos por categorias

## 👨‍💻 Como executar localmente
1º passo - Depois de clonar o projeto, renomeie o arquivo chamado `.env.example` para apenas `.env`, e o preencha com as informações que se pede:
```bash
# A porta onde o backend estará onvindo as requisições.
SERVER_PORT=
# A url de conexão com o seu banco de dados.
DB_URL=

# O tempo de expiração do token usado no login dos usuários. Ex: 7d, 1h, 10s
JWT_EXPIRATION_DATE=

# A string secreta que será usada para gerar os tokens
JWT_SECRET_KEY=

# O emissor do token. Normalmente se coloca algo remete à você ou ao nome da sua aplicação.
JWT_ISSUER=

# O destinatário do token, representa a aplicação que irá usá-lo.
JWT_AUDIENCE=

# O ID da aplicação criada no site do Imgur onde ficarão armazenadas as imagens enviadas para dentro do projeto.
Client_ID_Imgur=

# Dominio onde está hospedado o client (frontend)
Client_Domain=http://localhost:5173

# Dominio onde está hospedado este projeto
Host_Domain=http://localhost:3001

# ID do clinete imgur para upload das imagens
Client_ID_Imgur=819ad8019235ea0

# ID do cliente do google para o login (oauth with google)
Client_ID_Google=

# Secret key encontrada no mesmo lugar do ID, e para o mesmo propósito
Client_Secret_Google=

```

2º passo - Com o terminal aberto na raiz do projeto, execute o comando `npm install` para que todas as dependências sejam baixadas.

3º passo - No mesmo terminal, execute `npm run start:dev`para que o projeto seja executado em modo de desenvolvimento.

---


## 📚 Documentação
Para visualizar a documentação de todas as rotas do projeto usando o swagger, [clique aqui](https://orange-portfolio-swagger.onrender.com/api) <br><br>
