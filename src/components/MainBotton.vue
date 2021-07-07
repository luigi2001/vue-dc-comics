<template>
  <main>
      <ul>
          <li v-for="(item,index) in navMain" :key="index">
              <img :src="item.img" alt="ciao">
              <a href="item.url">{{item.text}}</a>
          </li>
      </ul>
  </main>
</template>

<script>
export default {
    data(){
        return{
            navMain:[
                {
                    text: 'digital comics',
                    url: '#',
                    img: '../img/buy-comics-digital-comics.png'
                },
                {
                    text: 'dc merchandise',
                    url: '#',
                    img: '../img/buy-comics-merchandise.png'
                },
                {
                    text: 'subscription',
                    url: '#',
                    img: '../img/buy-comics-subscriptions.png'
                },
                {
                    text: 'comic shop locator',
                    url: '#',
                    img: '../img/buy-comics-shop-locator.png'
                },
                {
                    text: 'dc power visa',
                    url: '#',
                    img: '../img/buy-dc-power-visa.svg'
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../style/var.scss';
main{
    background-color: #0282F9;
    height: $height_primary;
    display: $flex_primary;
    justify-content: center;
    align-items: center;

    ul{
        list-style: none;

        li{
            display: inline-block;
            margin-right: 20px;
        }
    }
}
</style>