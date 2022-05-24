<h1 align="center">
<br>
  <img src="./public/images/avatar.svg" alt="Ignews" width="200">
<br>
<br>
</h1>

#Site de notícias pay-per-view

## Ignews - O Projeto

O Ignews é um site de notícias pay-per-view. Qualquer pessoa pode acessar o site e ter um preview das notícias. Caso o visitante queira acessar as notícias na íntegra basta realizar a inscrição no site.

O site permite 
A aplicação é construída com modelo <strong>Serveless</strong>, sem necessidade de criar uma API externa para manipular os dados

## Techs
- [NextJS](https://nextjs.org/) - Framework para construção de sites
- [Typescript](https://www.typescriptlang.org/) - Linguagem de programação para construção de sites
- [Sass](https://sass-lang.com/) - Linguagem de estilo para construção de sites
- [FaunaDB](https://fauna.com/) - Banco de dados (noSql) para armazenamento de dados
- [Stripe](https://stripe.com/docs/payments) - Pagamento com cartão de crédito
- [Prismic.io](https://prismic.io/) - CMS para construção de sites

## Preview
<a target="_blank" href="#">
  <img src="./public/images/Ignews.gif" alt="License MIT">
</a>

## Iniciar a aplicação (desenvolvimento)
1. Requirido: 
  - [Git](https://git-scm.com/) - Sistema de controle de versão
  - [Node](https://nodejs.org/en/) - Linguagem de programação para construção de aplicações
  - [Yarn](https://yarnpkg.com/) - Gerenciador de dependências
2. Clonar o repositório:
```bash
$ git clone https://github.com/esbnet/ignews.git
$ cd ignews
```
3. Renomear o arquivo env.example para .env e alterar as configurações. Consultar a documentação de cada recurso definido no .env ([ver🏹](#techs))
```bash
ren env.example .env
```
4. Configurar o arquivo:  __sm.json__ (ver documentação)
```bash
{ "_latest": "0.3.7",
  "apiEndpoint": "https://seu_dominio.prismic.io/api/v2",
  "libraries": [
    "@/slices"
  ]
}
```
5. Instalar as dependências do projeto e iniciar a aplicação:
```bash
$ yarn install
$ yarn dev
```
##  Licença
[MIT](https://github.com/esbnet/ignite-next-ignews/blob/main/LICENSE)
## Créditos
- 🚀 [Rocketseat](www.ignews.com.br) - aplicação do curso ignite
- Edmilson Soares - [send 📨](esbnet@gmail.com) | [linkedin](https://www.linkedin.com/in/edmilson-soares/)