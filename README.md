# nuxt-test

> Nuxt.js project to file a bug report

## Bug reproduction

### versions
- node    : 9.11.1
- npm     : 5.8.0
- vue-cli : 2.9.3


### Steps to reproduce:
- npm install -g vue-cli
- vue init nuxt-community/starter-template nuxt-test
- npm uninstall nuxt
- npm install nuxt-edge -S
- npm run dev

This gives following output :
```
> nuxt-test@1.0.0 dev /Users/tdhulster/workspace/tmp/nuxt-edge
> nuxt


 INFO  Building project

✔ success Builder initialized
✔ success Nuxt files generated


 ERROR  Failed to compile with 1 errors                                                                                                                                                                                          12:10:32 AM

Module build failed: TypeError: Cannot read property 'eslint' of undefined
    at Object.module.exports (/Users/tdhulster/workspace/tmp/nuxt-edge/node_modules/eslint-loader/index.js:148:18)

You may use special comments to disable some warnings.
Use // eslint-disable-next-line to ignore the next line.
Use /* eslint-disable */ to ignore all warnings in a file.
```

