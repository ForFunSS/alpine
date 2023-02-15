<template>
  <div class="wrap-cont1">
    <div class="container">
      <h2 class="center">Объекты с которыми мы работаем</h2>
      <div class="div-line"></div>
      <div class="block-projects">
        <elem-prev v-for="elem in projData" :sourceImg="elem.sourceImage" :sourceName="elem.sourceName"/>
      </div>
    </div>
  </div>
</template>
<script>
  import elemPrev from './mainPageComponents/elementModalPresentation.vue'

  export default {
    components: {
      "elem-prev": elemPrev,
    },
    data() {
      return{
        projData: [
          { sourceImage: 'https://placekitten.com/200/200', sourceName: 'ca dad asd q232 bw '},
          { sourceImage: 'https://placekitten.com/200/200', sourceName: 'lorem asd aseq23'},
          { sourceImage: 'https://placekitten.com/100/200', sourceName: 'asd 23 4rawse eq2'},
          { sourceImage: 'https://placekitten.com/2400/200', sourceName: 'ca dad asd q232 bw '},
          { sourceImage: 'https://placekitten.com/500/200', sourceName: 'lorem asd aseq23'},
          { sourceImage: 'https://placekitten.com/100/200', sourceName: 'asd 23 4rawse eq2'},
        ]
      }
    }
  }
</script>
<styles>

</styles>