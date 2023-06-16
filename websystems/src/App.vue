<template>
  <div>
    <header-comp></header-comp>
    <div class="content">
      <text-comp></text-comp>
    </div>
  </div>
</template>

<script>
import headerComp from "@/components/headerComp.vue"
import textComp from "@/components/textComp.vue"
export default {
  name: 'App',
  components: {
    headerComp, textComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #f7d0d0;
  height: fit-content;
  min-height: 100vh;
  padding-bottom: 10px;
}

.content {
  display: flex;
  flex-direction: row;
}
</style>
