<template lang="html">
  <div class="container">
    <div class="has=-text-centered">
      <strong><h1>Contact Us</h1></strong>
    </div>
    <div class="columns">
      <div class="column">
        <div class="margin">
          <AppForm />
        </div>
      </div>
      <div class="column"></div>
    </div>
  </div>
</template>

<script>
import  AppForm from '@/components/AppForm'
export default {
  components:{
    AppForm
  }
}
</script>

<style lang="css" scoped>
  h1 {
    text-align: center;
    margin-bottom: 5%;
  }

  .margin {
    margin-bottom: 10%;
  }
</style>