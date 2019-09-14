<template>
 
      <v-card class="card">
        <v-card-title class='title yellow lighten-2'>
          Hobby
        </v-card-title>

        
        <v-card-content>

            <p class='text-center pt-4 px-2'>楽器(ギター、ベース、ピアノ、カホン…)を弾くのが好きです。</p>

            <v-expansion-panels class='px-2 py-4'>

              <!--パネル-->
              <v-expansion-panel>
                <v-expansion-panel-header class='yellow lighten-4'>Blog</v-expansion-panel-header>
                <v-expansion-panel-content>
                  <div class="img_block">
                            <img src='@/assets/blog.png' class='sp-card-image py-4'/>
                  </div>
                  <p class='text-center py-4 px-2'>
                      耳コピした曲のギター用コード譜や<br>ベースのTab譜を公開しています。<br><br>
                      <a href="http://hanatasdiary.hatenablog.com/" target="_blank">はなたの日記</a>
                  </p>
                </v-expansion-panel-content>
              </v-expansion-panel>

            <!--2つめ-->
            <v-expansion-panel>
              <v-expansion-panel-header class='yellow lighten-4'>YouTube</v-expansion-panel-header>
              <v-expansion-panel-content>
                <div class="img_block">
                            <img src='@/assets/youtube.png' class='sp-card-image py-4'/>
                  </div>
                  <p class='text-center py-4 px-2'>
                      ベースの演奏動画をアップロードしています。<br><br>
                      <a href="https://www.youtube.com/channel/UCXfCw6GmILC8gj8c07rl_2g/" target="_blank">はなたの部屋</a>
                  </p>
              </v-expansion-panel-content>
            </v-expansion-panel>

          </v-expansion-panels>

        </v-card-content>
      </v-card>

</template>


<script>
export default {
  data: () => ({
  }),
};
</script>


<style>
.mini-card {
  width: 40vw;
  margin: 20px;
  border-radius: 10px;
}

.sp-card-image{
  width:100%;
  height:100%;
  padding-left: 10%;
  padding-right: 10%;
}

.img_block img{
     display: block;
     margin:auto;
}
</style>