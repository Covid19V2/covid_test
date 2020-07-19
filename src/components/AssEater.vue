<template>
  <button @click="count++">Eat it</button>
  <p class="hobo1">Asses eaten: {{ count }}</p>
</template>

<script>
export default {
  name: 'AssEater',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>


<style>
  .hobo1 {
    color: white;
  }
</style>