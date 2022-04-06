<template>
    <header>
        <img src="img/dc-logo.png" alt="dc-logo">
        <ul>
            <li class="nav-bar"><a href="#">CHARACTERS</a></li>
            <li class="nav-bar"><a href="#">COMICS</a></li>
            <li class="nav-bar"><a href="#">MOVIES</a></li>
            <li class="nav-bar"><a href="#">TV</a></li>
            <li class="nav-bar"><a href="#">GAME</a></li>
            <li class="nav-bar"><a href="#">COLLECTIBLES</a></li>
            <li class="nav-bar"><a href="#">VIDEOS</a></li>
            <li class="nav-bar"><a href="#">FANS</a></li>
            <li class="nav-bar"><a href="#">NEW</a></li>
            <li class="nav-bar"><a href="#">SHOP</a></li>

        </ul>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent'
}
</script>

<style>
header{
    display: flex;
    justify-content: space-around;
}
header img{
    display: flex;
    align-content: center;
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