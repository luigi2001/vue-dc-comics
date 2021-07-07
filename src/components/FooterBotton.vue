<template>
  <footer>
      <div class="button">
          <h3>sign-up now</h3>
      </div>
      <div class="social">
          <h3>follow us</h3>
          <div class="icon">
              <img src="../assets/img/footer-facebook.png" alt="facebook">
              <img src="../assets/img/footer-twitter.png" alt="twitter">
              <img src="../assets/img/footer-youtube.png" alt="youtube">
              <img src="../assets/img/footer-pinterest.png" alt="pinterest">
              <img src="../assets/img/footer-periscope.png" alt="periscope">
          </div>
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '../style/var.scss';
footer{
    height: $height_primary;
    background-color: #303030;
    display: $flex_primary;
    justify-content: space-around;
    align-items: center;

    .button{
        h3{
            border: 3px solid #0282F9;
            padding: 10px;
            text-transform: uppercase;
            color: white;
        }
    }

    .social{
        display: $flex_primary;

        h3{
            text-transform: uppercase;
            margin-right: 20px;
            color: #0282F9;
        }

        .icon{
            img{
                margin-right: 20px;
                vertical-align: middle;
            }
        }
    }


}

</style>