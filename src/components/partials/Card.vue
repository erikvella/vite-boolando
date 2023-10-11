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
        
      
        <img class="img1" 
        :src="/src/assets/product.primaryImage" alt="">
        <img class="img2" 
        :src="/src/assets/product.secondaryImage" alt="1b">

         <span class="discount">{{ product.discount }}</span>

        <span class="heart">&hearts;</span>

        <div class="descr">
          <span class="marca">{{ product.marca }}</span>
          <h3>{{ product.modello }}</h3>
          <span class="red-price">&euro;{{ product.fullPrice }}</span>
          <span class="barred-price">&euro;{{ product.lastPrice }}</span>
        </div>

  </div>
 
</template>



<style lang="scss" scoped>

</style>