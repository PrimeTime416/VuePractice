<template>
<div>
  <h1>Hello Wolrd App2</h1>
  <p>The Status is: {{status}}</p>
  <App-Server></App-Server>
  <App-Home></App-Home>
</div>
</template>

<script>
import Server from './Server/Component/Server.vue';
import Home from './Home/Component/Home.vue';
export default {
  data: function(){
    return {status: 'All Good'}
  },
  components:{
    'App-Server': Server,
    'App-Home': Home,
  }
}
</script>

<style>

</style>
