<template>
  <div class="benefits">
     <h3>Наши преимущества</h3>
     <div class="benefits-box">

          <ul class="benefitslist">
           <li>
             <img src="@/assets/benefits/fast.svg"  alt="icon of running man" height="56" width="50">
           </li>
           <li>Быстро</li>
         </ul>  

          <ul class="benefitslist">
           <li>
             <img src="@/assets/benefits/trusted.svg"  alt="secure sign" height="50" width="40">
           </li>
            <li>Качественно</li>
          </ul>
   
          <ul class="benefitslist">
             <li>
             <img src="@/assets/benefits/piggybank.svg"  alt="icon of running man" height="56" width="50">
           </li>
           <li>Недорого</li>
          </ul>

          <ul class="benefitslist">
             <li>
             <img src="@/assets/benefits/cooperation.svg"  alt="handshake" height="56" width="50">
             </li>
             <li>Даем гарантию на выполненные работы</li>
          </ul>

          <ul class="benefitslist">
             <li>
             <img src="@/assets/benefits/worker.svg"  alt="worker" height="56" width="50">
           </li> 
            <li>Опытные мастера с большим стажем</li> 
          </ul>

          <ul class="benefitslist">
           
             <li>
             <img src="@/assets/benefits/delivery-truck.svg"  alt="delivery truck" height="56" width="50">
           </li>
            <li>Починим все за один выезд </li>
          </ul>
     </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.benefits{
    margin: 9rem 0;
    text-align: center;
}
.benefits h3 {
    font-size: 2rem;
    font-weight: 400;
    margin:5rem 0 2rem 0;
}
.benefits-box {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.benefits-box ul{
    list-style: none;
    margin-bottom: 10px;
}
 

</style>