<template>
  <div id="app">
    <HomeHeader/> 
   <MainHeader/>
   <Hinhanh/>
   <HomeDichvu/>
   <Intro/>
  <Home-Package/>
  </div>
  
</template>

<script>
import HomeHeader from './componments/HomeHeader.vue';
import MainHeader from './componments/MainHeader.vue';
import Hinhanh from './componments/Hinhanh.vue';
import HomeDichvu from './componments/HomeDichvu.vue';
import Intro from './componments/intro.vue';
import HomePackage from './componments/Home-package.vue';
export default {
components:{ HomeHeader, MainHeader, Hinhanh, HomeDichvu, Intro,HomePackage },
}
</script>

<style>
#app {
  max-width: 1969px;
  padding: 0;
  margin: 0;
}
</style>