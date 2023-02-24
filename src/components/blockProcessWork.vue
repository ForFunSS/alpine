<template>
  <div class="cont-arrow">
    <div class="arrow-down">
      <div class="r1"></div>
      <div class="r2"></div>
      <div class="r3"></div>
    </div>
  </div>
  <div class="wrap-cont2">
    <div class="container">
      <h2 class="center">Процесс работы</h2>
      <div class="block-process-work">
        <div class="el" v-for="(elem, index) in dataElem">
          <div class="div-float-number unselect">
            {{ index + 1 }}
          </div>
          <div class="div-main-cont">
            <div class="header-text">
              <div class="desc-text">
                {{ elem.textDesc }}
              </div>
              <div class="desc-img">
                <img src="../../src/assets/images/ico-car.svg" alt="">
              </div>
            </div>
            <div class="sub-desc">
              <div class="text">
                {{ elem.fullDesc }}
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="first-step">
        <div class="div-elems-step">
          <div class="dt dt1">
            <div class="div-text">
              подберём наилучшее <br>
              решение для вас
            </div>
            <div class="elem-after right">
              Инженер бесплатно приедет <br>
              на ваш объект для подробного <br>
              изучения и оценки
            </div>
            <div class="elem-after right">
              Подберем оборудование <br>
              под ваш бюджет и оперативно <br>
              вышлем предложение
            </div>
          </div>
          <div class="dt dt2">
            <div class="div-text div-text-2">
              сделать первый шаг
            </div>
            <a href="" class="btn">
              вызвать инженера
            </a>
          </div>
          <div class="dt dt3">
            <div class="div-text">
              гарантия на оборудование<br>
              и монтаж до 5 лет
            </div>
            <div class="elem-after left">
              Гарантию прописываем в договоре
            </div>
            <div class="elem-after left">
              Имеем собственный сервис но-гарантийный отдел
          </div>
        </div>
      </div>
    </div>
  </div>
<!--    <div class="overflow-rect">-->
<!--      <div class="block-rectangle"></div>-->
<!--    </div>-->
  </div>
</template>
<script>
import elemPrev from "@/components/mainPageComponents/elementModalPresentation";

export default {
  components: {
    "elem-prev": elemPrev,
  },
  data() {
    return{
      dataElem: [
        { textDesc: "первый шаг это\n" + "выезд инженера" ,sourceImage: '../assets/images/ico-key.svg' ,fullDesc: "Инженер выезжает на объект\n" + "для осмотра помещений\n" + "и подробного изучения задачи"},
        { textDesc: "ТЕХНИЧЕСКОЕ\n" + "ЗАДАНИЕ" ,sourceImage: '../assets/images/ico-key.svg' ,fullDesc: "Составляем техническое задание\n" + "под задачу с учетом ваших\n" + "пожеланий по расположению оборудования "},
        { textDesc: "СОСТАВЛЕНИЕ\n" + "СМЕТЫ" ,sourceImage: '../assets/images/ico-key.svg' ,fullDesc: "Подбираем несколько вариантовоборудования и формируемподробную смету"},
        { textDesc: "ЗАКЛЮЧЕНИЕ\n" + "ДОГОВОРА" ,sourceImage: '../assets/images/ico-key.svg' ,fullDesc: "Заключаем договор,\n" + "прописываем гарантию,\n" + "отвественность, сроки и окончательную цену\n" + "за ваш проект"},
        { textDesc: "РАЗРАБОТКА\n"+ "ПРОЕКТА" ,sourceImage: '../assets/images/ico-key.svg' ,fullDesc: "Разрабатываем проект\n" + "по техническому заданию\n" + "под контролем главного\n" + "инженера"},
        { textDesc: "ПОСТАВКА\n" + "И МОНТАЖ" ,sourceImage: '..Доставляем материалы\n' + 'и оборудование на объект\n' + 'и приступаем к монтажу' ,fullDesc: "Инженер выезжает на объект\n" + "Доставляем материалы\n" + "и оборудование на объект\n" + "и приступаем к монтажу"},
        { textDesc: "ВЫВОЗ\n" + "МУСОРА" ,sourceImage: '../assets/images/ico-key.svg' ,fullDesc: "Монтажные работы\n" + "сопровождаются\n" + "большим количеством мусора.\n" + "Вывозим весь строительный\n" + "мусор после себя"},
        { textDesc: "ЗАПУСК\n" + "СИСТЕМЫ" ,sourceImage: '../assets/images/ico-key.svg' ,fullDesc: "Производим пуско-наладочные \n" + "работы и тестирование системы. \n" + "Вводим систему в эксплуатацию"},
        { textDesc: "ГАРАНТИЙНО\n" +"И СЕРВИСНОЕ\n" + "ОБСЛУЖИВАНИЕ" ,sourceImage: '../assets/images/ico-key.svg' ,fullDesc: "Сервисный отдел поддерживает\n" + "безотказную работу\n" + "оборудования"},
      ]
    }
  }
}
</script>