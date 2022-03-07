# nuxt3-gql-test

Minimum repro for the following issue:

```sh
nuxt3-gql-test/ npm run build

> @ build /Users/jerryjappinen/Development/nuxt3-gql-test
> nuxi build

Nuxt CLI v3.0.0-27444434.856c01a

ERROR  [rollup-plugin-dynamic-import-variables] Unexpected token (1:0)
file: /Users/jerryjappinen/Development/nuxt3-gql-test/gql/GetItemsQuery.gql:1:0


ERROR  Unexpected token (1:0)

  at Parser.pp$4.raise (node_modules/rollup/dist/shared/rollup.js:19636:13)
  at Parser.pp$9.unexpected (node_modules/rollup/dist/shared/rollup.js:16932:8)
  at Parser.pp$5.parseMaybeUnary (node_modules/rollup/dist/shared/rollup.js:18764:63)
  at Parser.pp$5.parseExprOps (node_modules/rollup/dist/shared/rollup.js:18696:19)
  at Parser.pp$5.parseMaybeConditional (node_modules/rollup/dist/shared/rollup.js:18679:19)
  at Parser.pp$5.parseMaybeAssign (node_modules/rollup/dist/shared/rollup.js:18646:19)
  at Parser.pp$5.parseExpression (node_modules/rollup/dist/shared/rollup.js:18609:19)
  at Parser.pp$8.parseStatement (node_modules/rollup/dist/shared/rollup.js:17122:45)
  at Parser.pp$8.parseTopLevel (node_modules/rollup/dist/shared/rollup.js:16989:21)
  at Parser.parse (node_modules/rollup/dist/shared/rollup.js:16762:15)


ERROR  [!] Error: unfinished hook action(s) on exit:
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/@vue/runtime-dom/dist/runtime-dom.esm-bundler.js"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/ufo/dist/index.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/h3/dist/index.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/ohmyfetch/dist/index.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/hookable/dist/index.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/compat/legacy-app.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/component.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/asyncData.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/hydrate.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/state.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/fetch.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/cookie.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/ssr.mjs"
(vite:load-fallback) load "/Users/jerryjappinen/Development/nuxt3-gql-test/node_modules/nuxt3/dist/app/composables/router.mjs"
```