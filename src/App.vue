<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>
  <v-container>
  <h1 class="justify-center text-h1">Basketball Info</h1>
 

    <div class="w-full">
      <!-- <AppMenu /> -->
      <!-- <router-view /> -->
      <div class=" justify-center">
        <h2 class="text-h2">Fundamental Skills</h2>
        <ul class="videolist ga-3">
<!--   
          <li class="">
            <v-card :variant="elevated">
              <v-card-headline></v-card-headline>
              <v-card-actions>
      <v-btn
        variant="text"
        color="teal-accent-4"
        @click="reveal = true"
      >
        Learn More
      </v-btn>
    </v-card-actions>
              <v-card-item>
                 </v-card-item>
              
            </v-card>
          </li> -->
          <v-card color="green-accent-1" ><iframe src="https://www.youtube.com/embed/UGT7C7DdCYo?si=kkgYnSR1jqLrFL3w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; c v-cardpboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <v-card-text >Quick video on the fundamentals of having an accurate jumpshot.</v-card-text>
          </v-card>
          <v-card color="green-accent-1"><iframe src="https://www.youtube.com/embed/fzySl4Vqfwk?si=LYyl3s7Qk9LzSK0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; c v-cardpboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <v-card-text>How to do a crossover dribble but great tips for ball handling in general.</v-card-text>
        </v-card>
          <v-card color="green-accent-1"><iframe src="https://www.youtube.com/embed/Cvl980x11Jk?si=K-O_zWF_HlQObAGA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; c v-cardpboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <v-card-text>How to post up. A basic offensive skill for Power Forwards and Centers.</v-card-text>
        </v-card>
         <v-card color="green-accent-1" class="text-high-emphasis"><iframe src="https://www.youtube.com/embed/4tdZeJcyXf0?si=qcqyPJskHF1_NBY4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; c v-cardpboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          <v-card-text>The Drop Step is a simple, yet effective way for post players to score after posting up.</v-card-text>
        </v-card>
        </ul> 
      </div> 
      <div class="">
        <h2 class="justify-center text-h2">Strategy</h2>
        <ul>

            <p class="text-high-emphasis">Click Play animation and it will show you a video.</p>
              <iframe allow="fullscreen" style="border:0" title="Play Creator App" width="800" height="500" src='https://www.thehoopsgeek.com/react-apps/PlayCreator/embed/?code=k1VpXpZcfS&showTitle=1&showVideo=1&showDescription=1&showPhaseDescriptions=1'></iframe>
  
          </ul>
      </div> 
      <div class="w-2/3">
        <h2 class="justify-center">Attacking The Basket</h2>
        <ul class="videolist ga-3">
          <v-card color="green-accent-2"><iframe  src="https://www.youtube.com/embed/szOBT0zUIMg?si=EtOpszox1xE4WTd1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <v-card-text>How to make space and drive from the three point line.</v-card-text></v-card>
          
          <v-card color="green-accent-1"><iframe  src="https://www.youtube.com/embed/WM90iRaOZ3w?si=7dm4iS4-VtqC1m6_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          <v-card-text>Learn how to effectively use a jab step before your drive.</v-card-text></v-card>
            <v-card color="green-accent-2"><iframe src="https://www.youtube.com/embed/BKMSf3QVvAk?si=NGXSJ6gmkzjYSzUH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <v-card-text>Learn what a kick pass is and when you should use it</v-card-text></v-card>
            <v-card color="green-accent-2"><iframe  src="https://www.youtube.com/embed/HDHFyQ0DwS4?si=bXB5jiTzujGBbRYL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <v-card-text>Learn about the pullback dribble and add it your bag.</v-card-text></v-card>
        </ul>
      </div>
    </div>
</v-container>
</template>
<style scoped>

</style>
