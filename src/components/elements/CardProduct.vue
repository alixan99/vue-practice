<template>
  <div class="card">
    <h2 class="card__title">{{ title }}</h2>
    <p class="card__description"> {{description }}</p>
    <ButtonUi name="купить"/>
  </div>
</template>

<script>
import ButtonUi from '@/components/ui/ButtonUi.vue'

export default {
  name: 'CardProduct',
  components: {
    ButtonUi
  },
  props: {
    title: {
      type: String,
      default: ''
    },
    description: {
      type: String,
      default: ''
    }
  },
  setup () {
  }
}
</script>

<style lang="scss" scoped>
.card {
  border: 1px solid green;
}
</style>
