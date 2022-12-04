<template>
  <div class="home">
    <h1>HI THERE!</h1>
    <h2>I'M GRZEGORZ</h2>
    <p>Junior FRONTEND DEVELOPER</p>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eius adipisci eaque, dolores, perspiciatis maxime nemo, cumque quasi blanditiis ipsum sint alias odio consequatur rerum excepturi autem? Neque iure impedit explicabo.</p>
    <button>More About Me</button>
    <PrimaryButton>More About Me!</PrimaryButton>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import PrimaryButton from '@/components/PrimaryButton.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    PrimaryButton
  }
}
</script>
