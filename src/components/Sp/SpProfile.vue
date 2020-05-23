<template>
  <v-container class="container">
    <v-column>
      
      <!--プロフィール-->
      <v-card class="card">
        <v-card-title class='title red lighten-3'>
          Profile
        </v-card-title>
        <v-card-content>
          <div class="text-center py-4 px-4">
            いしむらと申します。<br>
            所属：東京工業大学 情報理工学院 矢野和男研究室 修士2年<br>
            インターン：かっこ株式会社（2018/12～現在）<br>
            ビジネスにおける、統計・機械学習の活用に興味があります。
          </div>
        </v-card-content>
      </v-card>

      <!--成果物-->
      <Works/>


      <Skill/>

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
import Skill from './Skill';
export default {
  // name:'HelloWorld',
  components: {
    Works,
    Hobby,
    Skill,
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
  margin: 30px;
  border-radius: 10px;
}
.title {
  justify-content: center;
}
</style>