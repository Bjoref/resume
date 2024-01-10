<template>
  <header>
    <Header/>
  </header>
  <div class="content container" id="printJS-form">
    <LeftColumn/>
    
    <RightColumn
      name="Макаров Олег Константинович"
      job-title="FRONTEND-РАЗРАБОТЧИК"
    />
  </div>

  <button id="print" type="button" @click="this.print">
    Print Form
  </button>

  <div id="test"></div>
</template>

<script>
import LeftColumn from './components/LeftColumn.vue'
import RightColumn from './components/RightColumn.vue'
import Header from './components/Header.vue'
import html2pdf from 'html2pdf.js'

export default {
  name: 'App',
  components: {
    LeftColumn,
    Header,
    RightColumn
  },
  methods: {
    print() {

      html2pdf()

        // УСТАНОВИТЬ ПАРАМЕТРЫ
        .set({
          margin: [0, 0, 0, 0],
          filename: `MakarovOK`,
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