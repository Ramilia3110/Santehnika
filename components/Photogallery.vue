<template>
  <div class="photogallery">
      <div class="container">
         <div class="gal i1">
              <div class="image">
                <img src="@/assets/photogallery/sink1.jpg" alt="sink">
             </div>
         </div>
         <div class="gal i2">
             <div class="image">
                <img src="@/assets/photogallery/shower.jpg" alt="sink">
             </div>
         </div>
         <div class="gal i3">
             <div class="image">
                <img src="@/assets/photogallery/bath.jpg" alt="sink">
             </div>
         </div>
         <div class="gal i4">
             <div class="image">
                <img src="@/assets/photogallery/toilet.jpg" alt="sink">
             </div>
         </div>
         <div class="gal i5">
             <div class="image">
                <img src="@/assets/photogallery/sink2.jpg" alt="sink">
             </div>
         </div>
         <div class="gal i6">
             <div class="image">
                <img src="@/assets/photogallery/sink3.jpg" alt="sink">
             </div>
         </div>
         <div class="gal i7">
             <div class="image">
                <img src="@/assets/photogallery/bath2.jpg" alt="sink">
             </div>
         </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style> 

.photogallery .container{ 
    display: grid;
    grid-template-columns: repeat (4, 1fr );
    grid-template-rows: 200px 200px 200px;
    grid-gap: 20px;
   
}
.gal {
    position: relative;  
    width: 100%;
    height: 100%;
   
}
.gal .image {
      width: 100%;
    height: 100%;
    overflow: hidden;
}
.gal .image img {
      width: 100%;
    height: 100%;
    object-fit: cover;
}

.i1{
    grid-column: 1/3;
    grid-row: 1/2;
    position: relative;
    width: 100%;
    height: 100%;
    
}

.i2{
    grid-column: 3/4;
    grid-row: 1/3;
}
.i3{
    grid-column: 4/5;
    grid-row: 1/2;
}
.i4{
    grid-column: 1/2;
    grid-row: 2/4;
}
.i5{
    grid-column: 2/3;
    grid-row: 2/3;
}
.i6{
    grid-column: 4/5;
    grid-row: 2/3;
}
.i7{
    grid-column: 2/5;
    grid-row: 3/4;
}

@media (max-width: 991px){
    .photogallery .container{
        grid-template-columns: repeat (auto-fill, minmax(50%, 1fr));
        grid-template-rows: minmax(auto, auto);
    }

    .gal {
        grid-column: unset !important;
        grid-row: unset !important;
        height: 20rem;
    }
    .i1, .i2,.i4,.i5,.i7 {
        display: none;
    }
}


</style>