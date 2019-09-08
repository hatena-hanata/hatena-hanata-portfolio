<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span class="font-weight-light">Portfolio</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        text
        href="https://hatena-hanata.github.io/"
        target="_blank"
      >
        <span class="mr-2">Top</span>
      </v-btn>
    </v-app-bar>
    <v-content>
      <!-- <img src="@/assets/logo.png" class="logo"/> -->
      <HelloWorld/>
    </v-content>
  </v-app>
</template>
<script>
import HelloWorld from './components/HelloWorld';
export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  data: () => ({
    //
  }),
};
</script>
