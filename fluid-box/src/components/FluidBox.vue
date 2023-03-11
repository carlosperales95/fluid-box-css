<template>

  <div class="mainBox">
        <div class="smallBox">
        
        </div>
        <h1><b>{{ title }}</b></h1>
        <p>{{ msg }}</p>
    </div>
</template>

<script>
export default {
  name: 'FluidBox',
  props: {
    title: String,
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
