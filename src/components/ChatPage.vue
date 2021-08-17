<template>
  <v-container>
    <div id="example-1">
      <button v-on:click="counter += 1">+1</button>
      <p>The button above was pressed {{ counter }} time </p>
    </div>
  </v-container>

</template>

<script>
export default {

  data: () => {
    return {
      counter: 0,
      username: '',
      message: '',



      messages: [],
      intervalCtx: null,
      lastMsgID: 0,
    }

  },
}

</script>

<style scoped>

</style>