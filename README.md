# JavaScript template

Starter for a vanilla JavaScript app bundled with webpack, with ESLint and Prettier already wired up.

## Use this template

On GitHub, open this repository and choose **Use this template**, then **Create a new repository**. That copies these files into a new repo with a fresh git history.

[Use this template](https://github.com/HunterFlechsig/js_template/generate)

After you create the new repo, clone it and install dependencies:

```bash
npm install
npm start
```

`npm start` opens the dev server. `npm run build` writes a production bundle to `dist/`.

## Scripts

| Command                | What it does                           |
| ---------------------- | -------------------------------------- |
| `npm start`            | Start the webpack dev server           |
| `npm run build`        | Build for production into `dist/`      |
| `npm run lint`         | Check JavaScript with ESLint           |
| `npm run lint:fix`     | Apply ESLint fixes                     |
| `npm run format`       | Format the project with Prettier       |
| `npm run format:check` | Check formatting without writing files |
| `npm run deploy`       | Push `dist/` to the `gh-pages` branch  |

## Project layout

```
src/index.js        app entry
src/style.css       global styles
src/template.html   HTML template
webpack.common.js   shared webpack config
webpack.dev.js      development config
webpack.prod.js     production config
eslint.config.js    ESLint flat config
.prettierrc.json    Prettier config
```

Repository, bugs, and homepage fields are left out of `package.json` on purpose. Add them in the new project so they point at that repo, not this template.
