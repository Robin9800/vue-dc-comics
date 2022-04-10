<template>
  <main>
      <div class="jumbotron"></div>
      <div class="container">
            <Slideitem class="card" v-for="(item, index) in slides" :key="index" :slide='item'/>
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
    .container{
        margin: 0px 200px;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
      
    }
  
    .jumbotron{
        height: 45vh;
        background-image: url("../../public/img/jumbotron.jpg");
        background-size: 100%;
    }
</style>