# laravel-react-redux-boilerplate

<a target="_blank" href="https://opensource.org/licenses/MIT" title="License: MIT">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg">
</a>
<a href="#badge">
  <img alt="code style: prettier" src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg">
</a>

A simple boilerplate for [React](https://reactjs.org/) and [Redux](https://redux.js.org/) with [Laravel](https://laravel.com) as API server.

## Features

-   **[Laravel 5.6](https://laravel.com/docs/5.6)**: Back-end server framwork.
-   **[React 16](https://reactjs.org/)**: Front-end framework.
-   **[Redux 4](https://redux.js.org/)**: React state management.
-   **[Boostrap 4](https://getbootstrap.com/)**: Front-end UI kit.
-   **[React Router v4](https://reacttraining.com/react-router/)**: Declerative routing.
-   **[redux-thunk](https://github.com/reduxjs/redux-thunk)**: `async` Redux action.
-   **[styled-components](https://www.styled-components.com/)**: The best CSS in JS library.
-   **[webpack-dev-server](https://github.com/webpack/webpack-dev-server)**: Hot Module Replacement.
-   **[ESLint](https://eslint.org/), [prettier](https://github.com/prettier/prettier)**: Lint JavaScript.
-   **[Babel 6](https://babeljs.io/)**: Support ES6 syntax.

## Install

```sh
$ git clone https://github.com/xxhomey19/laravel-react-redux-boilerplate.git
$ cd laravel-react-redux-boilerplate
$ composer install
$ yarn // or npm install
$ cp .env.example .env
$ php artisan key:generate
```

## Development

Open two consoles. One is for `webpack-dev-server`, and the other is for `Laravel` server.

The first console:

```sh
$ npm run dev
```

The second console:

```sh
$ php artison serve
```

## License

MIT © [xxhomey19](https://github.com/xxhomey19)
