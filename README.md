## Build from source

1. Install dependencies.

   ```sh
   npm install
   ```

2. Open debug tab on VScode and run "

   ```sh
   npm build
   ```

3. Error:
   ```
   /home/tailt/.nvm/versions/node/v19.1.0/bin/node -r /home/tailt/Workspace/projects/private-projects/test-tsconfig-paths-tsoa-bugs/node_modules/ts-node/register -r /home/tailt/Workspace/projects/private-projects/test-tsconfig-paths-tsoa-bugs/node_modules/tsconfig-paths/register ./dist/index.js
/home/tailt/Workspace/projects/private-projects/test-tsconfig-paths-tsoa-bugs/src/controllers/ping.controller.ts:9
  @Get("/")
      ^
TypeError: (0 , tsoa_1.Get) is not a function
    at Object.<anonymous> (/home/tailt/Workspace/projects/private-projects/test-tsconfig-paths-tsoa-bugs/src/controllers/ping.controller.ts:9:7)
    at Module._compile (node:internal/modules/cjs/loader:1205:14)
    at Module.m._compile (/home/tailt/Workspace/projects/private-projects/test-tsconfig-paths-tsoa-bugs/node_modules/ts-node/src/index.ts:1455:23)
    at Module._extensions..js (node:internal/modules/cjs/loader:1259:10)
    at Object.require.extensions.<computed> [as .ts] (/home/tailt/Workspace/projects/private-projects/test-tsconfig-paths-tsoa-bugs/node_modules/ts-node/src/index.ts:1458:12)
    at Module.load (node:internal/modules/cjs/loader:1068:32)
    at Function.Module._load (node:internal/modules/cjs/loader:909:12)
    at Module.require (node:internal/modules/cjs/loader:1092:19)
    at require (node:internal/modules/cjs/helpers:103:18)
    at Object.<anonymous> (/home/tailt/Workspace/projects/private-projects/test-tsconfig-paths-tsoa-bugs/src/routes/index.ts:2:1)
Process exited with code 1

   ```


