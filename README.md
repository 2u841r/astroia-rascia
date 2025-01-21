source code of astro.zmt3.com, originally created by [Tania Rascia](https://github.com/taniarascia/taniarascia.com) in Gatsby+Markdown, I converted it to Astro.
previously to previously to [Svelte+Wordpress-API](https://github.com/2u841r/zmt3.com) and [Nuxt](https://github.com/2u841r/nuxt.zmt3.com/).

My future plan is 
- [x] [Svelte](https://github.com/2u841r/zmt3.com) version of this site. 
- [x] [Vue-Nuxt](https://github.com/2u841r/nuxt.zmt3.com/) version of this site. 
- [ ] Convert CSS to Tailwind CSS.

Instruction
create a .env file beforenpm run dev

```
PUBLIC_API=https://yoursite.tld/wp-json/wp/v2
```

It's a WordPress REST API link. Astro will visit each post, tag, and category and make static files. You can see that in the terminal in the build process. npm run build

Feel free to change/use this src code for Markdown files.

If you don't have a WordPress site, find a website with WordPress, then visit that-sites-name.com/wp-json/wp/v2/posts.

If you get posts, use that link for test :-) or ask me (email available at /me route), I will give you my wordpress link.
