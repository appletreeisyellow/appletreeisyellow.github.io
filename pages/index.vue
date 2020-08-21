<template>
  <section class="container">
    <div>
      <img
        src="https://vueschool.io/img/favicons/apple-touch-icon.png"
        alt="the logo"
      />
      <h1 class="title">
        nuxt-fundamentals
      </h1>
      <h2 class="subtitle">
        My gnarly Nuxt.js project
      </h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green"
          >Documentation</a
        >
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
          >GitHub</a
        >
      </div>
    </div>
    <div>
      <p>Icons</p>
      <font-awesome-icon :icon="['fab', 'linkedin']" />
      <font-awesome-icon :icon="['fab', 'github']" />
      <font-awesome-icon :icon="['fab', 'facebook']" />
      <font-awesome-icon :icon="['fas', 'coffee']" />
    </div>
  </section>
</template>

<script>
export default {
  head() {
    return {
      title: "Chunchun Ye 👩‍💻",
      meta: [
        { name: "twitter:title", content: "Chunchun Ye" },
        // TODO: update description
        { name: "twitter:description", content: "A software engineer" },
        //{ name: 'twitter:image', content: 'https://i.imgur.com/UYP2umJ.png'},
        //{ name: 'twitter:card', content: 'summary_large_image'}
        // TODO: facebook, instagram, ...
      ],
    };
  },
};
</script>

<style scoped>
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  letter-spacing: 1px;
}
.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
}
.links {
  padding-top: 15px;
}
</style>
