<template>

  <div id="app">
    <div id="headerimgback">
      <img id="headerimg" src="https://wcms18.nodehill.se/wp-content/uploads/2019/01/mobleralla.png">
    </div>    
    <div id="nav">      
      <router-link to="/">Home</router-link> |      
      <router-link to="/kontor">Kontor</router-link> |
      <router-link to="/sovrum">Sovrum</router-link> |
      <router-link to="/vardagsrum">Vardagsrum</router-link> |
      <router-link to="/kok">Kök</router-link> 
    </div>
    
  <router-view/>
  </div>

 

</template>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  padding-top: 10px;
  padding-bottom: 20px;
  background-color: #d8f1fc;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
img#headerimg{
  height:10%;
  width:10%;
}
#headerimgback{
  width:100%;
  background-color: #d8f1fc;
}

#group{
  margin-top: 15px;
}

export default {
    name: 'app'
  }

</style>
