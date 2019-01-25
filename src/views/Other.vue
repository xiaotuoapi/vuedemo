<template>
<div id='app1'>
<button v-if='showBtn' v-on:click='handleClick'>Click me</button>
</div>
</template>
<script>
new Vue ({
el :'#app', 
data : {
showBtn: true 
},
methods: {
  handleClick: function () {
  console.log ( 'Clicked !'); 
  }
}
})
</script> 
