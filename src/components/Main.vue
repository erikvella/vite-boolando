<script>
export default {
name: 'Main'
}
</script>

<template>
  <main>

    <div class="container-main d-flex ">


      <div class="card">
        
      
            <img class="img1" src="/src/assets/1.webp" alt="">
            <img class="img2" src="/src/assets/1b.webp" alt="1b">

        <span class="discount">-50&percnt;</span>

            <span class="heart">&hearts;</span>

            <div class="descr">
              <span class="marca">Levi's</span>
              <h3>RELAXED FIT TEE UNISEX</h3>
              <span class="red-price">&euro;14.98</span>
              <span class="barred-price">&euro;29.99</span>
            </div>

      </div>
     
      
    

      






    </div>
   
  </main>
</template>



<style lang="scss" scoped>

.card{
  margin-top: 20px;
  position: relative;
  cursor: pointer;
}
.descr{
  position: absolute;
  bottom: 0;
  left: 0;
}



img{
  max-width: 350px;

}

.img1{
  display: block;
}
.img2{
  display: none;
}
.card:hover .img1{
  display: none;
}

.card:hover .img2{
  display: block;
}
</style>