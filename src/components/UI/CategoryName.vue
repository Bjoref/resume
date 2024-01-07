<template>
    <div class="category-name__content">
        <h3 class="category-name__h3">
            {{ categoryName }}
        </h3>
    </div>
</template>
  
<script>

export default {
    name: 'CategoryName',
    props: [
        'categoryName'
    ]
}
</script>