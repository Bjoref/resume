<template>
    <div>
        <h3 class="info-block__h3">
            <img class="info-block__icon" :src="data.img" :alt="data.alt">
            {{ data.text }} <span class="info-block__span" v-if="data.exp"> {{ data.exp }}</span>
        </h3>
        <hr />
    </div>
</template>
  
<script>


export default {
    name: 'InfoBlockHeader',
    components: {

    },
    props: [
        'data'
    ],
}
</script>
  
<style></style>
  