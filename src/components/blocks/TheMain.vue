<template>
  <main class="main">
    <h1 class="main__title">Заголовок нашего приложения</h1>
    <div class="main__list">
      <CardProduct
      title = "Заголовок 1"
      description="Описание 1-го товара"/>

      <CardProduct
      title = "Заголовок 2"
      description="Описание 2-го товара"/>

      <CardProduct
      title = "Заголовок 3"
      description="Описание 3-го товара"/>

      <CardProduct
      title = "Заголовок 4"
      description="Описание 4-го товара"/>
    </div>
  </main>
</template>

<script>
import CardProduct from '@/components/elements/CardProduct.vue'

export default {
  name: 'TheMain',
  components: {
    CardProduct
  },
  props: {
  },
  setup () {
  }
}
</script>

<style lang="scss" scoped>
.main {
  padding: 50px 0;
  border: 10px solid green;
  display: flex;
  flex-direction: column;
  align-items: center;
  &__title {
    text-align: center;
    color: red
  }
  &__list {
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 20px;
    text-align: center;
    width: 50%;
  }
}
</style>
