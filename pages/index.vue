<template>
  <section class="container">
    <div>
      <img class="profile-image" src="~/assets/images/default_avatar.png" />
      <h1 class="title">
        Dan Collins
      </h1>
      <h2 class="subtitle">
        Software Developer
      </h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green"
          >Documentation</a
        >
        <a
          href="https://github.com/dan-collins"
          target="_blank"
          class="button--grey"
        >
          <font-awesome-icon :icon="['fab', 'github']" />
        </a>
      </div>
    </div>
  </section>
</template>

<script>
/*
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
*/
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.profile-image {
  width: 30%;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
