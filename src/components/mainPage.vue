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
          { sourceImage: 'https://via.placeholder.com/640x360', sourceName: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit'},
          { sourceImage: 'https://via.placeholder.com/500x360', sourceName: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit3'},
          { sourceImage: 'https://via.placeholder.com/200x340', sourceName: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit2'},
          { sourceImage: 'https://via.placeholder.com/640x360', sourceName: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit'},
          { sourceImage: 'https://via.placeholder.com/2000x360', sourceName: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit'},
          { sourceImage: 'https://via.placeholder.com/640x360', sourceName: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit'},
        ]
      }
    }
  }
</script>
<styles>

</styles>