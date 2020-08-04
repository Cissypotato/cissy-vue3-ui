<template>
  <div>
  <div>
  
   <router-link to='/'>a</router-link> |
   <router-link to='/hello'>b</router-link>
  </div>
  <router-view></router-view>
  </div>
 
</template>

<script>


export default {
  name: 'App',
  components: {
   
  }
}
</script>
