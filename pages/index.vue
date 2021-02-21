<template>
<div class="home">
    <Hero/>
     <div class="container">
         <Services/>  
     </div>
        <Photogallery/> 
     <div class="container">
        <Benefits />
      </div>   
</div>
</template>

<script>
import Hero from "@/components/Hero"
import Services from "@/components/Services"
import Photogallery from "@/components/Photogallery"
import Benefits from "@/components/Benefits"
export default {
  components: {
    Hero,
    Services,
    Photogallery,
    Benefits
  }
}
</script>

<style >
.home{
position: relative;

}
.container {
    width: 90%;
    margin: 0 auto;
}

</style>
