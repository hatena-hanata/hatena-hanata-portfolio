<template>
  <v-container class="container">
    <v-column>
      
      <!--プロフィール-->
      <v-card class="card">
        <v-card-title class='title red lighten-3'>
          Profile
        </v-card-title>
        <v-card-content>
          説明
        </v-card-content>
      </v-card>

      <!--成果物-->
      <Works/>



      <v-card class="card">
        <v-card-title class='title blue lighten-3'>
          Skill
        </v-card-title>
        <v-card-content>
          説明
        </v-card-content>
      </v-card>

      <!--趣味-->
      <Hobby/>

      <!--連絡先-->
      <v-card class="card">
        <v-card-title class='title brown lighten-3'>
          Contact・Links
        </v-card-title>
        <v-card-content>
          <p class='text-center py-4 px-2'>
              mail:hatena.hanata＠gmail.com<br>
              Qiita:<a href='https://qiita.com/hanata'>https://qiita.com/hanata</a>
          </p>
        </v-card-content>
      </v-card>

    </v-column>
  </v-container>
</template>


<script>
import Works from './Works';
import Hobby from './Hobby';
export default {
  // name:'HelloWorld',
  components: {
    Works,
    Hobby,
  },
  data: () => ({
  }),
};
</script>


<style>
.container {
  display: flex;
  justify-content: center;
}
.logo {
  width: 100vw;
}
.card {
  width: 80vw;
  margin: 100px;
  border-radius: 10px;
}
.title {
  justify-content: center;
}
</style>