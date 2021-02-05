<template>
  <div class="hero">
    <div class="banner">
      <div class="hot">
        <span style ="--i:1;"></span>
        <span style ="--i:3;"></span>
        <span style ="--i:16;"></span>
        <span style ="--i:5;"></span>
        <span style ="--i:13;"></span>
        <span style ="--i:20;"></span>
        <span style ="--i:6;"></span>
        <span style ="--i:7;"></span>
        <span style ="--i:10;"></span>
        <span style ="--i:8;"></span>
        <span style ="--i:17;"></span>
        <span style ="--i:11;"></span>
        <span style ="--i:12;"></span>
        <span style ="--i:14;"></span>
        <span style ="--i:2;"></span>
        <span style ="--i:9;"></span>
        <span style ="--i:15"></span>
        <span style ="--i:4;"></span>
        <span style ="--i:19;"></span>
      </div>
     <div class="text-content">
       <ul class="text">
         <li>24/7</li>
         <li>Быстро</li>
         <li> Качественно</li>
         <li> Недорого</li>
       </ul>
     </div>
    </div>
    
<!--       
        0501 544 888
0770 544 888
0990 544 888 --> 
       

  </div>
</template>

<script>
export default {

}
</script>

<style >
.banner{
  position: relative;
  min-height: 100vh;
  background: url('~assets/banner.png');
  background-position: center center;
   background-repeat: no-repeat;
   background-size: cover;
}
.hot{
  position: relative;
  height: 20rem;
  width: 22rem;
  transform: translate(20vw, 60vh); 
  display: flex;
  z-index: 1;
  padding: 0 20px;
}
.hot span {
  position: relative;
  display: block;
  margin: 0 2px 50px;
  min-width: 8px;
  height: 120px;
  background: #fff;
  border-radius: 50%;
  animation: animate 5s linear infinite;
  opacity: 0;
  filter: blur(6px);
  animation-delay: calc(var(--i) * -0.5s);;

}

.text-content{
  position: absolute;
  left: 12.5%;
  top: 30%;
   z-index: 3;
}

.text{
  list-style: none;
  font-size: 2.8rem;
  line-height: 3.9rem;
  font-weight: 600;
  color: #024cbd;
 
}

@keyframes animate {
  0%{
    transform: translateY(0) scaleX(1);
    opacity: 0;
  }
  15%{
    opacity: 1;
  }
  50%{
    transform: translateY(-150px) scaleX(5);
  }
  95%{
    opacity: 0;
  }
  100%{
    transform: translateY(-300px) scaleX(10);
  }
  
}
@media (max-width: 991px){
.hot{
  display: none;
}
}
</style>