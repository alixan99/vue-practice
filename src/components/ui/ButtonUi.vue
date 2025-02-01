<template>
  <button class="button">{{ name }}</button>
</template>

<script>

export default {
  name: 'ButtonUi',
  components: {
  },
  props: {
    name: {
      type: String,
      default: ''
    }
  },
  setup () {
  }
}
</script>

<style lang="scss" scoped>
.button {
  background-color: orange;
  padding: 5px 15px;
  color: red;
}
</style>
