<template>
   <header id="site-header">
      <div class="logo">logo</div>
      <div class="navbar">navbar</div>
    </header>
</template>

<script>
export default {

}
</script>

<style lang= "scss">
#site-header {
    width: 960px;
    height: 90px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    background-color: grey;
        .logo {
            width: 90px;
            height: 90px;
            background-color: green;
        }
        .navbar {
            width: 550px;
            height: 90px;
            background-color: yellow

        }



}

</style>