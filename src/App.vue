<template>
  <v-app>
    <v-app-bar app>
        <v-toolbar-title class="headline">
        <span class="font-weight-light">Portfolio</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        text
        href="https://hatena-hanata.github.io/hatena-hanata-portfolio/"
      >
        <span>Top</span>
      </v-btn>
    </v-app-bar>
    <v-content>
      
      <div class='pc'>
        <div class="img-header-pc">
          <img src='@/assets/header.png' class='sp-card-image pt-4'/>
          <p>Portfolio</p>
      </div>
        <HelloWorld/>
      </div>

      <div class='sp'>
        <div class="img-header-sp">
          <img src='@/assets/header.png' class='sp-card-image pt-4'/>
          <p>Portfolio</p>
      </div>
        <SpProfile/>
      </div>
      
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import SpProfile from './components/Sp/SpProfile';
export default {
  name: 'App',
  components: {
    HelloWorld,
    SpProfile,
  },
  data: () => ({
    //
  }),
};
</script>

<style>
.pc { display: block !important; }
.sp { display: none !important; }

@media only screen and (max-width: 750px) {
.pc { display: none !important; }
.sp { display: block !important; }
}

.img-header-pc {
  position: relative;
  
}
.img-header-pc img {
  opacity: 0.2;
}

.img-header-pc p {
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%,-50%);
  -webkit-transform: translate(-50%,-50%);
  transform: translate(-50%,-50%);
  margin:0;
  padding:0;
  /* font-weight: bold; 太字に */
  font-size: 5em;/*サイズ2倍*/
  font-family :Roboto, sans-serif;/*Google Font*/
  /*文字の装飾は省略*/
  }

  .img-header-sp {
  position: relative;
  
}
.img-header-sp img {
  opacity: 0.2;
}

.img-header-sp p {
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%,-50%);
  -webkit-transform: translate(-50%,-50%);
  transform: translate(-50%,-50%);
  margin:0;
  padding:0;
  /* font-weight: bold; 太字に */
  font-size: 2em;/*サイズ2倍*/
  font-family :Roboto, sans-serif;/*Google Font*/
  /*文字の装飾は省略*/
  }
</style>