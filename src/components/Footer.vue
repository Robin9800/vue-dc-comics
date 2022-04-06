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
              <li>peppe</li>
          </ul>
          <ul>
              <h4>DC</h4>
              <li>peppe</li>
          </ul>
          <ul>
              <h4>SITES</h4>
              <li>peppe</li>
          </ul>
          <ul>
              <h4>SHOP</h4>
              <li>peppe</li>
          </ul>
      </div>
      <div class="footer-container flex">

          <div class="footer-footer">
            <button class="sign-up">SIGN-UP NOW!</button>
          </div>
          <div class="social flex">
              <a class="follow" href="#">FOLLOW US</a>
              <ul>
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
        background-color: grey;
    }.main-footer ul{
        margin: 20px;
        flex-direction: column;
    }
    .main-footer li{
        margin: 0px
    }
    .footer-container,.sign-up{
        padding: 30px 0px;
        background-color: hsl(0deg 0% 19%);
    }
    .footer-footer,.sign-up{
        color: white;
        padding: 10px 8px;
    }
    .sign-up{
        border: 2px solid hsl(209deg 98% 49%);
    }
    .follow{
        color: hsl(209deg 98% 49%);
        font-weight: bold;
        text-decoration: none;
    }
    .footer-container{
        justify-content: space-around;
    }
    .footer-footer ul li{
        margin: 0px 10px
    }
</style>