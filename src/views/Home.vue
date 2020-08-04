<template>
    <div>
       <topbar/>
       <div class="content">
       <div class="mian">
        <h1>cissy-ui</h1>
         <h2>最好看的ui</h2>
         <div>
          <a href="">github</a>
          <a href="">开始</a>
         </div>
        </div>
       </div>
        
        
    </div>
</template>
<script lang="ts">
import Topbar from '../components/Topbar.vue'

export default {
    name:"Home",
    components:{
       Topbar
    }
}
</script>

<style lang="scss" scoped>

</style>
