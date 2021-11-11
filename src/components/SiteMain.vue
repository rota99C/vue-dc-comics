<template>
  <main id="site-main">
    <div class="content-goes">
      <div>
        <h2>--> Content goes here &#60;--</h2>
      </div>
    </div>
    <div class="content-cards">
      <div>
        <ul>
          <li>
            <a href="">
              <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
              <p>DIGITAL COMICS</p>
            </a>
          </li>
          <li>
            <a href="">
              <img src="../assets/img/buy-comics-merchandise.png" alt="" />
              <p>DC MERCHANDISE</p>
            </a>
          </li>
          <li>
            <a href="">
              <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
              <p>SUBSCRIPTION</p>
            </a>
          </li>
          <li>
            <a href="">
              <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
              <p>COMIC SHOP LOCATOR</p>
            </a>
          </li>
          <li>
            <a href="">
              <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
              <p>DC POWER VISA</p>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss">
#site-main {
  width: 100%;
  height: 215px;
  background-color: violet;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;

  .content-goes {
    height: 95px;
    background-color: black;

    div {
      width: 1000px;
      margin: auto;

      h2 {
        color: white;
        line-height: 95px;
      }
    }
  }

  .content-cards {
    height: 120px;
    background-color: #0282f9;

    div {
      width: 1000px;
      height: 100%;
      margin: auto;

      ul {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 100%;
        
        li {
          list-style-type: none;
          
          a {
            display: flex;
            align-items: center;
            justify-content: center;

            img {
                width: 20%;
            }
          }
        }
      }
    }
  }
}
</style>
