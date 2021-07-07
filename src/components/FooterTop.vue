<template>
  <footer>
      <div class="container">
      <div class="box dc_comics">
          <div class="top">
              <h3>dc comics</h3>
              <ul>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Comics</a></li>
                  <li><a href="#">Movies</a></li>
                  <li><a href="#">TV</a></li>
                  <li><a href="#">Games</a></li>
                  <li><a href="#">Videos</a></li>
                  <li><a href="#">News</a></li>
              </ul>
          </div>
          <div class="botton">
              <h3>shop</h3>
              <ul>
                  <li><a href="#">Shop DC</a></li>
                  <li><a href="#">Shop DC Collectibles</a></li>
              </ul>
          </div>
      </div>
      <div class="box dc">
          <h3>dc</h3>
          <ul>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy policy (New)</a></li>
              <li><a href="#">Ad Choices</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
          </ul>
      </div>
      <div class="box sites">
          <h3>sites</h3>
          <ul>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Megazione</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
          </ul>
      </div>
      </div>
      <img src="../assets/img/dc-logo-bg.png" alt="logo DC">
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '../style/var.scss';
footer{
    height: 300px;
    background-image: url(../assets/img/footer-bg.jpg);
    display: $flex_primary;
    justify-content: space-around;

    .container{
        display: $flex_primary;
        padding: 10px;

        .box{
            margin-right: 50px;

            h3{
                text-transform: uppercase;
                color: white;
                margin: 10px 0;
            }

            ul{
                list-style: none;

                a{
                    text-decoration: none;
                    color: gray;
                }
            }
        }
    }
}
</style>