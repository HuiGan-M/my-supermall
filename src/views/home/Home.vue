<template>
  <div id="home">
    <nav-bar class="home-nav">
      <div slot="center">女人的衣柜</div>
    </nav-bar>
  </div>
</template>

<script>
import NavBar from "components/common/navbar/NavBar";
export default {
  name: "Home",
  components: {
    NavBar
  }
};
</script>

<style scoped>
.home-nav {
  background-color: var(--color-tint);
}
</style>
