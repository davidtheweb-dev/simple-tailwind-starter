# Starter app for Tailwind projects

This is an extremely simple setup to develop Tailwind projects with everything you need to have a good development experience (ESlint + Prettier).

Dependencies included:

- tailwindcss, prettier-plugin-tailwindcss (needed for automatic class sorting for Tailwind w/ Prettier [https://tailwindcss.com/blog/automatic-class-sorting-with-prettier]).
- eslint, eslint-config-prettier (needed to avoid conflicts between eslint and prettier [https://vueschool.io/articles/vuejs-tutorials/eslint-and-prettier-with-vite-and-vue-js-3/]).

Required plugins (must be installed via VSCode extensions):

- ESLint
- PostCSS Language Support
- Prettier - Code formatter
- Tailwind CSS IntelliSense

## Usage

Install required VSCode plugins

Install dependencies

```
npm install
```

Run Tailwind CLI in watch mode

```
npm run watch
```

You can use tailwind classes in any .html files in the src directory

Put any custom CSS that you may have in the **input.css** file

Add any config values to the **tailwind.config.js** file

To build once, run

```
npm run build
```

You only need to deploy your html files and css/style.css

Enjoy! 😋
