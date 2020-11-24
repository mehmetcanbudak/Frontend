<template>
  <Navbar />
  <router-view/>
  <AppFooter />
</template>

<script>
import Navbar from './components/Navbar'
import AppFooter from './components/AppFooter'
export default {
  components: {
    Navbar,
    AppFooter
    }
}
</script>

<style>
</style>