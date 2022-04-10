<template>
  <div class="card">
      <img :src="slide.thumb" alt="card">
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

<style lang='scss' scoped>

</style>