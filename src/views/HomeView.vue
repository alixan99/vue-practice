<template>
  <div class="composition"> Главная страница приложения
    <ButtonUi name="Заказать обратный звонок"/>
    <TheMain/>
  </div>
</template>

<script>
import TheMain from '@/components/blocks/TheMain.vue'
import ButtonUi from '@/components/ui/ButtonUi.vue'

export default {
  name: 'HomeView',
  components: {
    TheMain,
    ButtonUi
  },
  props: {
  },
  setup () {
  }
}
</script>

<style lang="scss" scoped>
.composition {
  color: green;
}
</style>
