<template>
  <button @click="count++">Eat it</button>
  <p>Asses eaten: {{ count }}</p>
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
