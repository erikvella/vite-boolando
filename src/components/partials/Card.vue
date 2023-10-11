<script>
export default {
name : 'Card',

props:{
product : Object

}
}
</script>

<template>
  
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
 
</template>



<style lang="scss" scoped>

</style>