<template>
  <div class="hello">
   <p>刘林凡先生&赵婉君女士结婚照</p>
    <img :src="myImg">
  </div>
</template>

<script>
import imgUrl from '@/assets/pic.jpeg'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      myImg: imgUrl
    }
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
