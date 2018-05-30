<template>
  <section class="container">
    <div class="index">
      <app-logo/>
      <h1 class="title">
        first-vue-project
      </h1>
      <h2 class="subtitle">
        first vue project with nuxtjs
      </h2>
      <div>This is the index page</div>
      <a href="/hello">Go to the hello page</a>
      <small>(if you hover this you'll see an image added in the css)</small>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>
