<template>
    <InfoBlockHeader :data="this.blockInfo" />
</template>
  
<script>
import InfoBlockHeader from './UI/InfoBlockHeader.vue';



export default {
    name: 'InfoBlock',
    components: {
        InfoBlockHeader,
    },
    props: [
        'blockInfo'
    ],
}
</script>
  
<style></style>
  