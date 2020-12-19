<template>
  <div class="container">
    <Navbar />
    <SearchBar/>
    <MainBlock/>
    <Nuxt />
  </div>
</template>


<script>

import Navbar from "@/components/Navbar"
import SearchBar from "@/components/Header"
import MainBlock from "@/components/MainBlock"

export default {
  components: {
    Navbar,
    SearchBar,
    MainBlock
  }
}
</script>

<style>

</style>
