<template>
    <div class="leftColumnContent">
        <LeftColumnHeader />

        <Contacts/>

        <Skills
            category-name="Hard Skills"
            :skills="hardSkills"
        />

        <Skills
            category-name="Soft Skills"
            :skills="softSkills"
        />
    </div>
</template>
  
<script>
import LeftColumnHeader from './UI/LeftColumnHeader.vue'
import Contacts from './UI/Contacts.vue'
import Skills from './UI/Skills.vue'


export default {
    name: 'App',
    components: {
        LeftColumnHeader,
        Contacts,
        Skills
    },
    data() {
        return {
            hardSkills: [
                {
                    text: 'Английский — Разговорный/чтение документации;'
                },
                {
                    text: 'HTML5, CSS3, JS;'
                },
                {
                    text: 'Vue.js;'
                },
                {
                    text: 'Jquery;'
                },
                {
                    text: 'Saas;'
                },
                {
                    text: 'Git;'
                },
                {
                    text: 'Bootstrap;'
                },
                {
                    text: 'Typescript;'
                },
                {
                    text: 'Кроссбраузерная и адаптивная вёрстка.'
                }
            ],
            softSkills: [
                {
                    text: 'Оптимизм;'
                },
                {
                    text: 'Умение работать в команде;'
                },
                {
                    text: 'Эмпатичность.'
                },
            ]
        }
    },
}
</script>
  
<style></style>
  