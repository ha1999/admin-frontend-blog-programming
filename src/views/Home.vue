<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <SideBar />
    <Card />
    <vs-button>Active</vs-button>
  </div>
</template>

<script>
// @ is an alias to /src
import Card from "@/components/Card.vue"
import SideBar from "@/components/SideBar.vue"
export default {
  name: "Home",
  components: {
    Card,
    SideBar
  },
}
</script>
