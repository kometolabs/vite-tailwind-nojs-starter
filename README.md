NoJS Vite + Tailwind CSS Starter
====

## Motivation

The official Create Vite tool doesn't have a Tailwind template [yet](https://github.com/vitejs/vite/pull/9304), so this project gives a solution for quick scaffolding of a new project with Vite and Tailwind CSS preconfigured.

The important difference of the starter template is that the build stage does not involve any JavaScript, just pure HTML/CSS compilation.

## When to use

1. When you need to develop a pure HTML/CSS prototype.
2. When you import a standalone version of a JS framework right through HTML.

## How to use

```bash
npx degit kometolabs/vite-tailwind-starter my-tailwind-app
cd my-tailwind-app
pnpm i || yarn || npm i
pnpm run dev || yarn dev || npm run dev
```

**Happy coding!**
