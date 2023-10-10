<script>
export default {
name: 'Main'
}
</script>

<template>
  <main>

    <div class="container-main d-flex ">
      <div class="card">
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
</style>