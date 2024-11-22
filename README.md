# MovieApp

Um aplicativo de filmes desenvolvido em React Native que permite aos usuários explorar, pesquisar e visualizar informações sobre seus filmes favoritos. O MovieApp utiliza a API do The Movie Database (TMDb) para fornecer dados atualizados sobre filmes, incluindo sinopses, trailers, classificações e muito mais.

## Funcionalidades

- Navegação intuitiva entre as telas
- Pesquisa de filmes por título
- Exibição de detalhes do filme, incluindo sinopse, elenco e avaliações
- Lista de filmes em alta e lançamentos recentes
- Favoritar filmes para fácil acesso posterior

## Tecnologias Utilizadas

- **React Native**: Framework para desenvolvimento de aplicativos móveis
- **React Navigation**: Para navegação entre telas
- **Axios**: Para requisições HTTP à API do TMDb
- **Redux**: Para gerenciamento de estado (opcional)
- **Styled Components**: Para estilização de componentes

## Pré-requisitos

Antes de começar, você precisará ter o Node.js e o npm (ou yarn) instalados em sua máquina.

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/movieapp.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd movieapp
    ```
3. Instale as dependências:

    ```bash
    npm install
    ```
ou

    ```bash
    yarn install
    ```

4. Crie um arquivo .env na raiz do projeto e adicione sua chave da API do TMDb:
    ```bash
    TMDB_API_KEY=suachavedaapi
    ```

5. Inicie o aplicativo:
    ```bash
    npm run start
    ```

ou

    ```bash
    yarn start
    ```

6. Para rodar no Android:

    ```bash
    npm run android
    ```

ou

    ```bash
    yarn android
    ```

7. Para rodar no iOS:

    ```bash
    npm run ios
    ```

ou

    ```bash
    yarn ios
    ```

