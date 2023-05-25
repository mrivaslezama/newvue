<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import ArticleItem from './components/Article.vue'
</script>

<template>
  <header>
    <img alt="logo" class="logo" src="./assets/logo.png" width="420" height="375" />

    <div class="wrapper">
      <HelloWorld msg="Bienvenidos!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>

  <section>
    <ArticleItem />
  </section>

</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
