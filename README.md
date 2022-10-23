<h1 align="center"> Desafio 03 - Github Blog </h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/Fellippemfv/rocketseat-react-challange-3">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Fellippemfv/rocketseat-react-challange-3">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Fellippemfv/rocketseat-react-challange-3?color=yellow">
  
  <a href="https://github.com/Fellippemfv/rocketseat-react-challange-3/commits/master">
  	<img alt="last-commit" src="https://img.shields.io/github/last-commit/Fellippemfv/rocketseat-react-challange-3">
  </a>

  <a href="https://github.com/Fellippemfv/rocketseat-react-challange-3/blob/master/LICENSE.md">
  	<img alt="GitHub/license" src="https://img.shields.io/github/license/Fellippemfv/rocketseat-react-project-3">
  </a>
</p>

<p align="center">
  <a href="#round_pushpin-sobre-o-projeto">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias-utilizadas">Tecnologias utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="logo" title="logo" src="https://user-images.githubusercontent.com/67835741/197403869-ad3015d8-ca2a-47c8-ac26-435ca313b1bf.png" />
</p>

<br>

## :round_pushpin: Sobre o projeto

 Terceiro desafio de reactJS, realizado durante o curso de react da rocketseat. 
 
 Nesse desafio, desenvolvemos uma aplicação que se utilizará da API do GitHub para buscar issues de um repositório, dados do seu perfil e exibir elas como um blog.

- Listagem do seu perfil com imagem, número de seguidores, nome e outras informações disponíveis pela API do GitHub.
- Listar e filtrar todas as issues do repositório com um pequeno resumo do conteúdo dela
- Criar uma página para exibir um post (issue) completo

Apesar de serem poucas funcionalidades, usamos conceitos como:

- Fetch / Axios
- Roteamento e React Router DOM
- Formulários

## :rocket: Tecnologias utilizadas

Este projeto foi desenvolvido com as seguintes tecnologias:

-  [ReactJS](https://pt-br.reactjs.org)
-  [ViteJS](https://vitejs.dev)
-  [TypeScript](https://www.typescriptlang.org)
-  [Eslint](https://eslint.org)

## :information_source: Como usar

Para clonar e executar esta aplicação, você precisará do [Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [Npm](https://www.npmjs.com/) e um editor de texto igual ao [Vs code](https://code.visualstudio.com/) instalado em seu computador. Na sua linha de comando:

```bash
# Clonar este repositório
$ git clone https://github.com/Fellippemfv/rocketseat-react-project-3.git

# Ir até a pasta criada
$ cd rocketseat-react-project-3

# Instalar dependências
$ npm install
```

Para rodar esta aplicação vamos precisar criar uma porta para o frontend usando o vite.

```bash
# Para o vite iniciar um servidor no endereço: http://127.0.0.1:5173
$ npm run dev
```

Também temos alguns comandos opicionais para uso do eslint.

```bash
# Para o Eslint VERIFICAR se há erros de identação, falta de ponto/virgula ou erro de importação
$ npm run lint

# Para o Eslint CONSERTAR todos os erros
$ npm run lint:fix
```

Se quiser ver informções em tela vai precisar criar um repositorio no seu github usando este como base, criar issues para usarmos como artigos no formato de titulo, subtitulo e o conteudo. Depois coloque uma label chamada "Published" em cada issue criada. Por fim colocar suas informações do github no arquivo ".env".

## :memo: Licença

Este projeto está sob a licença do MIT. Veja o [LICENSE](https://github.com/Fellippemfv/rocketseat-react-project-3/blob/master/LICENSE.md) para mais informação.

---