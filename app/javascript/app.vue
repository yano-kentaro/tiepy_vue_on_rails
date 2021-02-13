<template>
  <v-app>
    <p>{{ message }}</p>

    <div><v-btn color="primary" rounded dark>hello</v-btn></div>
  </v-app>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!!"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
