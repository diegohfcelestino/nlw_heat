<h1 align="center">NLW Heat - Elixir</h1>

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

Esse projeto foi desenvolvido na quarta aula da NLW, com intuito de ser o frontend web da aplicação.

- [Elixir](https://elixir-lang.org/)
- [Phoenix](https://www.phoenixframework.org/)
- [Ecto](https://hexdocs.pm/ecto/Ecto.html)
- [Task](https://hexdocs.pm/elixir/1.12/Task.html)
- [Quantum](https://github.com/quantum-elixir/quantum-core)
- [PostGreSQL](https://www.postgresql.org/)


## 🚀 Como executar


- Clone o repositório e acesse a pasta;
- Tenha o PostgreSQL instalado em sua maquina.
- Instale as dependências com `mix deps.get`;
- Navegue nas pastas do projeto e entre em config e verifique o username e password nos arquivos dev.exs e test.esx, estes campos devem estar preenchidos com nome e senha do seu banco de dados postgree.
- Crie o banco de dados com o comando `mix ecto.setup`
- Inicie a aplicação com `mix phx.server` ou dentro do IEx com `iex -S mix phx.server`.

A aplicação pode ser acessada em [`localhost:4000/dashboard`](http://localhost:4000/dashboard).

## 📄 Licença

Esse projeto está sob a licença MIT.

## Saiba mais
  * Site oficial: https://www.phoenixframework.org/
  * Guias: https://hexdocs.pm/phoenix/overview.html
  * Documentação: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Fonte: https://github.com/phoenixframework/phoenix
---

Feito por Diego Ferreira com o instrutor Rafael Camarda na NLW - Heat da [Rocketseat](https://www.rocketseat.com.br/).

👋🏻 &nbsp;[Participe da comunidade!](https://discordapp.com/invite/gCRAFhc)

