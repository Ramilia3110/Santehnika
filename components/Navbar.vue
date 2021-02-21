<template>
  <div class="navbar">
    <div class="container">
       <div class="menu">
        <div class="logo">
     Бишкек Сантехника
      </div>
         <ul itemscope class="phone-links">
         <li  class="first" itemprop="telephone">
            <img class="call" src="@/assets/socialmedia/phone-call.svg" alt="icon of telephone">
           <a href="tel:+996501544888">0501 544 888 </a>
         </li>
          <li itemprop="telephone">
             
            <a href="tel:+996770544888">0770 544 888</a>
         </li>
       </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.navbar{
  background: #024cbd;
  position: fixed;
  width: 100%;
  z-index: 10;
  height: 7vh;

}
.navbar-container{
  width: 70%;
  margin: 0 auto;

}


  
.phone-links {
  position: absolute;
  right: 1.3rem;
  top: 0.5rem;
  width: 25vh;
  display: flex;
  align-items: center;
  justify-content: center;
  list-style: none;
  flex-direction: column;
 
}

.first{
  display: flex;
  align-items: center;
}
.call{
  width: 1rem;
  height: 1em;
  color: #fff;
  margin-right: .5rem;

}
.phone-links li:last-child {
  padding-left: 1.6rem;
}

.phone-links li a{
  text-decoration: none;
  color: #fff;
  font-size: 1rem;
}
.logo{
  color: #fff;
  font-size: 1.8rem;
  font-weight: 400;
  padding-top: .5rem;
}
@media (max-width: 768px){
.logo{
  font-size: 1.5rem;
}
}

</style>