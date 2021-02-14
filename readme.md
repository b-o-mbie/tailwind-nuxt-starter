# tailwind-nuxtjs-starter

## about

Starter project for static site tailwind webpages. 

tailwind and nuxt.js has excelent documentation on this topic so this repo has two goals:
 - to get started faster (as this is a template repo)
 - to gather up all the neccessary docs from setting up tailwind to configure github pages cd 

## stack
 - [tailwind](https://tailwindcss.com/) - css framework
 - [nuxt.js](https://nuxtjs.org/) - static site generator
 - [GitHub pages](https://pages.github.com/) - hosting

## tl;dr;
### ide
You may use VS Code with these plugin to have an [amazing support](https://tailwindcss.com/docs/intellisense) for tailwind.
 - [VS Code](https://code.visualstudio.com/)
 - [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
 - [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
 - Open VS Code settings and configure tailwind intellisense to work with vue files too.
 ```
  "tailwindCSS.includeLanguages": {
    "vue": "html",
    "vue-html": "html"
  }
 ```
### project
 - Use this template
 - `npm i`
 - `npm run dev` - run dev server
 - set up [github pages] to host from `gh-pages` branch - you may push once before this step to create automaticly the branch.

## more info and references
 - [Install Tailwind CSS with Nuxt.js](https://tailwindcss.com/docs/guides/nuxtjs)
 - [Deploy Nuxt on GitHub Pages](https://nuxtjs.org/docs/2.x/deployment/github-pages/)

## ps
Feel free to open an issue if you have any question, I will try my best to answare or update this repo asap.
 