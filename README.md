# nuxt3-gql-test

Minimum repro for `Unexpected token` error.

Stack trace:

```sh
nuxt3-gql-test/ npm run build

> @ build /Users/jerryjappinen/Development/nuxt3-gql-test
> nuxi build

Nuxt CLI v3.0.0-27444434.856c01a

 ERROR  [rollup-plugin-dynamic-import-variables] Unexpected token (1:6)
file: /Users/jerryjappinen/Development/nuxt3-gql-test/GetItemsQuery.gql:1:6


 ERROR  Unexpected token (1:6)

  at Parser.pp$4.raise (node_modules/rollup/dist/shared/rollup.js:19636:13)
  at Parser.pp$9.unexpected (node_modules/rollup/dist/shared/rollup.js:16932:8)
  at Parser.pp$9.semicolon (node_modules/rollup/dist/shared/rollup.js:16909:66)
  at Parser.pp$8.parseExpressionStatement (node_modules/rollup/dist/shared/rollup.js:17392:8)
  at Parser.pp$8.parseStatement (node_modules/rollup/dist/shared/rollup.js:17125:24)
  at Parser.pp$8.parseTopLevel (node_modules/rollup/dist/shared/rollup.js:16989:21)
  at Parser.parse (node_modules/rollup/dist/shared/rollup.js:16762:15)
  at Function.parse (node_modules/rollup/dist/shared/rollup.js:16812:35)
  at Graph.contextParse (node_modules/rollup/dist/shared/rollup.js:22958:38)
  at Object.transform (node_modules/vite/dist/node/chunks/dep-9c153816.js:28694:27)


 ERROR  [!] Error: unfinished hook action(s) on exit:
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/ohmyfetch/dist/index.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/@vue/runtime-core/dist/runtime-core.esm-bundler.js"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/@vue/shared/dist/shared.esm-bundler.js"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/hookable/dist/index.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/compat/legacy-app.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/component.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/asyncData.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/hydrate.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/state.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/fetch.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/cookie.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/ssr.mjs"
```