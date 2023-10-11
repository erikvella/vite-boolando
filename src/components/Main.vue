<script>
import products from '../data/products';
import Card from './partials/Card.vue';
export default {
name: 'Main',
components:{
  Card
},
data(){
  return{
    products
  }
}
}
</script>

<template>
  <main>

    <div class="container-main d-flex ">


      <Card 
      v-for="product in products" 
      :key="product.id"
      :product="product"
      
       />
    

      






    </div>
   
  </main>
</template>



<style lang="scss" scoped>


</style>