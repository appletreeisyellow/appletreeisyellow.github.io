This is the logs of what I did to create the webpage from scratch using nuxt.js. I also followed this free course [Nuxt.js Fundamentals](https://vueschool.io/courses/nuxtjs-fundamentals) offered by from [Vue school](https://vueschool.io/).

---

Install nuxt app

```
npx create-nuxt-app appletreeisyellow.github.io
```

Add `.gitignore` file. Initially, add the following lines:

```
.DS_Store
node_modules/
dist/
.nuxt/
```

You can find more complete `.gitignore` [here](https://github.com/appletreeisyellow/dotfiles/blob/master/.gitignore).

Running the dev mode. Then open `http://localhost:3000/` in browser.

```
npm run dev
```

Install Font Awesome

```
npm i --save nuxt-fontawesome
npm i --save @fortawesome/free-brands-svg-icons
npm i --save @fortawesome/free-solid-svg-icons
```

Here is a [guide](https://medium.com/@kozyreva.hanna/nuxt-js-fontawesome-integration-7ec56b1a41c8) helps you to walk through the nuxt-fontawesome installation.
