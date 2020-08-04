<template>
    <div class="header">
       <div class="logo">logo</div> 
       <div class="nav">
        <a href="javascrpt:;">nav1</a>
        <a href="javascrpt:;">nav2</a>
        <a href="javascrpt:;">nav3</a>
       </div>
    </div>
</template>
<script lang="ts">
export default {
    
}
</script>

<style lang="scss" scoped>

.header{
    position: fixed;
    z-index: 20;
    top: 0;
    left: 0;
    right: 0;
    height: 3.6rem;
    background-color: #fff;
    box-sizing: border-box;
    border-bottom: 1px solid #eaecef;
    display: flex;
    padding: 10px 40px;
    justify-content: space-between;

    .nav{
        a{
            display: inline-block;

        }
    }
}
</style>