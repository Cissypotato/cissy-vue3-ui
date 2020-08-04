<template>
   <div>
       <Topbar/>
        <div class="content">
        <aside>aside</aside>
        <main>mian</main>
        </div>
   </div>
</template>
<script>
import Topbar from '../components/Topbar.vue'
export default {
    name:"Doc",
    components:{
       Topbar
    }
}
</script>

<style lang="scss" scoped>

</style>
