# Aryo

## For Developers

I have created the app using:
`npx create-next-app@latest`

### Extensions

Beside the common extensions for VsCode you should also make sure you have:

1. ES7+ React/Redux/React-Native snippets by dsznajder.
2. Prettier by Prettier.
3. Tailwind CSS IntelliSense by Tailwind Labs.
4. Tailwind CSS IntelliSense by alfredbirk.

### Chrome Tools

You should have:

1. Pesticide for Chrome
2. Redux DevTools

### Dependencies

`cd client`

We have added `--legacy-peer-deps` flag to be compatible with Next and React Versions

`npm i lucide-react uuid dotenv date-fns framer-motion react-hook-form zod @hookform/resolvers @hello-pangea/dnd --legacy-peer-deps`

#### Tailwind

`npm i tailwindcss-animate --legacy-peer-deps`

#### Shadcn

In shadcn always choose --legacy-peer-deps option

`npx shadcn@latest init -d`

`npx shadcn@latest add accordion avatar button card dialog form input label navigation-menu popover progress select separator sheet sidebar skeleton switch table tabs textarea toggle tooltip`

#### Redux

`npm i react-redux @reduxjs/toolkit --legacy-peer-deps`

### Dev Dependencies

`cd client`

`npm i -D @types/node @types/uuid --legacy-peer-deps`

`npm i -D prettier-plugin-tailwindcss --legacy-peer-deps`

### Env Variables

you should create `.env{.local/.development/.deployment}` with Variables same as `.env.example`
