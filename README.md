# issue

- blank nuxt project init
- install schema using ```pnpx nuxi module add schema-org```

```javascript

Nuxt 3.13.1 with Nitro 2.9.7                                                                                                                                    10:49:44 AM
                                                                                                                                                                10:49:44 AM
  ➜ Local:    http://localhost:3000/
  ➜ Network:  use --host to expose

  ➜ DevTools: press Shift + Option + D in the browser (v1.4.2)                                                                                                  10:49:45 AM

ℹ Re-optimizing dependencies because lockfile has changed                                                                                                      10:49:46 AM
✔ Vite client built in 34ms                                                                                                                                    10:49:46 AM
✔ Vite server built in 323ms                                                                                                                                   10:49:46 AM
✔ Nuxt Nitro server built in 439 ms                                                                                                                      nitro 10:49:46 AM
ℹ Vite client warmed up in 0ms                                                                                                                                 10:49:46 AM

[10:49:47 AM]  ERROR  [worker reload] [worker init] Package import specifier "#internal/nitro/virtual/app-config" is not defined in package /Users/saltytostitos/dev/testme/node_modules/.pnpm/nitropack@2.9.7_magicast@0.3.5/node_modules/nitropack/package.json imported from /Users/saltytostitos/dev/testme/node_modules/.pnpm/nitropack@2.9.7_magicast@0.3.5/node_modules/nitropack/dist/runtime/config.mjs

  at importNotDefined (node:internal/modules/esm/resolve:291:10)
  at packageImportsResolve (node:internal/modules/esm/resolve:741:9)
  at moduleResolve (node:internal/modules/esm/resolve:917:16)
  at defaultResolve (node:internal/modules/esm/resolve:1169:11)
  at ModuleLoader.defaultResolve (node:internal/modules/esm/loader:540:12)
  at ModuleLoader.resolve (node:internal/modules/esm/loader:509:25)
  at ModuleLoader.getModuleJob (node:internal/modules/esm/loader:239:38)
  at ModuleWrap.<anonymous> (node:internal/modules/esm/module_job:96:40)
  at link (node:internal/modules/esm/module_job:95:36)

ℹ Vite server warmed up in 370ms
```

# config

```json
export default defineNuxtConfig({
  "compatibilityDate": "2024-04-03",
  "devtools": { enabled: true },
  "modules": ["nuxt-schema-org"],
});
```

```
------------------------------
- Operating System: Darwin
- Node Version:     v20.17.0
- Nuxt Version:     3.13.1
- CLI Version:      3.13.1
- Nitro Version:    2.9.7
- Package Manager:  pnpm@9.10.0
- Builder:          -
- User Config:      compatibilityDate, devtools, modules
- Runtime Modules:  nuxt-schema-org@3.4.0
- Build Modules:    -
------------------------------
```