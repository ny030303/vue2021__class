<template>
  <div>
   라우터 실습 <br><br>

   <router-link to="/">INDEX</router-link> |
   <router-link to="/home">HOME</router-link> |
   <router-link to="/about/100/data/Nolbu">ABOUT</router-link> |
   <router-link to="/child">CHILD</router-link> |
   <router-link to="/abc">abc</router-link> |
   
   <router-view></router-view>
  </div>
</template>

<script>


export default {
    name: 'App',
    components: {
      
    }
  
}
</script>

<style>

</style>
