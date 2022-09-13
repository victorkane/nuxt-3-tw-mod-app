## Created

```bash
npx nuxi init nuxt-tw-app
cd nuxt-tw-app
npm i
npm run dev -- -o
```

## Simple homepage + tailwind

```bash
npm install --save-dev @nuxtjs/tailwindcss
vi nuxt.config.ts
cat nuxt.config.ts
import { defineNuxtConfig } from 'nuxt'

// https://v3.nuxtjs.org/api/configuration/nuxt.config
export default defineNuxtConfig({
  modules: ['@nuxtjs/tailwindcss']
})
npx tailwindcss init
vi app.vue
cat app.vue
victorkane@Victors-MacBook-Air nuxt-tw-app % cat app.vue
<template>
  <div class="text-center p-4">
    <h1 class="text-red-300">Welcome</h1>
    <h2 class="text-red-500">Welcome</h2>
    <h3 class="text-red-700">Welcome</h3>
  </div>
</template>

npm run dev -- -o
Nuxi 3.0.0-rc.9                                                       00:18:30
Nuxt 3.0.0-rc.9 with Nitro 0.5.1                                      00:18:30
                                                                      00:18:33
  > Local:    http://localhost:3000/
  > Network:  http://192.168.0.221:3000/

ℹ Using default Tailwind CSS file from runtime/tailwind.css
ℹ Tailwind Viewer: http://localhost:3000/_tailwind/  nuxt:tailwindcss 00:18:34
ℹ Vite server warmed up in 833ms                                      00:18:37
ℹ Vite client warmed up in 1731ms                                     00:18:37
✔ Nitro built in 1101 ms                                        nitro 00:18:38
```

- Runtime comes up automatically at http://localhost:3000/
- Incredible tailwind Viewer at http://localhost:3000/_tailwind

---
# Nuxt 3 Minimal Starter

Look at the [nuxt 3 documentation](https://v3.nuxtjs.org) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
