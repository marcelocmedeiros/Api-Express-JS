# ⭐ Curso API com Express ⭐

O curso API com Express faz parte da Trilha Backend do **Especialista.dev**.

Neste curso, comecei aprender como utilizar o Express, um framework popular para aplicações web em Node.js. Este framework simplifica o processo de criação de aplicações web em Node.js, permitindo a criação de rotas, manipulação de requisições e respostas HTTP, gerenciamento de sessões de usuários, e muito mais.

Durante o curso, foi visto os conceitos básicos do Express e como utilizá-los para criar aplicações web em Node.js. Aprender como configurar o Express, criar rotas e manipular as requisições e respostas HTTP, gerenciar sessões de usuário, utilizar middlewares e muito mais.

O curso também conta com o desenvolvimento de uma aplicação backend para um frontend desenvolvido utilizando o React. Nesta aplicação, serão abordados conceitos mais avançados como login e autenticação utilizando JWT.

## 🧑‍💻 O que foi visto e ensinado durante o curso 🧑‍💻

- Como configurar um servidor Express
- Definição de rotas
- Como lidar com requisições e respostas HTTP
- Utilização de Middlewares

## 📚 Organização e criação do Projeto 📚

- **1** - Escolha um local para criar seu projeto.
- **2** - Crie uma pasta curso-express.
- **3** - Entre na pasta.
- **4** - agora via terminal dentro do caminho da pasta digite o seguinte comando:
  <code>npx express-generator-typescript fundamentos</code>
- **5** - Entre na pasta fundamentos pelo VSCode
- **6** - Exclui as seguintes pastas: env, spec e src.
- **7** - Agora cria novamente src e dentro da pasta crie o arquivo index.ts
- **8** - Apartir daqui pode copiar os arquivos e rodar o projeto.
- **9** - No terminal dentro da pasta do projeto rode o seguinte comando <code>npm run dev</code> para iniciar o servidor.

## About

This project was created with [express-generator-typescript](https://github.com/seanpmaxwell/express-generator-typescript).

## Available Scripts

### `npm run dev`

Run the server in development mode.

### `npm test`

Run all unit-tests with hot-reloading.

### `npm test -- --testFile="name of test file" (i.e. --testFile=Users).`

Run a single unit-test.

### `npm run test:no-reloading`

Run all unit-tests without hot-reloading.

### `npm run lint`

Check for linting errors.

### `npm run build`

Build the project for production.

### `npm start`

Run the production build (Must be built first).

### `npm start -- --env="name of env file" (default is production).`

Run production build with a different env file.

## Additional Notes

- If `npm run dev` gives you issues with bcrypt on MacOS you may need to run: `npm rebuild bcrypt --build-from-source`.
