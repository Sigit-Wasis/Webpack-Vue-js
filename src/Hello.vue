<template>
    <div class="hello">{{ text }}</div>
</template>

<script>
export default {
  data () {
    return {
      text: 'Belajar Hello dari vue-loader!'
    }
  }
}
</script>

<style>
.hello {
  color: white;
  margin-top: 10px;
  padding: 10px;
  background-color: green;
}
</style>