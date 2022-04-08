<template>
  <footer>
      <div class="header-footer">
        <ul class="info flex column">
          <li>bla</li>
        </ul>
      </div>

      <div class="main-footer flex">
          <ul>
                <h4>DC COMICS</h4>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Game</a></li>
                <li><a href="#">Collectibles</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">Fans</a></li>
                <li><a href="#">New</a></li>
                <li><a href="#">Shop</a></li>
          </ul>
          <ul>
                <h4>DC</h4>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Game</a></li>
                <li><a href="#">Collectibles</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">Fans</a></li>
                <li><a href="#">New</a></li>
                <li><a href="#">Shop</a></li>
          </ul>
          <ul>
                <h4>SITES</h4>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Game</a></li>
                <li><a href="#">Collectibles</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">Fans</a></li>
                <li><a href="#">New</a></li>
                <li><a href="#">Shop</a></li>
          </ul>
          <ul>
                <h4>SHOP</h4>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC Collectibles</a></li>
               
          </ul>
      </div>
      <div class="footer-container flex">

          <div class="footer-footer flex">
            <button class="sign-up">SIGN-UP NOW!</button>
          </div>
          <div class="social flex">
              <a class="follow" href="#">FOLLOW US</a>
              <ul>
                  <li>a</li>
                  <li>a</li>
                  <li>a</li>
                  <li>a</li>
                  <li>a</li>
              </ul>
          </div>
        </div>
      
  </footer>
</template>

<script>
export default {
     name: 'FooterComponent'
}
</script>

<style>
/*UTILITIES*/
    .flex{
        display: flex;
    }
    .column{
        flex-direction: column;
    }
/*CONTENT*/
    footer{
        color: white;
        background-color: hsl(209deg 98% 49%);
    }
    .header-footer ul li{
        margin: 40px 20px;
    }
    .main-footer{
        background-color: rgb(65, 32, 32);
    }.main-footer ul{
        margin: 20px;
        flex-direction: column;
    }
    .main-footer li{
        align-self: start;
        margin: 0px;
        color: hsl(102deg 4% 49%);
    }
    .footer-container{
        padding: 20px 0px;
        background-color: hsl(0deg 0% 19%);
    }
    .sign-up{
         background-color: hsl(0deg 0% 19%);
    }
    .footer-footer{
        color: white;
    }
    .sign-up{
        border: 2px solid hsl(209deg 98% 49%);
        padding: 10px 8px;
        color: white;
    }
    .follow{
        color: hsl(209deg 98% 49%);
        font-weight: bold;
        text-decoration: none;
    }
    .social{
        align-self: center;
    }
    .social ul li{
        margin: 0px 10px;
    }
    .follow ul li{
        margin: 0px 10px;
    }
    .footer-container{
        justify-content: space-around;
    }
    .footer-footer ul li{
        margin: 0px 10px
    }
    .main-footer a{
        font-size: 12px;
        color: hsl(0deg 0% 51%);
        padding: 0px;
        line-height: 20px;
    }
    .main-footer ul h4{
        display: flex;
        justify-content: start;
        margin-bottom: 20px
    }
</style>