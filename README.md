# Storybook & SvelteKit 1.0.0 Problem

```sh
npm install
npm run storybook
```

**Error:**

```
ERR! Error [ERR_PACKAGE_PATH_NOT_EXPORTED]: No "exports" main defined in C:\path-to-repo\node_modules\@sveltejs\vite-plugin-svelte\package.json
ERR!     at new NodeError (node:internal/errors:387:5)
ERR!     at throwExportsNotFound (node:internal/modules/esm/resolve:365:9)
ERR!     at packageExportsResolve (node:internal/modules/esm/resolve:589:7)
ERR!     at resolveExports (node:internal/modules/cjs/loader:529:36)
ERR!     at Function.Module._findPath (node:internal/modules/cjs/loader:569:31)
ERR!     at Function.Module._resolveFilename (node:internal/modules/cjs/loader:981:27)
ERR!     at Function.Module._load (node:internal/modules/cjs/loader:841:27)
ERR!     at Module.require (node:internal/modules/cjs/loader:1067:19)
ERR!     at require (node:internal/modules/cjs/helpers:103:18)
ERR!     at pluginConfig (C:\path-to-repo\node_modules\@storybook\builder-vite\dist\vite-config.js:161:34)
ERR!  Error [ERR_PACKAGE_PATH_NOT_EXPORTED]: No "exports" main defined in C:\path-to-repo\node_modules\@sveltejs\vite-plugin-svelte\package.json
ERR!     at new NodeError (node:internal/errors:387:5)
ERR!     at throwExportsNotFound (node:internal/modules/esm/resolve:365:9)
ERR!     at packageExportsResolve (node:internal/modules/esm/resolve:589:7)
ERR!     at resolveExports (node:internal/modules/cjs/loader:529:36)
ERR!     at Function.Module._findPath (node:internal/modules/cjs/loader:569:31)
ERR!     at Function.Module._resolveFilename (node:internal/modules/cjs/loader:981:27)
ERR!     at Function.Module._load (node:internal/modules/cjs/loader:841:27)
ERR!     at Module.require (node:internal/modules/cjs/loader:1067:19)
ERR!     at require (node:internal/modules/cjs/helpers:103:18)
ERR!     at pluginConfig (C:\path-to-repo\node_modules\@storybook\builder-vite\dist\vite-config.js:161:34) {
ERR!   code: 'ERR_PACKAGE_PATH_NOT_EXPORTED'
ERR! }
```
