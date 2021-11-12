<template>
  <footer id="site-footer">
    <div class="footer-navbar">
      <div class="container">
        <div class="footer-list">
          <div class="list">
            <h3>DC COMICS</h3>
            <ul>
              <li><a href="">Characters</a></li>
              <li><a href="">Comics</a></li>
              <li><a href="">Movies</a></li>
              <li><a href="">TV</a></li>
              <li><a href="">Games</a></li>
              <li><a href="">Videos</a></li>
              <li><a href="">News</a></li>
            </ul>
          </div>
          <div>
            <h3>SHOP</h3>
            <ul>
              <li><a href="">Shop DC</a></li>
              <li><a href="">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <div>
            <h3>DC</h3>
            <ul>
              <li><a href="">Terms Of Use</a></li>
              <li><a href="">Privacy policy (New)</a></li>
              <li><a href="">Ad Choices</a></li>
              <li><a href="">Advertising</a></li>
              <li><a href="">Jobs</a></li>
              <li><a href="">Subscriptions</a></li>
              <li><a href="">Talent Workshops</a></li>
              <li><a href="">CPSC Certificates</a></li>
              <li><a href="">Ratings</a></li>
              <li><a href="">Shop Help</a></li>
              <li><a href="">Contact Us</a></li>
            </ul>
          </div>
          <div>
            <h3>SITES</h3>
            <ul>
              <li><a href="">DC</a></li>
              <li><a href="">MAD Magazine</a></li>
              <li><a href="">DC Kids</a></li>
              <li><a href="">DC Universe</a></li>
              <li><a href="">DC Power Visa</a></li>
            </ul>
          </div>
        </div>
        <div class="footer-logo">
          <img src="../assets/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>
    <div></div>
    <div class="footer-contacts">
      <div class="container-footer">
        <div class="sign-up"><a>SIGN-UP NOW!</a></div>
        <div class="social">
          <h3>FOLLOW US</h3>
          <img src="../assets/img/footer-facebook.png" alt="" />
          <img src="../assets/img/footer-twitter.png" alt="" />
          <img src="../assets/img/footer-youtube.png" alt="" />
          <img src="../assets/img/footer-pinterest.png" alt="" />
          <img src="../assets/img/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
#site-footer {
  width: 100%;
  height: 360px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;

  .footer-navbar {
    height: 270px;
    background-image: url("../assets/img/footer-bg.jpg");

    .container {
      width: 1000px;
      margin: auto;
      display: flex;
      flex-direction: row;
      height: 100%;

      div.footer-list {
        width: 50%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        padding: 30px 0px;

        h3 {
          color: white;
        }

        div.list {
          flex-grow: 1;
        }

        ul {
          li {
            list-style-type: none;
            color: #82827f;
            font-size: 0.8em;

            a {
              text-decoration: none;
            }

            a:visited {
              color: #82827f;
            }
          }
        }
      }

      div.footer-logo {
        width: 50%;
        position: relative;
        overflow: hidden;

        img {
          position: absolute;
          top: -130px;
          width: 100%;
          height: auto;
        }
      }
    }
  }
  .footer-contacts {
    height: 110px;
    background-color: #303030;

    div.container-footer {
      width: 1000px;
      margin: auto;
      height: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;

      div.sign-up {
        color: white;
        padding: 10px;
        border: 2px solid #0282f9;
        height: auto;
      }

      div.social {
        display: flex;

        h3 {
          color: #0282f9;
          margin-right: 20px;
          align-self: center;
        }

        img {
          margin: 0px 10px;
          width: auto;
          height: auto;
        }
      }
    }
  }
}
</style>
