<template>
  <div id="app">
    <NavBar />
    <router-view/>
  </div>
</template>
<script>
import NavBar from "@/components/NavBar";
export default {
  components : {
    NavBar
  }
}
</script>
<style>
#app{text-align: center}
</style>
