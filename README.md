# Astro 101

**Learning Astro **

Why?
I decided in some downtime on most weekends that I would like to learn something new so today I decided to learn about Astro, the latest and "greatest static site Javascript framework" (not my claim :D) which piqued my interest, let see how it goes.

## Day 1

Layouts, Astro Components, Styles, & Pages

On this day, I want to learn the basics such as how to create layouts, comonents, pages and passing props around through each of them.

Lesson learned (TBU)

## 🚀 Default Astro stuff --> Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## 👀 Want to learn more?

Feel free to check [our documentation](https://github.com/withastro/astro) or jump into our [Discord server](https://astro.build/chat).
