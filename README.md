# Empty Vue 3 App

## Project setup
```
npm install
```

## For performance testing 

### Run the application in production mode:

1) Build the application
```
npm run build
```

2) Launch the app. A `dist` folder has been generated, the following command will use the `dist` content.
```
npm run start:prod
```

3) Access to the page at `http://localhost:3000`

4) Open the chrome's console, go to the `Lighthouse` tab and run an audit with the Performance box checked (you can remove the other checkboxes)

### Measure the bundle size:

1) Build report

```
npm run build-report
```

Note: If you want to run the build-report command on your own vue 3 app, you need to add the command in the `package.json`.
```
    "build-report": "vue-cli-service build --report",
```

2) Open the generated report file: `dist/report.html`


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