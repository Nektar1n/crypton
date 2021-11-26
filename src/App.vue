<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld";

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
  #app{
    box-sizing: border-box;
    margin: 0;
  }

</style>
