<template>
  <div class="container">
    <h1>Contact me</h1>
    <div>
      <font-awesome-icon :icon="['fas', 'envelope']" />
      <p>yechunchun (at) ucla (dot) edu</p>
    </div>
    <a
      href="https://www.linkedin.com/in/chunchunye/"
      title="LinkedIn Page"
      target="_blank"
    >
      <font-awesome-icon :icon="['fab', 'linkedin']" />
      <p>LinkedIn Page</p>
    </a>
    <a
      href="https://github.com/appletreeisyellow/"
      title="Github Link"
      target="_blank"
    >
      <font-awesome-icon :icon="['fab', 'github']" />
      <p>Github Link</p>
    </a>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Contact me",
      meta: [
        { name: "twitter:title", content: "Contact Chunchun Ye" },
        { name: "twitter:description", content: "Email, LinkedIn, Github" },
        //{ name: 'twitter:image', content: 'https://i.imgur.com/UYP2umJ.png'},
        //{ name: 'twitter:card', content: 'summary_large_image'}
        // TODO: facebook, instagram, ...
      ],
    };
  },
};
</script>

<style></style>
