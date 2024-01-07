<template>
    <CategoryName :category-name='categoryName' />

    <ul class="skills__ul">
        <li v-for="skill in skills" :key="skill.text">
            {{ skill.text }}
        </li>
    </ul>
</template>
  
<script>
import CategoryName from './CategoryName.vue'

export default {
    name: 'SkillsVue',
    components: {
        CategoryName
    },
    props: [
        'skills',
        'categoryName'
    ],
}
</script>
  
<style></style>
  