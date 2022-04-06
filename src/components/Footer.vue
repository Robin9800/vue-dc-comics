<template>
  <footer>
      <div class="header-footer">
        <ul class="info">
          <li>bla</li>
        </ul>
      </div>

      <div class="main-footer">
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
  </footer>
</template>

<script>
export default {
     name: 'FooterComponent'
}
</script>

<style>
    footer{
            color: white;
            background-color: hsl(209deg 98% 49%);
        }
    .header-footer ul li{
            margin: 40px 20px;
        }
    .main-footer{
        display: flex;
        background-color: grey;
    }.main-footer ul{
        margin: 20px;
        flex-direction: column;
    }
    .main-footer li{
        margin: 0px
    }
    .info{
        display: flex;
        flex-direction: column;
    }
</style>