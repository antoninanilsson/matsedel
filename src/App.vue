<template>
  <div id="app">
     <Navbar />   
    <div class="container pb-5 mb-5">
         <router-view/> 
    </div>  
    <Footer />
   </div> 
</template>

<script>

import Navbar from './components/Navbar'
import Footer from './components/Footer'

export default {
    name:'app',
    components:{
      Navbar,
      Footer
    }

}

</script>



<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  height: 100%;
}


</style>
