<h1 align="center">
  ReacTests
</h1>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=Ignite ReactJS&message=Chapter V&color=8257E5&labelColor=000000" alt="Ignite ReactJS Chapter V"/>

  <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000" alt="License">
</p>

<br>

<p align="center">
  <img alt="ReacTests" src=".github/cover.png" width="100%">
</p>

<br>

## 🧪 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [React](https://reactjs.org)
- [NextJS](https://nextjs.org/)
- [Sass](https://sass-lang.com/)
- [NextAuth](https://next-auth.js.org)
- [Stripe](https://stripe.com/)
- [FaunaDB](https://fauna.com/)
- [Prismic CMS](https://prismic.io/)
- [Jest](https://jestjs.io/)
- [Testing Library](https://testing-library.com/)
- [TypeScript](https://www.typescriptlang.org/)

## 💻 Projeto

O projeto tem como objetivo o estudo e reutilização de uma aplicação em NextJS (ig.news) para aplicar conceitos de testes no ambiente front-end dentro do React.

ReacTests é uma reutilização de uma aplicação que utiliza o framework NextJS (ig.news) onde aplicamos conceitos de testes automatizados garantindo que nossos componentes e páginas continuem funcionando independente de novas manutenções, tudo isso usando Jest e Testing Library. 

Este é um projeto desenvolvido como prática das aulas do Chapter V da trilha ReactJS do **[Programa Ignite](https://www.rocketseat.com.br/ignite)** da Rocketseat.

## 🚀 Como executar

Clone o projeto e acesse a pasta do mesmo.

```bash
$ git clone https://github.com/rafaelramosdev/reactests
$ cd reactests
```

Para iniciá-lo, siga os passos abaixo:

```bash
# Instala as dependências
$ yarn

# Na raiz do projeto, no arquivo .env.local
# Preencha as variáveis ambiente de acordo com as instruções
$ .env.local

# Execute stripe para ouvir eventos do webhook
$ yarn stripe

# Inicia o website
$ yarn dev
```

O website estará disponível no seu navegador pelo endereço [`http://localhost:3000`](http://localhost:3000).

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito by [Rafael Ramos](https://rafaelramos.dev/) 🙋🏻‍♂️
