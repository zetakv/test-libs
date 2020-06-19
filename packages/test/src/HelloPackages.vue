<template>
  <div>
    hello packages {{ textKey }}
  </div>
</template>

<script>
export default {
  name: 'hello-packages',
  props: {
    textKey: {
      type: String,
      default: ''
    }
  }
}
</script>

<style>

</style>
