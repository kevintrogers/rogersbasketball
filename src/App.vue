<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>
  <v-container>
  <h1 class="justify-center text-h1">Basketball Info</h1>

  <v-card class="pa-6">
    <v-card-title>
      How to use this site
    </v-card-title>
    <v-card-content>
      The video cards are color-coded. The lightest shade of green is the most basic, getting more 
      advanced as the background darkens.
    </v-card-content>
  </v-card>

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
        <v-card color="green-accent-1"><iframe src="https://www.youtube.com/embed/h53iVteBwJ4?si=m7GH_E5AIZc80STL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        <v-card-text>Add arc to your jumpshot for greater accuracy</v-card-text>
      </v-card>
      <v-card color="green-accent-3"><iframe src="https://www.youtube.com/embed/hkfQXij2kp4?si=OsRhoeOlAtToxzJQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <v-card-text>How to dribble between your legs in 5 simple steps.</v-card-text>
    </v-card>
        </ul> 
      </div> 
      <div class="">
        <h2 class="justify-center text-h2">Dribble Drive Motion Offense</h2>

        <v-card class="pa-6 mx-4">
          <v-card-content >
            <p>The motion offense teaches kids the fundamentals of basketball and gets the whole team involved which is why I like to use it.
              There is an animation of the basic structure of the movement patterns below, but first a few rules to help guide the players.
            </p>
            <ol class="mx-8">
              <li>Make the defense work.</li>
              <li>An action after very pass (basket cut, ball screen, off-ball screen)</li>
              <li>Be aggressive, but only take open shots.</li>
              <li>Everybody is dangerous.</li>
              <li>3-4 seconds with the ball and then pass or shoot</li>
            </ol>
          </v-card-content>
        </v-card>
        <ul>

            <p class="text-high-emphasis">Click Play animation to see the Motion Offense in action.</p>
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
            <v-card color="green-accent-2"><iframe  src="https://www.youtube.com/embed/CTnSABsyzIE?si=vuLoa-WoGpRGB_RR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <v-card-text>Learn the proper technique for setting a screen</v-card-text></v-card>
        </ul>
      </div>
    </div>
</v-container>
</template>
<style scoped>

</style>
