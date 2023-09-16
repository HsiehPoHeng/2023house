<template>
  <img alt="house logo" height="200" src="https://lh3.googleusercontent.com/pw/AIL4fc9ddX_Ys4Vjlf6b1rCplQw_cwTVYSTwTMiUm5LUTh1N80BMENOLye_9wEEeDYQaXfy461Jqs68ho1Z2OMUEc5wqGyiHJcLDLOEy7Kl5zW1soJ7ljnH6Ctx2Vi_Z09rqyyonjDtanJGYsrAlSabW0hZJWQ=w600-h400-s-no">
  <HelloWorld msg="房屋網"/>
  <div class="home">
    <Header></Header>
    <Banner></Banner>
    <Footer></Footer>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from '@/components/HomeHeader.vue'; 
import Banner from '@/components/HomeBanner.vue'; 
import Footer from '@/components/HomeFooter.vue'; 

export default {
  name: 'App',
  components: {
    HelloWorld, Header, Banner, Footer,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
