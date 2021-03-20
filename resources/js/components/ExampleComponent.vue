<template>
  <div>
      <p>{{title}}</p>
  </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'こんにちは'
        }
    },
}
</script>

<style scoped>
div p {
    background-color: red;
    font-size: 19px;
}

</style>