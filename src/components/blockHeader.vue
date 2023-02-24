<template>
  <div class="block-header">
    <div class="wrap-header-1">
     <div class="container container-header">
      <div class="header-nav">
        <div class="div-el">
          Объекты, с которыми мы работаем
        </div>
        <div class="div-el">
          Процесс работы
        </div>
        <div class="div-el">
          Наши клиенты
        </div>
        <div class="div-el">
          Гарантия
        </div>
        <div class="div-el">
          контакты
        </div>
      </div>
    </div>
    </div>
    <div class="wrap-header-2">
      <div class="container container-header-2">
        <div class="header-cont">
          <div class="div-logo">
            <div class="dt1">
              <img src="../../src/assets/images/logo-head.svg" alt="">
            </div>
            <div class="dt2">
              <div class="cont-el">пн-пт: <b>9:00 - 18:00</b></div>
              <div class="cont-el">сб-вс: <b>выходной</b></div>
            </div>
          </div>
          <div class="div-cont-data">
            <div class="text">
              <img src="../../src/assets/images/ico-mail-2.svg" alt="">
              г. Тверь,  пр-т Чайковского, д.28/2
            </div>
            <div class="text">
              <img src="../../src/assets/images/ico-phone-2.svg" alt="">
              klimat-tver@yandex.ru
            </div>
          </div>
          <div class="div-cont-data div-cont-data-2">
            <div class="text">
              <img src="../../src/assets/images/ico-phone-2.svg" alt="">
              +7 (4822) 64-22-00
            </div>
            <div class="text">
              <a href="tel:+74822642200">Вызвать инженера</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="wrap-header-3">
      <div class="container container-header-3"></div>
    </div>
    <div class="flex-slider">
      <sliderHeader></sliderHeader>
    </div>
  </div>
</template>
<script>
import sliderHeader from "@/components/mainPageComponents/SliderHeader"

export default {
  name: 'blockHeader',
  components: {
    "sliderHeader": sliderHeader,
  }
}
</script>