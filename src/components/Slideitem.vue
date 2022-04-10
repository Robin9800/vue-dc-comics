<template>
  <div class="card">
      <img :src="slide.thumb" alt="card">
      <h2>{{slide.series}}</h2>
  </div>
</template>

<script>
export default {
    name: 'SlideitemComponent',
    props: {
        slide: Object
    }
}
</script>

<style>
    .card img{
        margin: 30px 10px;
        width: 100px;
    }
    .card h2{
        display: flex;
        color: white;
        font-size: 15px;
        justify-content: start;
    }
</style>