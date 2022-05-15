<template>
  <div class="mb-2">
    <b-jumbotron
      header="Copão IFC E-Sports"
      lead="Links para formulários e redes sociais. Youtube e Twitch para acompanhar os jogos e Discord para contato e mais informações."
    >
    <b-img :src="logo" width="220"></b-img>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: "Links",
    data() {
    return {
      logo: require("../assets/logo/logo.png"),
    };
  },
};
</script>

<style></style>
