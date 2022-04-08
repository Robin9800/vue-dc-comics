<template>
  <main>
      <div class="container">
            <Slideitem v-for="(item, index) in slides" :key="index" :slide='item'/>
        </div>
        
  </main>
</template>

<script>
import Slideitem from '@/components/Slideitem.vue'
export default {
    name: 'MainComponent',
    props: {
        slides: Array
    },
    components: {
        Slideitem
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