<h1 align="center">NLW Heat - Node.js</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">
  <img src="https://img.shields.io/static/v1?label=NLW&message=Heat&color=8257E5&labelColor=000000" alt="NLW Heat" />
</p>

## ✨ Tecnologias

Esse projeto foi desenvolvido na primeira aula da NLW, com intuito de ser o backend da aplicação.
> Obs.: Nesse projeto temos autenticação via OAuth com o GitHub

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)
- [SQLite](https://www.sqlite.org)

## 🚀 Como executar


- Clone o repositório e acesse a pasta;
- Faça uma copia das três variáveis abaixo e coloque em um arquivo `.env` e preencha com as suas credenciais do GitHub;
- GITHUB_CLIENT_SECRET=Aqui usa a credencial do Github;
- GITHUB_CLIENT_ID=Aqui usa a credencial do Github;
- JWT_SECRET=Aqui usa um gerador de hash e coloque as credencias, ou pode digitar uma sequencia de caracteres de sua preferência.
- Instale as dependências com `yarn`;
- Executa as migrations com `yarn prisma migrate dev`;
- Inicie o servidor com `yarn dev`;

A aplicação pode ser acessada em [`localhost:4000`](http://localhost:4000).

## 📄 Licença

Esse projeto está sob a licença MIT.

---

Feito por Diego Ferreira com a instrutora Dani Leão na NLW - Heat da Rocketseat 
👋🏻 &nbsp;[Participe da comunidade!](https://discordapp.com/invite/gCRAFhc)