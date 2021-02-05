<template>
  <div class="services">
      <h1> Услуги сантехника</h1>
      <div class="container">

        <div class="card">
         <div class="box b1">
           <div class="content">
             <img src="@/assets/1.jpg" alt="">
           <ul>
              <li> Монтаж систем отопления </li>
              <li> Проектирование сан узла с нуля</li>
              <li> Монтаж металлопластиковых труб</li>
              <li> Монтаж сан узла с нуля </li>
              <li> Разводка труб водоснабжения</li>
         </ul>
            </div>  
          </div>
       </div>

       <div class="card">
          <div class="box b2">
            <div class="content">
                  <img src="@/assets/4.jpg" alt="">
                 <ul>
                   <li>  Прочистка труб канализаций</li>
                   <li>  Устранение засора в трубах</li>
                   <li>Гидро-динамическая промывка</li>
                   <li> Чистка засоров канализации</li>
                   <li>  Электромеханическая чистка</li>
                   <li>  Разморозка труб</li>
                 </ul>
            </div>
          </div>
       </div>

       <div class="card">
          <div class="box b3">
            <div class="content">
                <img src="@/assets/3.jpg" alt="">
               <ul>
                 <li>  Установка, ремонт, замена ванн <br/>и прочих оборудований</li>
                 <li>  Установка унитаза, раковин и  сифона</li>
                 <li>  Установка батарей </li>
                 <li>   Установка стриральной и посудомоечной машины</li>
               </ul>
            </div>
          </div>
       </div>
       
       <div class="card">
         <div class="box b4">
           <div class="content">
              <img src="@/assets/sa.jpg" alt="">
              <ul>
                 <li>Замена крана</li>
                 <li> Замена канализации</li>
                 <li> Замена труб водоснабжения</li>
              </ul>
           </div>
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
.services{
  font-size: 1rem;
  margin: 9rem 0 5rem 0;

}
h1{
  text-align: center;
  margin: 3rem 0 2rem 0;
  font-size: 2rem;
  font-weight: 400;
}
.services .container{
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  flex-wrap: wrap;
  width: 90%;
  margin: 0 auto;

}
.card{
  position: relative;
  margin: 50px;
  min-width: 23rem;
  height: 36rem;
  border-radius: 15px;
  box-shadow: inset -3px -3px 7px #ffffffb0, inset 3px 3px 5px rgba(94, 104, 121, 0.692);
}
.card .box{
  position: absolute;
  top:20px;
  right: 20px;
  left: 20px;
  bottom: 20px;
  margin: 0 auto;
  border: 2px solid #e2e1e1;
  background: #e2e4e7;
  border-radius: 15px;
  box-shadow: -3px -3px 7px #ffffffb2, 3px 3px 5px rgba(94, 104, 121, 0.945);

}
.card .box:hover {
  transform: translateY(-50px);
  box-shadow: 0 40px 70px rgba(255, 255, 255, 0.5);
}
.content{
  margin-top: 1rem;
  padding: 0 1rem;
  
}
.content img {
  width: 100%;
  height: 15rem;
  object-fit: cover;
clip-path: polygon(30% 0%, 70% 0%, 100% 30%, 100% 70%, 70% 100%, 30% 100%, 0% 70%, 0% 30%);
}

.content ul {

  padding-top: 2rem;
  line-height: 1.8rem;
}



</style>