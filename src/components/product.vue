<template>
  <div class="product-container">
      <img :src="thumb" alt="" srcset="">
      <p>{{series}}</p>
  </div>
</template>

<script>

export default {
    name: "product",

    props : {
        thumb : String,
        series : String,
    },
}
</script>

<style>

</style>