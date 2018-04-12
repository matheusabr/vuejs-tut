<template>
  <div class="skills">
    <h3>{{ name }}</h3>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data () {
    return {
      name: 'Matt'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 20px 0;
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
