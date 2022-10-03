<template>
  <v-carousel
    height="95vh"
    hide-delimiters
  >
    <v-carousel-item
      v-for="(item, i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    >
    </v-carousel-item>
  </v-carousel>
</template>

  

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: "https://cdn.otkritkiok.ru/posts/big/s-dnem-uchitelya-gif-47777-8866353.gif",
          },
          {
            src: 'https://media.tenor.com/6En8e547Qb0AAAAd/gandalf-gandalf-araba.gif',
          },
          {
            src: 'https://c.tenor.com/CWgfFh7ozHkAAAAC/rick-astly-rick-rolled.gif',
          },
          {
            src: 'https://media.tenor.com/TbTe1Nc6j34AAAAC/hacker-hackerman.gif',
          },
        ],
      }
    },
  }
</script>