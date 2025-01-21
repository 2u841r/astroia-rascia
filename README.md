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

