<template>
  <blockHeader></blockHeader>
  <block1></block1>
  <block2></block2>
  <block3></block3>
  <blockFormCallbackPhone></blockFormCallbackPhone>
</template>

<script>
import blockHeader from './components/blockHeader'
import mainPage from './components/mainPage.vue'
import blockProcessWork from './components/blockProcessWork.vue'
import blockAdvantageComp from './components/mainPageComponents/blockAdvantageComp.vue'
import blockFormCallbackPhone from './components/blockFormCallbackPhone.vue'


export default {
  name: 'App',
  components: {
    "blockHeader": blockHeader,
    "block1": mainPage,
    "block2": blockProcessWork,
    "block3": blockAdvantageComp,
    "blockFormCallbackPhone": blockFormCallbackPhone
  }
}
</script>

<style>

</style>
