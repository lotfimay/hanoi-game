<template>
  <hanoi-game />
</template>

<script>
import HanoiGame from './components/HanoiGame.vue';

export default {
  name: 'App',
  components: {
    HanoiGame,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200;300;400;500;600;700;800&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-family: 'Nunito', sans-serif;
}

button {
  cursor: pointer;
}
p {
  font-weight: bold;
  font-size: 1.2rem;
}
</style>
