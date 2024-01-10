<template>
    <div class="right-column__content">
        <h1 class="right-column__name">
            {{ name }}
        </h1>

        <h2 class="right-column__job-title">
            {{ jobTitle }}
        </h2>

        <InfoIcons :info-data="infoData" />

        <InfoBlock
            :block-info="blockInfoWork"
        />

        <InfoBlockContent
            time='Июнь 2022 — Настоящее время'
            :work-list="lastWorkList"
            :job-responsibilities="lastJobResponsibilities"
        />

        <InfoBlockContent
            time='Март 2022 — Июнь 2022'
            :work-list="workList"
            :job-responsibilities="jobResponsibilities"
        />

        <InfoBlock
            :block-info="blockInfoCourses"
        />

        <InfoBlockContent
            :courses = 'courses'
        />


        <InfoBlock
            :block-info="blockInfoAbout"
        />

        <p class="right-column__about-text">
            Умею работать в постоянно меняющейся среде фронтенда — одной из самых быстроразвивающихся сфер It.
            Сильные коммуникативные навыки, умею договариваться, что неимоверно важно при работе в команде, немного навыков
            публичных выступлений :)
            Аналитические способности, смогу быстро обрабатывать информацию из различных источников
        </p>
    </div>
</template>
  
<script>

import InfoIcons from './UI/InfoIcons.vue'
import InfoBlock from './InfoBlock.vue'
import InfoBlockContent from './UI/InfoBlockContent.vue'


export default {
    name: 'RightColumn',
    components: {
        InfoIcons,
        InfoBlock,
        InfoBlockContent

    },
    props: [
        'name',
        'jobTitle'
    ],
    data() {
        return {
            courses: [
                {
                    time: '2021 — 2022',
                    courseName: 'Skillbox',
                    cousrseText: 'Frontend-разработчик PRO 2021 (Вёрстка, JavaScript, Vue.js)',
                    id: 1
                },
                {
                    time: '2023',
                    courseName: 'HTML Academy',
                    cousrseText: 'Typescript',
                    id: 2
                },
                {
                    time: '2023',
                    courseName: 'Skillbox',
                    cousrseText: 'Typescript',
                    id: 3
                }
            ],
            
            blockInfoWork: {
                'text': 'Опыт работы',
                'img': '../../img/work.svg',
                'alt': 'work',
                'id': 1,
                'exp': '1 год 11 месяцев'
            },
            blockInfoCourses: {
                'text': 'Курсы',
                'img': '../../img/courses.svg',
                'alt': 'courses',
                'id': 2,
            },
            blockInfoAbout: {
                'text': 'О себе',
                'img': '../../img/about.svg',
                'alt': 'about',
                'id': 3,
            },
            infoData: [
                {
                    text: 'Россия, г. Екатеринбург',
                    img: '../../img/location-default.svg',
                    alt: 'location',
                    id: 1
                },
                {
                    text: '26 лет',
                    img: '../../img/age-default.svg',
                    alt: 'age',
                    id: 2
                },
            ],
            lastWorkList: {
                workName: 'СКБ-Банк, ОАО',
                jobTitle: 'Программист',
                responsibilitiesTitle: 'Должностные обязанности',
                achievements: {
                    achievementsTitle: 'Достижения за последние 2 года:',
                    achievementsText: [
                        '80% проекта переведено из JS на Vue.js;',
                        'Реализовал собственные плагины для работы проекта, например, Zoom для просмотра Pdf в браузере;',
                        'В качестве представителя It-направления учавствовал в ПИК-IT в УрФУ, г. Екатеринбург.'
                    ]
                }
            },
            workList: {
                workName: 'СКБ-Банк, ОАО',
                jobTitle: 'Младший программист',
                responsibilitiesTitle: 'Должностные обязанности',
            },
            lastJobResponsibilities: [
                'Рефакторинг легаси-кода с Jquery/JS на Vue.js;',
                'Разработка решений под задачи бизнеса;'
            ],
            jobResponsibilities: [
                'Вёрстка новых блоков проекта;',
                'Ребрендинг проекта;',
                'Кроссбраузерная и адаптивная вёрстка.'
            ],

        }
    },
    methods: {
        monthDiff(dateFrom, dateTo) {
            console.log( dateTo.getMonth() - dateFrom.getMonth() +
                (12 * (dateTo.getFullYear() - dateFrom.getFullYear())))
            return dateTo.getMonth() - dateFrom.getMonth() +
                (12 * (dateTo.getFullYear() - dateFrom.getFullYear()))
        }

    },
    mounted() {
        this.monthDiff(
            new Date(2022, 3, 1),
            new Date(2024, 1, 8)  // 08/01/2024
        )
    }
}
</script>
  
<style></style>
  