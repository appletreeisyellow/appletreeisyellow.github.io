Here are the logs I did to create the webpage from scratch using nuxt.js.

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

Here is a [guide](https://medium.com/@kozyreva.hanna/nuxt-js-fontawesome-integration-7ec56b1a41c8) helps you to walk through the nuxt-fontawesome installation
