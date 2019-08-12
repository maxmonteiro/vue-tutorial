<template>
  <div id="app">
     <section class="hero is-primary is-bold is-fullheight">
      <!-- header -->
      <div class="hero-head">
        <nav class="navbar">
          <div class="container">
            <div class="navbar-brand">
              <a class="navbar-item">VueJs Tutorial 1.0</a>
            </div>
          </div>
        </nav>
      </div>

      <!-- content -->
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">{{msg}}</h1>
        </div>
      </div>

      <!-- footer -->
      <div class="hero-foot">
        <div class="container">
          <div class="content has-text-centered">
            <p>
              <strong>VueJS Tutorial</strong> by <a href="http://github.com/maxmonteiro">Máximo Monteiro</a>.
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Hello, World!'
    }
  }
}
</script>

<style>
</style>
