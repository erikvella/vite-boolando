<script>
import { computed } from 'vue'
export default {
name : 'Card',

props:{
product : 'object'

},

computed:{
  fullPrice(){
    return `&euro; ${this.product.fullPrice.toFixed(2 ,'0')}`
  },
  lastPrice(){
    return `&euro; ${this.product.lastPrice.toFixed(2 ,'0')}`
  }
}
}
</script>

<template>
  
  <div class="card">
        
      
        <img class="img1" 
        :src="`/src/assets/`+product.primaryImage" alt="">
        <img class="img2" 
        :src="`/src/assets/`+product.secondaryImage" alt="1b">

         <span class="discount">{{ product.discount }}</span>

        <span class="heart">&hearts;</span>

        <div class="descr">
          <span class="marca">{{ product.marca }}</span>
          <h3>{{ product.modello }}</h3>
          <span class="red-price">&euro;{{ product.lastPrice }}</span>
          <span class="barred-price">&euro;{{ product.fullPrice }}</span>
        </div>

  </div>
 
</template>



<style lang="scss" scoped>
.barred-price{
  margin-left: 15px;
}
</style>