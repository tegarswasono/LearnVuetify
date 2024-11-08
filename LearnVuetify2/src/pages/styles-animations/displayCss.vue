<template>
  <h2>display: none:</h2>
  <div>
  Lorem ipsum dolor.... <p class="ex1">HELLO WORLD!</p> Vestibulum volutpat tellus diam....
  </div>

  <h2>display: inline:</h2>
  <div>
  Lorem ipsum dolor.... <p class="ex2">HELLO WORLD!</p> Vestibulum volutpat tellus diam....
  </div>

  <h2>display: block:</h2>
  <div>
  Lorem ipsum dolor.... <p class="ex3">HELLO WORLD!</p> Vestibulum volutpat tellus diam....
  </div>

  <h2>display: inline-block:</h2>
  <div>
  Lorem ipsum dolor.... <p class="ex4">HELLO WORLD!</p> Vestibulum volutpat tellus diam....
  </div>

  <v-divider />
  <v-img src="./inline-block0.jpg" />
  <v-img src="./inline-block.jpg" />
</template>
<style>
  p {color: red;}

  p.ex1 {display: none;}
  p.ex2 {display: inline;}
  p.ex3 {display: block;}
  p.ex4 {display: inline-block;}
</style>
