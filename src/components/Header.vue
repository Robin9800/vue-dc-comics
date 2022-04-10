<template>
    <header>
        <img src="img/dc-logo.png" alt="dc-logo">
        <ul>
            <li v-for="(page, index) in navigation" :key="index"><a href="#">{{page.name}}</a></li>

        </ul>
    </header>
</template>

<script>
import navigation from '@/assets/navigation'
export default {
    name: 'HeaderComponent',
    data(){
        return {navigation}
    }
}
</script>

<style>
header{
    display: flex;
    justify-content: space-around;
}
header img{
    display: flex;
    align-self: center;
    height: 60px;

}
ul{
    display: flex;
}
ul li{
    margin: 43px 10px;
    font-weight: bold;
    list-style-type: none;
    font-size: 12px;
}
ul li a{
    text-decoration: none;
    color: black;
    padding-bottom: 40px;
}
ul li a:hover{
    color: hsl(209deg 98% 49%);
    border-bottom: 4px solid hsl(209deg 98% 49%);
}

</style>