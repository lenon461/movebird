<template>
  <div class="hello">
    <h1>{{ msg }}wd</h1>
    <glide>dd</glide>
  </div>
</template>

<script>
import GlideVue from '../components/Glide'

export default {
  name: 'HelloWorld',
  components: {
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components : {
    'Glide' : GlideVue,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
