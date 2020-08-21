<template>
  <nav class="navbar navbar-expand-lg navbar-light border-bottom">
    <nuxt-link :to="{ name: 'index' }" class="navbar-brand text-dark">
      Chunchun Ye
    </nuxt-link>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <nuxt-link :to="{ name: 'index' }" class="nav-link">
            Home <span class="sr-only">(current)</span>
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link :to="{ name: 'projects' }" class="nav-link">
            Projects
          </nuxt-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style></style>
