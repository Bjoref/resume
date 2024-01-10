<template>
    <ul class="right-column__info-list">
        <li class="right-column__info-item" v-for="info in infoData" :key="info.id">
            <img class="right-column__img" :src="info.img" alt="info.alt">

            <p class="right-column__text">
                {{ info.text }}
            </p>
        </li>
    </ul>
</template>
  
<script>


export default {
    name: 'InfoIcon',
    props: [
        'infoData'
    ]

}
</script>
  
<style></style>
  