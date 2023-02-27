<script>
  import CitiesList from './components/CitiesList.vue'
  import CounterButton from './components/CounterButton.vue'

  export default {
    components: {
      CitiesList,
      CounterButton
    }
  }
</script>

<template>
  <nav>
           <ul>
      <li>
        <RouterLink to="/">Hem</RouterLink>
      </li>
      <li>
        <RouterLink to="/about">Om</RouterLink>
      </li>
      <li>
        <RouterLink to="/contact">Kontakt</RouterLink>
      </li>
    </ul>
  </nav>
  <CitiesList />
  <CounterButton />
  <main>
    <RouterView />
  </main>
</template>
