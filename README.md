# Vue3 + Tailwind CSS Boilerplate

A Vue 3 Starter Boilerplate with Tailwind CSS, Vue Router 4, Vuex 4, Typescript 4, Webpack 5, Prettier and More.

**And not using the Vue CLI.**

![Vue3 + Tailwind CSS Boilerplate](./2020-11-16-232725_596x413_scrot.png)

## Architecture

```text
├─ public           // static assets.
├─ service          // commands and webpack configurations.
├─ src
│  ├─ assets        // assets such as images or font files.
│  ├─ components    // universal Vue components.
│  ├─ router        // view's routers config.
│  ├─ store         // Vuex store modules.
│  ├─ typings       // typescript .d.ts files.
│  └─ views         // pages.
```

## Commands

```bash
# Start development server.
yarn serve

# Compile production bundle.
yarn build
```
