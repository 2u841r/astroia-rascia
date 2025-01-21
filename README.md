Source code of [astro.zmt3.com](https://astro.zmt3.com), originally created by [Tania Rascia](https://github.com/taniarascia/taniarascia.com) in Gatsby+Markdown, I converted it to Astro.

previously to [Svelte+Wordpress-API](https://github.com/2u841r/zmt3.com) 
and [Nuxt](https://github.com/2u841r/nuxt.zmt3.com/)

My future plan is- 
[x] Svelte version of this site. 
[x] Vue/Nuxt version of this site. 
[] Convert css to TailwindCSS. 

## Instruction 
create a .env file bofore `npm run dev`, 
```txt
PUBLIC_API=https://yoursite.tld/wp-json/wp/v2
```
Its wordpress rest api link. Astro will visit each post, tag, category and make static files. you can see that in terminal in build process/ `npm run build`

feel free to change / use this src code for Markdown files. 

If you don't have wordpress site, find a website with wordpress, then visit that-sites-name.com/wp-json/wp/v2/posts 

If you get posts, use that link for test :-) 
or ask me (email available at /me route), I will give you my wordpress link. 


![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
