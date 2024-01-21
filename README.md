# blog.guitarrapc.com

# Deploy

see: https://docs.astro.build/en/guides/deploy/github/

# Getting started

Use pnpm to install and run.

```shell
npm install -g pnpm
pnpm install
pnpm run dev
```

Update packages with pnpm.

```shell
pnpm update
```

Update specific package.

```
pnpm add astro@latest
pnpm add @astro/mdx
pnpm add @astro/rss
pnpm add @astro/sitemap
```

# Create Astro Project

```
pnpm create astro@latest
```

        dir   Where should we create your new project?
                ./blog.guitarrapc.com

        tmpl   How would you like to start your new project?
                Use blog template
            ✔  Template copied

        deps   Install dependencies?
                Yes
            ✔  Dependencies installed

            ts   Do you plan to write TypeScript?
                Yes

        use   How strict should TypeScript be?
                Strict
            ✔  TypeScript customized

        git   Initialize a new git repository?
                No
            ◼  Sounds good! You can always run git init manually.

        next   Liftoff confirmed. Explore your project!

                Enter your project directory using cd ./blog.guitarrapc.com
                Run pnpm dev to start the dev server. CTRL+C to stop.
                Add frameworks like react or tailwind using astro add.

                Stuck? Join us at https://astro.build/chat

# Astro Starter Kit: Blog

```
npm create astro@latest -- --template blog
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/blog)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/blog)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/blog/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!


![blog](https://user-images.githubusercontent.com/4677417/186189140-4ef17aac-c3c9-4918-a8c2-ce86ba1bb394.png)

Features:

- ✅ Minimal styling (make it your own!)
- ✅ 100/100 Lighthouse performance
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Sitemap support
- ✅ RSS Feed support
- ✅ Markdown & MDX support

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

The `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`, and type-check your frontmatter using an optional schema. See [Astro's Content Collections docs](https://docs.astro.build/en/guides/content-collections/) to learn more.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Check out [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## Credit

This theme is based off of the lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).
