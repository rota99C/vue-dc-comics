<template>
   <header id="site-header">
      <div class="logo">
          <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <div class="navbar">
          <ul>
              <li><a>CHARACTERS</a></li>
              <li><a class="active">COMICS</a></li>
              <li><a>MOVIES</a></li>
              <li><a>TV</a></li>
              <li><a>COLLECTIBILES</a></li>
              <li><a>GAMES</a></li>
              <li><a>VIDEOS</a></li>
              <li><a>FANS</a></li>
              <li><a>NEWS</a></li><a></a>
              <li><a>SHOP</a></li>
          </ul>
      </div>
    </header>
</template>

<script>
export default {

}
</script>

<style lang= "scss">

@import url('https://fonts.googleapis.com/css2?family=Acme&display=swap');
/* @import url('../assets/variables.scss'); */

#site-header {
    width: 1000px;
    height: 90px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    
        .logo {
            width: 90px;
            height: 90px;
            padding: 10px;

            img {
                width: 100%;
                height: 100%;
            }
        }
        .navbar {
            width: 590px;
            height: 90px;
            display: flex;
            align-items: center;
            justify-content: space-around;
            font-size: 0.8em;
            font-family: 'Acme', sans-serif;
        
        ul {

            li {
                list-style-type: none;
                display: inline-block;
                margin: 0px 8px;

                a.active {
                    /* color: $brand-blue;  come importare foglio variabili scss? */ 
                    color: #0282F9;
                }
            }
        }

        }



}

</style>