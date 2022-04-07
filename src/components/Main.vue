<template>
  <main>
      <div class="container">
          <div v-for="(item, index) in slides" :key="index">

          </div>
      </div>
  </main>
</template>

<script>
export default {
    name: 'MainComponent',
    props: {
        slides: Array
    }
}
</script>

<style>
    main{
        background-color: hsl(0deg 0% 11%);;
    }
    main h3{
        padding: 40px;
        color: white;
        font-weight: bold;
    }
</style>