<template>
  <header>
    <Header/>
  </header>
  <div class="content container" id="printJS-form">
    <LeftColumn/>
    <div class="rightColumnContent">
      <h1>
        Макаров Олег Константинович
      </h1>

      <h2>
        FRONTEND-РАЗРАБОТЧИК
      </h2>

      <ul class="info-list" style="display: flex; align-items: center;">
        <li class="info-list__item" style="margin-left: -5px;">
          <svg style="margin-right: 5px;" width="24" height="24" viewBox="0 0 800 800" fill="none"
            xmlns="http://www.w3.org/2000/svg">
            <path
              d="M400 700C516.667 580 633.333 472.547 633.333 340C633.333 207.452 528.867 100 400 100C271.134 100 166.667 207.452 166.667 340C166.667 472.547 283.333 580 400 700Z"
              stroke="var(--main-color)" stroke-width="66.6667" stroke-linecap="round" stroke-linejoin="round" />
            <path
              d="M400 433.333C455.23 433.333 500 388.563 500 333.333C500 278.105 455.23 233.333 400 233.333C344.77 233.333 300 278.105 300 333.333C300 388.563 344.77 433.333 400 433.333Z"
              stroke="var(--main-color)" stroke-width="66.6667" stroke-linecap="round" stroke-linejoin="round" />
          </svg>

          <p class="info-list__text">
            Россия, г. Екатеринбург
          </p>

        </li>

        <li class="info-list__item" style="margin-left: -5px;">
          <svg style="margin-right: 5px;" width="24" height="24" viewBox="0 0 800 800" fill="none"
            xmlns="http://www.w3.org/2000/svg">
            <path d="M400 566.667V366.667" stroke="var(--main-color)" stroke-width="50" stroke-linecap="round" />
            <path
              d="M400 233.333C418.409 233.333 433.333 248.257 433.333 266.667C433.333 285.076 418.409 300 400 300C381.59 300 366.667 285.076 366.667 266.667C366.667 248.257 381.59 233.333 400 233.333Z"
              fill="var(--main-color)" />
            <path
              d="M233.333 111.261C282.362 82.899 339.287 66.6667 400 66.6667C584.093 66.6667 733.333 215.905 733.333 400C733.333 584.093 584.093 733.333 400 733.333C215.905 733.333 66.6667 584.093 66.6667 400C66.6667 339.287 82.899 282.362 111.261 233.333"
              stroke="var(--main-color)" stroke-width="50" stroke-linecap="round" />
          </svg>

          <p class="info-list__text">
            26 лет
          </p>

        </li>

      </ul>

      <div>
        <h3 style="display: inline-flex; align-items: center;">
          <svg style="margin-right: 10px;" width="24" height="24" viewBox="0 0 668 634" fill="none"
            xmlns="http://www.w3.org/2000/svg">
            <path
              d="M234 167.333H100.667C63.8477 167.333 34 197.181 34 234V534C34 570.82 63.8477 600.667 100.667 600.667H567.333C604.153 600.667 634 570.82 634 534V234C634 197.181 604.153 167.333 567.333 167.333H434M234 167.333V100.667C234 63.8477 263.848 34 300.667 34H367.333C404.153 34 434 63.8477 434 100.667V167.333M234 167.333H434"
              stroke="var(--main-color)" stroke-width="66.6667" stroke-linecap="round" stroke-linejoin="round" />
          </svg>
          Опыт работы
        </h3>
        <hr />
      </div>


      <div style="display: flex;">
        <div style="width: 30%;">
          <p style="color: grey; font-size: 12px; margin: 0;">
            Июнь 2022 — Настоящее время
          </p>

        </div>

        <div style="width: 70%;">
          <h4 style="margin: 0;">
            СКБ-Банк, ОАО
          </h4>
          <p style="margin-top: 10px; margin-bottom: 10px">Программист</p>

          <h5 style="margin-top: 10px; margin-bottom: 10px">
            Должностные обязанности:
          </h5>

          <ul style="font-size: 13px; padding-left: 25px;">
            <li>
              Рефакторинг легаси-кода с Jquery/JS на Vue.js;
            </li>
            <li>
              Разработка решений под задачи бизнеса;
            </li>
          </ul>

          <h5>
            Достижения за последние 2 года:
          </h5>

          <ul style="font-size: 13px; padding-left: 25px;">
            <li>
              80% проекта переведено из JS на Vue.js;
            </li>
            <li>
              Реализовал собственные плагины для работы проекта, например, Zoom для просмотра Pdf в браузере;
            </li>
            <li>
              В качестве представителя It-направления учавствовал в ПИК-IT в УрФУ, г. Екатеринбург.
            </li>
          </ul>
        </div>



      </div>

      <div style="display: flex;">
        <div style="width: 30%;">
          <p style="color: grey; font-size: 12px; margin: 0;">
            Март 2022 — Июнь 2022
          </p>

        </div>

        <div style="width: 70%;">
          <h4 style="margin: 0;">
            СКБ-Банк, ОАО
          </h4>
          <p style="margin-top: 10px; margin-bottom: 10px">Младший программист</p>

          <h5 style="margin-top: 10px; margin-bottom: 10px">
            Должностные обязанности:
          </h5>

          <ul style="font-size: 13px; padding-left: 25px;">
            <li>
              Вёрстка новых блоков проекта;
            </li>
            <li>
              Ребрендинг проекта;
            </li>
            <li>
              Кроссбраузерная и адаптивная вёрстка.
            </li>
          </ul>
        </div>
      </div>

      <div>
        <h3 style="display: inline-flex; align-items: center;">
          <svg style="margin-right: 10px;" width="24" height="24" viewBox="0 0 800 800" fill="none"
            xmlns="http://www.w3.org/2000/svg">
            <path
              d="M18.3333 591H606.667C627.738 591 647.951 599.347 662.882 614.216C677.813 629.084 686.245 649.262 686.333 670.333C686.333 691.462 677.94 711.726 663 726.666C648.059 741.607 627.796 750 606.667 750H18.3333"
              stroke="var(--main-color)" stroke-width="63.6667" stroke-miterlimit="10" />
            <path d="M81.6667 591C102.567 612.173 114.505 640.586 115 670.333C114.488 700.175 102.559 728.686 81.6667 750"
              stroke="var(--main-color)" stroke-width="63.6667" stroke-miterlimit="10" />
            <path
              d="M781.667 591H193.333C172.204 591 151.941 582.607 137.001 567.666C122.06 552.726 113.667 532.462 113.667 511.333C114.103 490.495 122.688 470.657 137.582 456.075C152.475 441.493 172.49 433.329 193.333 433.333H781.667"
              stroke="var(--main-color)" stroke-width="63.6667" stroke-miterlimit="10" />
            <path
              d="M718.333 591C697.835 569.542 686.397 541.009 686.397 511.333C686.397 481.658 697.835 453.125 718.333 431.667"
              stroke="var(--main-color)" stroke-width="63.6667" stroke-miterlimit="10" />
            <path
              d="M559 246.333C559 339 495.333 481.667 400 413C304.667 479.667 241 337.667 241 246.333C241 155 336.333 113 400 179.667C463.667 111.667 559 153.333 559 246.333Z"
              stroke="var(--main-color)" stroke-width="63.6667" stroke-miterlimit="10" />
            <path d="M336.333 50C369.667 50 400 83.3333 400 145.333" stroke="var(--main-color)" stroke-width="63.6667"
              stroke-miterlimit="10" />
          </svg>

          Курсы
        </h3>
        <hr />
      </div>

      <div style="display: flex;">
        <div style="width: 30%;">
          <p style="color: grey; font-size: 12px; margin: 0;">
            2021 — 2022
          </p>

        </div>

        <div style="width: 70%;">
          <h5 style="margin-top: 10px; margin-bottom: 10px">
            Skillbox
          </h5>

          <ul style="font-size: 13px; padding: 0; list-style-type: none;">
            <li>
              Frontend-разработчик PRO 2021 (Вёрстка, JavaScript, Vue.js)
            </li>
          </ul>
        </div>
      </div>

      <div style="display: flex;">
        <div style="width: 30%;">
          <p style="color: grey; font-size: 12px; margin: 0;">
            2023
          </p>

        </div>

        <div style="width: 70%;">
          <h5 style="margin-top: 10px; margin-bottom: 10px">
            HTML Academy
          </h5>

          <ul style="font-size: 13px; padding: 0; list-style-type: none;">
            <li>
              Typescript
            </li>
          </ul>
        </div>
      </div>

      <div style="display: flex;">
        <div style="width: 30%;">
          <p style="color: grey; font-size: 12px; margin: 0;">
            2023
          </p>

        </div>

        <div style="width: 70%;">
          <h5 style="margin-top: 10px; margin-bottom: 10px">
            Skillbox
          </h5>

          <ul style="font-size: 13px; padding: 0; list-style-type: none;">
            <li>
              Typescript
            </li>
          </ul>
        </div>
      </div>

      <div>
        <h3 style="display: inline-flex; align-items: center;">
          <svg style="margin-right: 10px;" width="24" height="24" viewBox="0 0 800 800" fill="none"
            xmlns="http://www.w3.org/2000/svg">
            <path
              d="M333.333 66.6667H466.667V200H333.333V66.6667ZM233.333 233.333H566.667V300H500V733.333H433.333V533.333H366.667V733.333H300V300H233.333V233.333ZM166.667 166.667V233.333H233.333V166.667H166.667ZM166.667 166.667H100V100H166.667V166.667ZM633.333 166.667V233.333H566.667V166.667H633.333ZM633.333 166.667V100H700V166.667H633.333Z"
              fill="var(--main-color)" />
          </svg>

          О себе
        </h3>
        <hr />
      </div>

      <p style="margin: 0;">
        Умею работать в быстро меняющейся среде фронтенда — одной из самых быстроразвивающихся сфер It.
        <br>
        Сильные коммуникативные навыки, умею договариваться, что неимоверно важно при работе в команде, немного навыков
        публичных выступлений :)
        <br>
        Аналитические способности, смогу быстро обрабатывать информацию из различных источников
      </p>
    </div>
  </div>

  <button id="print" type="button" @click="this.print">
    Print Form
  </button>

  <div id="test"></div>
