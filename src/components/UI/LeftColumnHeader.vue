<template>
  <div class="header__content">
    <img class="header__img" src="../../img/user-default.svg" alt="user">
  </div>
</template>

<script>
export default {
  name: 'leftColumnHeader',
}
</script>

<style scoped>
.header__content img {
  width: 100px;
  height: 134px;
  border-radius: 15px;
}

.header__content {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px 0;
}
</style>
