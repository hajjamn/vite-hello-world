<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: {
    AppTitle,
    AppHero
  },
  data() {
    return {
      message: 'Ciao mondo'
    }
  },
  methods: {
    sayHello() {
      console.log('Hello')
    }
  },
  mounted() {
    console.log('Mounted')
  }
}

</script>

<template>
  <AppTitle/>
  <AppHero/>
</template>

<style>

</style>