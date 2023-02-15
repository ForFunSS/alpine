<template>
  <blockHeader></blockHeader>
  <block1></block1>
</template>

<script>
import blockHeader from './components/blockHeader'
import mainPage from './components/mainPage.vue'

export default {
  name: 'App',
  components: {
    "blockHeader": blockHeader,
    "block1": mainPage,
  }
}
</script>

<style>

</style>
