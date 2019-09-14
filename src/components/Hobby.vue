<template>
 
      <v-card class="card">
        <v-card-title class='title yellow lighten-2'>
          Hobby
        </v-card-title>

        
        <v-card-content>

            <p class='text-center pt-4 px-2'>楽器(ギター、ベース、ピアノ、カホン…)を弾くのが好きです。</p>
            <div class="d-flex flex-row">
                    <!--中の小さいカード-->
                    <v-card class="mini-card">
                        <v-card-title class='title yellow lighten-3'>
                            Blog
                        </v-card-title>

                        <v-card-content>
                          <div class="img_block">
                            <img src='@/assets/blog.png' class='card-image py-4'/>
                  </div>
                            <p class='text-center py-4 px-2'>
                                耳コピした曲のギター用コード譜や<br>ベースのTab譜を公開しています。<br><br>
                                <a href="http://hanatasdiary.hatenablog.com/" target="_blank">はなたの日記</a>
                            </p>
                        </v-card-content>
                    </v-card>

                <!--中の小さいカード-->
                <v-card class="mini-card">
                    <v-card-title class='title yellow lighten-3'>
                        YouTube
                    </v-card-title>

                    <v-card-content>
                      <div class="img_block">
                            <img src='@/assets/youtube.png' class='card-image py-4'/>
                  </div>
                        <p class='text-center py-4 px-2'>
                            ベースの演奏動画をアップロードしています。<br><br>
                            <a href="https://www.youtube.com/channel/UCXfCw6GmILC8gj8c07rl_2g/" target="_blank">はなたの部屋</a>
                        </p>
                        
                    </v-card-content>
                </v-card>

            </div>

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
/* .container {
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
} */
.mini-card {
  width: 40vw;
  margin: 20px;
  border-radius: 10px;
}
</style>