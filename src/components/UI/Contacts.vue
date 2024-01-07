<template>
    <CategoryName category-name='Контакты' />

    <ul class="contacts__ul">
        <li class="contacts__li" v-for="contact in contacts" :key="contact.alt">
            <img class="contacts__svg" :src="contact.img" :alt="contact.alt">
            {{ contact.text }}
        </li>

    </ul>
</template>
  
<script>

import CategoryName from './CategoryName.vue'


export default {

    name: 'HeaderVue',
    data() {
        return {
            contacts: [
                {
                    img: '../../img/phone-default.svg',
                    text: '+7(963) 036-60-77',
                    alt: 'phone'
                },
                {
                    img: '../../img/mail-default.svg',
                    text: 'flamros@yandex.ru',
                    alt: 'mail'
                }
            ]

        }
    },
    components: {
        CategoryName

    },
}
</script>