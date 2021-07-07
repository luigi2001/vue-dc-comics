<template>
  <main>
      <ul>
          <li v-for="(item,index) in navMain" :key="index">
              <img :src="item.img" alt="">
              <a href="item.url">{{item.text}}</a>
          </li>
      </ul>
  </main>
</template>

<script>
import NavMain from '@/data/ArrayNavMain.js';
export default {
    data(){
        return{
            navMain: NavMain
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

            a{
                text-decoration: none;
                text-transform: uppercase;
                color: white;
            }
            
            img{
                width: 30px;
                margin-right: 20px;
                vertical-align: middle;
            }
        }
    }
}
</style>