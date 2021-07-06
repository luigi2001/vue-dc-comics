<template>
  <header>
      <a href="#"><img src="../assets/img/dc-logo.png" alt="logo DC"></a>
      <nav>
          <ul>
              <li v-for="(item,index) in nav" :key="index"><a href="item.url">{{item.text}}</a></li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            nav: [
        {
            text: 'characters',
            url : '#',
            position: false
        },
        {
            text: 'comics',
            url : '#',
            position: true
        },
        {
            text: 'movies',
            url : '#',
            position: false
        },
        {
            text: 'tv',
            url : '#',
            position: false
        },
        {
            text: 'games',
            url : '#',
            position: false
        },
        {
            text: 'collectibles',
            url : '#',
            position: false
        },
        {
            text: 'videos',
            url : '#',
            position: false
        },
        {
            text: 'fans',
            url : '#',
            position: false
        },
        {
            text: 'news',
            url : '#',
            position: false
        },
        {
            text: 'shop',
            url : '#',
            position: false
        }
    ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../style/var.scss';
header{
    height: $height_primary;
    display: $flex_primary;
    justify-content: space-around;
    align-items: center;
    background-color: red;

    img{
        width: 70px;
    }

    ul{
        list-style: none;

        li{
            display: inline-block;
            margin-right: 20px;
            padding: 28px 0;

            &:hover{
                border-bottom: 5px solid #0282F9;
            }

            a{
                text-decoration: none;
                text-transform: uppercase;
                color: black;
            }

            
        }
    }
}
</style>