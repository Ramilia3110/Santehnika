<template>
  <div class="footer">
    <div class="container">
      <div class="contact-us">
           <h4> Напишите нам :</h4>
            <div class="social-media-links">
          <a href="">
            <img class="social" src="@/assets/socialmedia/gmail.svg" alt="logo of gmail">
          </a>
          <a href="https://www.instagram.com/p/CKYRpZwsvdM/?igshid=yx9io1naqgta">
            <img class="social"  src="@/assets/socialmedia/i.svg" alt="logo of instagram">
          </a>
      </div>
    </div>
      <p>Бишкек  2021</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.footer{
    background: #000;

    color: #fff;
    
}
.contact-us {
 padding: 1.5rem 0 2rem 0;
 font-size: 1.2rem;
 text-align: center;
 display: flex;
 align-items: flex-start; 
 justify-content: space-evenly;
 flex-direction: column;

}
.contact-us h4 {
  padding-bottom: 1.1rem;
}
.social-media-links a{
  padding: 1rem .7rem 0 1rem;
}
.social-media-links a:hover{
  background: rgba(255, 255, 255, .18);
}
.social {
  width: 2rem;
  height: 2rem;
  
}
p{
  text-align: center;
  padding-bottom: 1rem;
}
</style>