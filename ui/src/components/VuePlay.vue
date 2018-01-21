<template>
  <div class="vue-play">
    <nav>
      <a class="java" href="https://java.com/en/">
        <img width="450" height="300"  :src="logos.javaLogo" alt="Java Logo" />
      </a>
      <a class="play" href="https://www.playframework.com/">
        <img width="400" height="400" :src="logos.playLogo" alt="Play Framework Logo" />
      </a>
      <a class="vue" href="https://vuejs.org/">
        <img class="App-logo" width="400" height="400" :src="logos.vueLogo" alt="Vue Logo" />
      </a>
    </nav>
    <div>
      <h2>Check out the project on GitHub for more information</h2>
      <h3>
        <a target="_blank" href="https://github.com/duncannevin/java-play-vue-seed">
          java-play-vue-seed
        </a>
      </h3>
      <h2>Project based on java-play-react-seed by <a href="https://github.com/yohangz">Yohan Gomez</a></h2>
      <a target="_blank" href="https://github.com/yohangz/java-play-react-seed">
        java-play-react-seed
      </a>
    </div>
  </div>
</template>
<script>
  import assets from '../assets'
  export default {
    computed: {
      logos () {
        return assets
      }
    }
  }
</script>
