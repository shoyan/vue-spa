<template>
  <div class="home">
    <div class="circle"></div>
  </div>
</template>

<script>
import { gsap } from "gsap";
export default {
  name: 'Home',
  mounted: function() {
    gsap.to('.circle', {x: 500, duration: 3})
  },
}
</script>

<style scoped>
div{
  margin-top: 10em
}

.circle{
  background-color:red;
  height: 5em;
  width: 5em;
  border-radius: 100%
}
</style>