</template>

<script>
import LeftColumn from './components/LeftColumn.vue'
import Header from './components/Header.vue'
import html2pdf from 'html2pdf.js'

export default {
  name: 'App',
  components: {
    LeftColumn,
    Header
  },
  methods: {
    print() {

      html2pdf()

        // УСТАНОВИТЬ ПАРАМЕТРЫ
        .set({
          margin: [0, 0, 0, 0],
          filename: `MakarovOK,pdf`,
          image: { type: 'jpeg', quality: 1 },
          html2canvas: {
            dpi: 192,
            scale: 4,
            letterRendering: true,
            useCORS: true
          },
          jsPDF: { unit: 'mm', format: 'a4', orientation: 'portrait' }
        })
        // ПОЛУЧИТЬ КОНТЕНТ ИЗ РАЗДЕЛА
        .from(document.getElementById("printJS-form"))
        // СОХРАНИТЬ В ФАЙЛ
        .save();
    }
  },
  mounted() {
  }
}
</script>

<style>
#app {
  height: 297mm;
}

.content {
  display: flex;
  justify-content: space-between;
}

.leftColumnContent {
  width: 30%;
  background-color: var(--main-color);
}

.rightColumnContent {
  width: 70%;
  padding: 20px 20px 0;
}

.info-list {
  margin: 0;
  padding: 0;
  list-style-type: none;
}

.info-list__item {
  padding: 0;
  display: flex;
  align-items: center;
}

.info-list__text {
  margin: 0;
  color: grey;
}

.info-list__item:first-child {
  margin-right: 10px;
}
</style>
