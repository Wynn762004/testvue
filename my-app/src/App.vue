<script setup>
/*import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'*/
import navbar from './components/navbar.vue'
import card from './components/card.vue'
import items from './test.json'
</script>

<template>
<div>
  <header>
    
    <navbar />
    
    <!--<img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div> -->
  </header>

  <main>
    <div class="grid-container">
      <card v-bind="items[0]" />
      <card v-bind="items[1]" />
      <card v-bind="items[2]" />
      <card v-bind="items[3]" />
      <card v-bind="items[4]" />
      <card v-bind="items[5]" />
      <card v-bind="items[6]" />
      <card v-bind="items[7]" />
      <card v-bind="items[8]" />
      <card v-bind="items[9]" />
      <card v-bind="items[10]" />
      <card v-bind="items[11]" />
    </div>
    <!-- <card /> -->

  </main>
</div>
</template>

<style scoped>
/*header {
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
}*/
</style>
