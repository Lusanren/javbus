<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Javbus for App is a Free App
	  <br>
 
    </p>
    <h3>Install to IOS</h3>
    <ul>
      <li><a href="javascript:return false;" target="_blank" rel="noopener">No download ,Testting</a></li>
    </ul>
   <h3>Install to Android</h3>
    <ul>
      
    </ul>
   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
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
