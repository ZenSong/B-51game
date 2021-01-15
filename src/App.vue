<template>
  <div id="app"> 
    <router-view/> 
    <!-- <div class="my-positioning" @click="myPositioning()"> 
         <img src="../static/img/dingwei.png" alt=""> 
     </div> -->
  </div>
</template>

<script>
export default {
  name: 'App', 
   mounted () {  
    // window.addEventListener("scroll", e => {
    //     var scrollTop = document.documentElement.scrollTop || document.body.scrollTop;
    //     if(scrollTop > 1000) {
    //       document.querySelector(".my-positioning").style.display = "block"
    //     }
    //     else {
    //       document.querySelector(".my-positioning").style.display = "none"
    //     } 
    // })  
  },
   methods : {
    // myPositioning() {
    //   document.documentElement.scrollTop = 0;
    //   document.body.scrollTop = 0  
    // }, 
  }
}
</script>

<style>
.van-tab{
  font-size: .875rem;
}

.my-positioning{
  width: 32px;
  height: 32px;
  position: fixed;
  bottom: 2rem;;
  right: 20px;
  display: none; 
}
.my-positioning>img{
  width: 100%;
  height: 100%;
  opacity: 0.7;
}
</style>
