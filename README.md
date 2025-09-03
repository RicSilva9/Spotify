
# Spotify Clone

O Spotify Clone é um projeto desenvolvido durante a Imersão Dev da Alura, com o objetivo de recriar a interface e algumas funcionalidades básicas do Spotify. O foco principal foi a manipulação visual e a construção da estrutura do projeto, além do consumo de uma API disponibilizada pela própria Alura para rodar em localhost.


## Stacks utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)


## Screenshots

![Site Screenshot](/src/readmeIMG/Captura%20de%20tela%202025-09-02%20204935.png)![Pesquisa Screenchot](/src/readmeIMG/Captura%20de%20tela%202025-09-02%20215023.png)


## Rodando localmente

**Clone o projeto**

```bash
  git clone https://github.com/RicSilva9/Spotify
```

**Instale o JSON Server (Caso ainda não tenha)**

```bash
  npm install -g json-server
```

**Inicie a API Local**

```bash
  json-server --watch artists.json --port 3000

```
- *Isso vai iniciar a API na porta 3000.*

- *A API estará disponível em: http://localhost:3000/artists*

**Teste a API**

- Abra o link da API no navegador -
✅ Deve aparecer todos os artistas em formato JSON.

- Teste uma pesquisa parcial ex:(http://localhost:3000/artists?name_like=Foo)
✅ Deve retornar apenas o artista correspondente (Foo Fighters).

*Observação: se o JSON Server não filtrar corretamente, o projeto já está preparado para filtrar no JavaScript, garantindo que a pesquisa funcione.*

**Abrir o projeto no navegador**

- Abra o link https://ricsilva9.github.io/Spotify/

- Ou, se estiver usando VS Code, instale a extensão Live Server e abra o projeto para rodar em http://localhost:5500

**Testar a pesquisa**

Digite o nome ou inicial de um artista no campo de pesquisa.

O projeto vai exibir o primeiro artista correspondente, com imagem e nome.

Se não houver correspondência, nada será exibido.