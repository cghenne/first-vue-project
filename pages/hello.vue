<template>
  <section class="container">
    <div class="hello">
      <app-logo/>
      <div>This is the hello page</div>
      <a href="/">Return to the index page</a>

      <div>
        <h4>This is an image added in the html</h4>
        <img src="~/assets/images/super-beach.jpeg" width="400"/>
      </div>

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
