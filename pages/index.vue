<template>
  <div class="container">
    <Landing />
    <About />
    <Projects />
  </div>
</template>

<script>
import Landing from '@/components/Landing'
import About from '@/components/About'
import Projects from '@/components/Projects'

export default {
  components: {
    Landing,
    About,
    Projects,
  },
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,900;1,500;1,900&display=swap');

*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
}

.container {
  display: flex;
  flex-direction: column;

  > div {
    height: 100vh;
  }
}
</style>
