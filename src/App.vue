<template>
  <v-app>
    <v-card>
      <v-app-bar app color="#121212" dark elevation="5" outlined height="60vh">
        <div class="d-flex align-center">
          <v-img
            alt="My_Logo"
            class="shrink mr-2"
            contain
            src="./assets/ava.png"
            transition="scale-transition"
            width="40"
          />
        </div>

        <v-spacer></v-spacer>

        <span>
          С днем учителя, Максим Кадомцев, всей группой желаем, чтобы у Вас были хорошие ученики!
        </span>
        
        <v-spacer></v-spacer>

        <v-btn
          href="https://vk.com/id223595943"
          target="_blank"
          text
        >
          <span class="mr-2">Ваш вк</span>
          <v-icon>mdi-open-in-new</v-icon>
        </v-btn>
      </v-app-bar>
    </v-card>

    
    <v-main>
      <SliderController/>
    </v-main>
    
    
    <v-app-bar
    elevation="24" dark
    >
      <v-spacer></v-spacer>
      <v-btn
      href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"
      >
        <span>Поздравление на Youtube</span>

        <v-icon>mdi-youtube</v-icon>
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn>
        <span>Эта кнопка ничего не делает</span>

        <v-icon>mdi-message</v-icon>
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn
      href="https://www.youtube.com/watch?v=76wzB8-GB98"
      >
        <span>Поздравительная музыка</span>

        <v-icon>mdi-spotify</v-icon>
      </v-btn>
      <v-spacer></v-spacer>
    </v-app-bar>

  </v-app>
</template>

<script>
import SliderController from './components/SliderController';

export default {
  name: 'App',

  components: {
    SliderController,
},

  data: () => ({
    value: 'recent'
  }),
};
</script>

<style>
  main { 
    background-color: #000000; 
  }
</style>
