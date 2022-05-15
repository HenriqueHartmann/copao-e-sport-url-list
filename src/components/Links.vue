<template>
  <div>
    <div class="body">
      <b-list-group>
        <b-list-group-item variant="info" class="link-item">
          <b-row align-v="center">
            <b-col sm="12" md="4">
              <b-img :src="lolImg" width="50"></b-img>
            </b-col>
            <b-col sm="12" md="4" class="link-title"> LOL </b-col>
            <b-col sm="12" md="4" class="link-button">
              <b-button :href="lolLink" variant="primary"
                >Acessar</b-button
              ></b-col
            >
          </b-row>
        </b-list-group-item>

        <b-list-group-item variant="warning" class="link-item">
          <b-row align-v="center">
            <b-col sm="12" md="4">
              <b-img :src="csImg" width="50"></b-img>
            </b-col>
            <b-col sm="12" md="4" class="link-title"> CSGO</b-col>
            <b-col sm="12" md="4" class="link-button">
              <b-button :href="csLink" variant="primary"
                >Acessar</b-button
              ></b-col
            >
          </b-row>
        </b-list-group-item>

        <b-list-group-item>
          <b-row align-v="center">
            <b-col sm="12" md="4">
              <b-img :src="discordImg" width="50"></b-img>
            </b-col>
            <b-col sm="12" md="4" class="link-title"> Discord</b-col>
            <b-col sm="12" md="4" class="link-button">
              <b-button :href="discordLink" variant="primary"
                >Acessar</b-button
              ></b-col
            >
          </b-row>
        </b-list-group-item>

        <b-list-group-item class="link-item">
          <b-row align-v="center">
            <b-col sm="12" md="4">
              <b-img :src="instagramImg" width="50"></b-img>
            </b-col>
            <b-col sm="12" md="4" class="link-title"> Instagram</b-col>
            <b-col sm="12" md="4" class="link-button">
              <b-button :href="instagramLink" variant="primary"
                >Acessar</b-button
              ></b-col
            >
          </b-row>
        </b-list-group-item>

        <b-list-group-item>
          <b-row align-v="center">
            <b-col sm="12" md="4">
              <b-img :src="twitterImg" width="50"></b-img>
            </b-col>
            <b-col sm="12" md="4" class="link-title"> Twitter</b-col>
            <b-col sm="12" md="4" class="link-button">
              <b-button :href="twitterLink" variant="primary"
                >Acessar</b-button
              ></b-col
            >
          </b-row>
        </b-list-group-item>

        <b-list-group-item>
          <b-row align-v="center">
            <b-col sm="12" md="4">
              <b-img :src="twitchImg" width="50"></b-img>
            </b-col>
            <b-col sm="12" md="4" class="link-title"> Twitch</b-col>
            <b-col sm="12" md="4" class="link-button">
              <b-button :href="twitchLink" variant="primary"
                >Acessar</b-button
              ></b-col
            >
          </b-row>
        </b-list-group-item>

        <b-list-group-item>
          <b-row align-v="center">
            <b-col sm="12" md="4">
              <b-img :src="youtubeImg" width="50"></b-img>
            </b-col>
            <b-col sm="12" md="4" class="link-title"> Youtube</b-col>
            <b-col sm="12" md="4" class="link-button">
              <b-button :href="youtubeLink" variant="primary"
                >Acessar</b-button
              ></b-col
            >
          </b-row>
        </b-list-group-item>
      </b-list-group>
    </div>
  </div>
</template>

<script>
export default {
  name: "Links",
  data() {
    return {
      csImg: require("../assets/csgo.png"),
      lolImg: require("../assets/lol.png"),
      instagramImg: require("../assets/instagram.png"),
      twitterImg: require("../assets/twitter.png"),
      twitchImg: require("../assets/twitch.png"),
      youtubeImg: require("../assets/youtube.png"),
      discordImg: require("../assets/discordia.png"),

      csLink: "https://forms.gle/RpksTXWzUTq7Wq9n9",
      lolLink: "https://forms.gle/nipbTKesnEKwfYew6",
      instagramLink: "https://www.instagram.com/copaoifc/",
      twitterLink: "https://twitter.com/Copaoifc2022",
      twitchLink: "https://www.twitch.tv/copaoesportsifc",
      youtubeLink: "https://www.youtube.com/channel/UCLn3EBtAY09Mb-JGLyCu1aw",
      discordLink: "https://discord.com/invite/q7yekFPEex",
    };
  },
};
</script>

<style>
.body {
  margin: 0 auto 0 auto;
  width: 55%;
}
.link-title {
  font-family: Holigan;
  font-size: 1.8rem;
}

@media only screen and (max-width: 950px) {
  /* For mobile phones: */
  .body {
    width: 100%;
  }

  .link-title {
    font-size: 2.3rem;
  }
}

@media only screen and (max-width: 768px) {
  /* For mobile phones: */
  .body {
    width: 100%;
  }
  .link-title {
    margin: 0.5rem auto 1rem auto;
  }
}

@font-face {
  font-family: "Holigan";
  src: local("Holigan"), url(../assets/fonts/HOLIGAN.ttf) format("truetype");
}

@font-face {
  font-family: "Uncle";
  src: local("Uncle"),
    url(../assets/fonts/UnclefarmsRegular.ttf) format("truetype");
}
</style>
