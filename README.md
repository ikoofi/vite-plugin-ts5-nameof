<h1 align="center">vite-plugin-ts5-nameof</h1>


## Usage

1. Install as `devDependencies`

   ```bash
   npm add --save-dev vite-plugin-ts5-nameof
   # or
   yarn add --dev vite-plugin-ts5-nameof
   # or
   pnpm add --save-dev vite-plugin-ts5-nameof
   ```

2. Inject `vite-plugin-ts5-nameof` using the `vite.config.ts` module

   ```ts
   import vue from '@vitejs/plugin-vue';
   import { defineConfig } from 'vite';
   import tsNameof from 'vite-plugin-ts5-nameof';

   // https://vitejs.dev/config/
   export default defineConfig({
     plugins: [tsNameof(), vue()],
   });
   ```

3. Add `ts5-nameof.d.ts` to your `tsconfig.json`

   ```jsonc
   {
     // "compilerOptions"
     // "include"
     // ...
     "files": ["./node_modules/ts5-nameof/ts5-nameof.d.ts"]
   }
   ```

## More Awesome Vite Plugins

Can be found here: [Awesome Vite.js](https://github.com/vitejs/awesome-vite#readme)
