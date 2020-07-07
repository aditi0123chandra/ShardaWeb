<template>
  <div id="app">
    <br><br>
    <img id="image" height="80" width="300" src="./assets/shardalogo.png"/>
    <br><br>
    <h3>SCHOOL OF ENGINEERING AND TECHNOLOGY</h3> <br>
    <h3>PRESENTS</h3> <br>
    <p><img height="70" width="70" src="./assets/books.png"/> LEARNSHALA</p> 
    <a href="#">Where learning never stops!</a><br><br>
    <button>Enter Learnshala</button>
    <Sidebar/>
    
  </div>
</template>

<script>
  import Sidebar from './components/sidebar.vue'

  export default {
    components: {
      Sidebar
    }
  }
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Anton');
  @import url('https://use.fontawesome.com/releases/v5.8.2/css/all.css');

  body {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: 'Anton', Arial, Helvetica, sans-serif;
    font-size: 1rem;
    letter-spacing: 1px;
    color: #322F42;
    width: 100%;
    min-height: 100vh;
    background: #0627F0;
    background-size: cover;
    overflow: hidden;
    text-align: center;
  }
  #app h3{
    color: #fff;
  }
  #app p{
    color: #fff;
    font-size: 30px;
  }
  #app a{
    color: #fff;
  }
  #app button{
    background: #fff;
    border: 2px solid white;
    border-radius: 4px;
  }
  #app #image{
    background: white;
  }
</style>
