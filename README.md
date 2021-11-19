# Desafio FrontEnd - Gazin-Tech

### 📺 GazinFilms 

![](https://i.ibb.co/pyc6MGS/Group-15.png)

## ℹ️ Informações

Esse desafio é composto de algumas etapas. O intuito não é de forma alguma que se tenha que implementa-lo completamente para qualquer consideração de contração.

Dica 1: Fique tranquilo e tente resolvê-lo como se estivesse estudando algo novo que queira aprender.

O objetivo desse desafio é compreender quais conhecimentos você já possui e sua desenvoltura diante a problemas ou tarefas que esteja se deparando pela primeira vez.

Imagine que o resultado do seu trabalho será um projeto público que será utilizado por várias pessoas. Sendo assim, aplique neste projeto as boas práticas de desenvolvimento de software que você conhece.

**Criar um repositório público em algum serviço de hospedagem como GitHub, GitLab, BitBucket, para armazenar seu código. O mesmo deve ser enviado para a avaliação do código.**

## 💬 Escopo do desafio

Desenvolver uma aplicação Front-end na linguagem/framework de sua preferência, tendo como requisito ser em SPA (single-page application) e atender os requisitos listados abaixo.

**Você deve seguir como base para o desenvolvimento do layout da aplicação o seguinte mockup:**
#### [ ► Mockup - Figma ](https://www.figma.com/file/9rnzjWDSvwlENgQNwxfu28/GazinFilms?node-id=110%3A1881)

Com base no mockup do link acima você deve criar uma aplicação Front-end que consome a seguinte API : **[IMDb API](https://rapidapi.com/apidojo/api/imdb8/)**. Esta API é pública e tem dados de diversos filmes de todo o mundo. Para obter todas as informações sobre a API, pelo mesmo link você tem acesso a documentação da mesma.

Outra API que pode ser utilizada para auxiliar com a tradução de algum dado é a API de traduções do Google, que pode ser acessada por aqui: **[Google Translate Api](https://rapidapi.com/googlecloud/api/google-translate1/)**. A API do IMDb já possuí integração com a API de traduções do google, porém caso necessite ou deseje, a API do google pode ser utilizada separadamente, basta consultar a sua documentação no link informado.

## 💽 Requisitos

A aplicação deve ser componentizada, com os seguintes componentes obrigatórios:

- ***Header*** (Componente de cabeçalho);
- ***Footer*** (Componente de rodapé);
- ***Banner*** (Componente de banner com imagens recuperadas da API do IMBb);
- ***ListFilms*** (Componente de listagem de filmes com dados recuperados da API do IMBb);
- ***ListActors*** (Componente de listagem de atores com dados recuperados da API do IMBb);
- ***ListResults*** (Componente de listagem de filmes com dados recuperados da API do IMBb após um filtro aplicado via Front-End);
- ***Details*** (Componente de descrição da biografia/filmogragia/descrição de um filme ou ator com dados recuperados da API do IMBb).

A aplicação deve conter no mínimo as quatro páginas apresentadas no mockup com as seguintes rotas:

- ***/home ►*** Página incial da aplicação;
- ***/search ►*** Página que lista os filmes após serem filtrados via o campo de input presente no header;
- ***/movie-detail ► *** Página que exibe os detalhes de um filme selecionado;
- ***/actor-detail ►*** Página que exibe os dados de um ator selecionado.

A aplicação deve conter um campo de busca no header das páginas, que quando submetido renderiza a página `/search` contendo os filmes retornados da busca na API do IMDb.

⚠️ **O layout apresentado no Figma não precisa ser seguido 100% fiel, você pode implementar novas features, funcionalidades, campos, animações, etc... como bem desejar! Use sua criatividade com base no layout apresentado para nos surpreender, isso pode acabar contando mais pontos no seu desafio.** 😃

**Você também pode utilizar bibliotecas de componentes já existentes de sua escolha, como por exemplo MaterialUI, Tailwind, Bootstrap, etc..**

## 🔋 Opcionais

Os itens abaixo não são obrigatórios para o desafio, mas caso tenha as skills necessárias para implementá-los podem contar mais pontos no seu desafio!

- **Implementação de testes;**
- **Utilizar Storybook;**
- **Clean Code;**
- **Hospedagem em algum serviço de nuvem (Vercel, Heroku, etc...);**
- **Implementar função Dark/Light Theme (Com a utilização de contexto);**
- **Animações CSS;**
- **Criação de novas páginas e funcionalidades;**
- **Implementação de Docker para execução do ambiente;**
- **Controle de versão (GIT);**
- **Documentação do projeto.**

## BOA SORTE! 😁
