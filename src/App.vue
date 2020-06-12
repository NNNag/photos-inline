<template>
  <div id="app">
    <div class="hello">
      <div class="name">
        <div class="letter">
          <img src="./assets/pic1.jpg">
        </div>
        <div class="letter">
          <img src="./assets/pic2.jpg">
        </div>
        <div class="letter">
          <img src="./assets/pic3.jpg">
        </div>
        <div class="letter">
          <img src="./assets/pic4.jpg">
        </div>
      </div>
    </div>
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

</script>
<style scoped>
body {
  background-color: #080808;
  padding: 0;
  margin: 0;
}
.name {
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: 100vh;
}
.photos {
  margin: 10px;
  filter: drop-shadow(0px 0px 7px rgba(150, 150, 150, .7));
  max-width: 20%;
}
images {
  max-width: 20%;
}
</style>
