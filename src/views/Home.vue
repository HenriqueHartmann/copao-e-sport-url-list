<template>
  <div class="container vh-100">
    <b-row align-v="center">
      <Header />
    </b-row>
    <b-row class="content" align-v="center">
      <Links />
    </b-row>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Links from "@/components/Links.vue";

export default {
  name: "Home",
  components: {
    Header,
    Links,
  },
};
</script>

<style scoped>
.content {
  height: 55%;
}
</style>
