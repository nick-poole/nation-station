# nation-station

![Nation Station Logo](src/assets/logo/nation_station.png)

Nation Station is a captivating country guide app built with Vue.js and Bootstrap. It enables users to explore and discover fascinating information about different countries.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Home page with a visually appealing hero section to prompt users to explore countries.
- Country selection feature to choose a specific country and view detailed information.
- Integration with Unsplash API to dynamically generate images based on the selected country.

## Usage

- 0n the home page, users can explore countries by selecting a country from the provided options or by using the search functionality.
- After selecting a country, users are presented with detailed information about that country, including cultural highlights, landmarks, and travel tips.
- Users can navigate back to the home page or explore other countries through the navigation menu.

## Dependencies

The main dependencies used in this project are:

- Vue.js: A progressive JavaScript framework for building user interfaces.
- Bootstrap: A popular CSS framework for building responsive and mobile-first websites.
- Unsplash API: An API for accessing a vast collection of high-quality images.

For a complete list of dependencies, refer to the `package.json` file.

## Contributing

Contributions are welcome! If you would like to contribute to Atlas Insight, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and write tests if applicable.
4. Commit and push your changes to your forked repository.
5. Submit a pull request, explaining the changes you made.

## License

This project is licensed under the [MIT License](LICENSE).

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Headed Component Tests with [Cypress Component Testing](https://on.cypress.io/component)

```sh
npm run test:unit:dev # or `npm run test:unit` for headless testing
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

### Design

- Primary: $yellow-500

- Secondary: $blue-800

- Alt: $gray-600
