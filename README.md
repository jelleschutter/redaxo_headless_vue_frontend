# redaxo-headless-vue
This a example for a possible use of the [redaxo_headless](https://github.com/jelleschutter/redaxo_headless) REDAXO AddOn.

## Examples
The navigation endpoint of the addon is used in "[src/App.vue](https://github.com/jelleschutter/redaxo_headless_vue_frontend/blob/improve-readme/src/App.vue)" and the page content endpoint can be found in action inside "[src/views/Page.vue](https://github.com/jelleschutter/redaxo_headless_vue_frontend/blob/improve-readme/src/views/Page.vue)".

## SEO
This example application is not Search Engine Optimized (due to a lack of knowlegde on my part). Feel free to add a PR!

## Development Setup
1. Please make sure that the [redaxo_headless](https://github.com/jelleschutter/redaxo_headless) addon is installed on your REDAXO Instance.
2. Copy the ".env" file as ".env.local".
3. Set the url of your REDAXO instance inside the ".env.local".
4. Make sure the debug mode is enabled in the REDAXO addon.
5. Install NPM dependencies run `npm install`
5. Start app `npm run serve`

## Deployment Setup
1. Please make sure that the [redaxo_headless](https://github.com/jelleschutter/redaxo_headless) addon is installed on your REDAXO Instance.
2. Make sure the headless/deployment plugin is installed and enabled.
3. Enable in deployment and add a token in the REDAXO addon on the "deploy" page.
4. Add GitHub action to the repo: [redaxo-headless-deploy](https://github.com/jelleschutter/redaxo-headless-deploy)

## NPM Development
### Install dependencies
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
