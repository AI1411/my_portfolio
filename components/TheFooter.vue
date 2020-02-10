<template>
  <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <nuxt-link to="/">
            Home
          </nuxt-link>
          <nuxt-link to="/about">
            About Me
          </nuxt-link>
          <nuxt-link to="/work">
            Work
          </nuxt-link>
          <nuxt-link to="/contact">
            Contact
          </nuxt-link>
        </p>
        <p>
          <a href="">
            <i class="fab fa-twitter-square fa-2x"></i>
          </a>
          <a href="https://github.com/AI1411" target="_blank">
            <i class="fab fa-github fa-2x"></i>
          </a>
        </p>
      </div>
  </footer>
</template>

<script>
    export default {
        name: "TheFooter"
    }
</script>

<style scoped>
footer.container{
  max-height: 100px;
}
  a {
    padding: 5px;
  }
</style>
