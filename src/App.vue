<template>
  <h1>hi {{name}} </h1>
  <div v-text="x"></div>
  <div v-html="y"></div>
  <div v-html="hack"></div>
  <h1 v-bind:id="heading">Heading</h1>
  <dir></dir>
</template>
<script>

export default {
  name: 'App',
  data(){
    return{
      name:'ashutosh',
      x: 'Python',
      y: '<b>Django</b>',
      z: 'rest',
      hack: '<a href="#" onclick="alert("aklsdfhkja akjsdhd")">Click here</a>',
      heading: 'hading'
    };
  },

};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #23e715;
  margin-top: 60px;
  
}
</style>
