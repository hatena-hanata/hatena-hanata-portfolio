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
        <HelloWorld/>
      </div>

      <div class='sp'>
        <SpProfile/>
      </div>
      
    </v-content>
  </v-app>
  <!-- <img src="@/assets/logo.png" class="logo"/> -->
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
</style>