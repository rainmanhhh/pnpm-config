# pnpm-config

## vue-pnpm
1. alias `yarn` to `pnpm i` if you choose yarn for vue-cli config; or alias `npm` to `pnpm` if you choose npm for vue-cli config
2. to fix webpack deps  
`pnpm i -D @vue/component-compiler-utils ansi-regex babel-core cache-loader css-loader vue-loader url-loader vue-style-loader postcss-loader thread-loader @vue/cli-service`

3. to fix ts deps  
`pnpm i -D typescript tslib ts-loader reflect-metadata`