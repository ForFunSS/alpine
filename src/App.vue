<template>
  <blockHeader></blockHeader>
  <block1></block1>
  <block2></block2>
</template>

<script>
import blockHeader from './components/blockHeader'
import mainPage from './components/mainPage.vue'
import blockProcessWork from './components/blockProcessWork.vue'

export default {
  name: 'App',
  components: {
    "blockHeader": blockHeader,
    "block1": mainPage,
    "block2": blockProcessWork,
  }
}
</script>

<style>

</style>
