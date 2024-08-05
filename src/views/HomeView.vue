<template>
    <div>
        <Hero />
        <Video />
        <Precing />
    </div>
</template>

<script>
import Hero from '../components/Hero.vue'
import Video from '../components/Video.vue'
import Precing from '../components/Precing.vue'

export default {
  components: {
    Hero,
    Video,
    Precing
  }
};
</script>
