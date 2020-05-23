<template>

      <v-card class="card">
        <v-card-title class='title green lighten-2'>
          Works
        </v-card-title>

        
        <v-card-content>
          
          <v-expansion-panels class='px-2 py-4'>

            <!--パネル-->
            <v-expansion-panel>
              <v-expansion-panel-header class='green lighten-4'>Key判別AI</v-expansion-panel-header>
              <v-expansion-panel-content>

                  <div class="img_block">
                    <img src='@/assets/keyai.png' class='sp-card-image pt-4'/>
                  </div>

                <div class="text-center pt-4">
                    <v-btn class='mx-2 btn-round' href='https://keyjudgeai.herokuapp.com/kj_ai/' target='_blank'>App</v-btn>
                    <v-btn class='mx-2 btn-round' href='https://github.com/hatena-hanata/KJA_app' target='_blank'>Code</v-btn>
                    <v-btn class='mx-2 btn-round' href='https://qiita.com/hanata/items/48e84fb051f4b7e04ac1' target='_blank'>Qiita</v-btn>
                </div>
                <div class="text-center px-2 py-4">
                    U-fretに掲載されている楽曲のコード進行から、キーを判別するWebアプリです。<br>
                    Djangoを用いて開発しました。
                </div>
              </v-expansion-panel-content>
            </v-expansion-panel>

            <!--2つめ-->
            <v-expansion-panel>
              <v-expansion-panel-header class='green lighten-4'>TSUTAYA在庫検索フィルター</v-expansion-panel-header>
              <v-expansion-panel-content>
                                      <div class="img_block">
                            <img src='@/assets/tutaya.png' class='sp-card-image py-4'/>
                          </div>
                  <div class="text-center pt-4">
                      <v-btn class='mx-2 btn-round' href='https://github.com/hatena-hanata/Search_zaiko_app' target='_blank'>Code</v-btn>
                      <v-btn class='mx-2 btn-round' href='https://qiita.com/hanata/items/0b0f733e87cd67ec8fe7' target='_blank'>Qiita</v-btn>
                  </div>
                  <div class="text-center px-2 py-4">
                      TSUTAYAの在庫検索システムの結果をスクレイピングし、<br>
                      在庫がある店舗名のみを抽出するGUIアプリを開発しました。<br>
                      PythonのGUI開発用ライブラリTkinterを用いて開発しました。
                  </div>
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header class='green lighten-4'>Key判別Bot(LINE BOT)</v-expansion-panel-header>
              <v-expansion-panel-content>
                                      <div class="img_block">
                            <img src='@/assets/linebot2.png' class='sp-card-image py-4'/>
                          </div>
                  <div class="text-center pt-4">
                    <v-btn class='mx-2 btn-round' href='https://github.com/hatena-hanata/pupple_bot' target='_blank'>Code</v-btn>
                            <v-btn disabled class='mx-2 btn-round' href='#' target='_blank'>Qiita</v-btn>
                     </div>
                  <div class="text-center px-2 py-4">
                      U-fretに掲載されている楽曲のコード進行から、キーを判別します。<br>
                            アーティスト名や曲名の入力に対応しています。<br>
                            開発技術：Python(flask)
                  </div>
              </v-expansion-panel-content>
            </v-expansion-panel>

            <v-expansion-panel>
              <v-expansion-panel-header class='green lighten-4'>Portfolio</v-expansion-panel-header>
              <v-expansion-panel-content>
                <div class="img_block">
                            <img src='@/assets/portfolio.png' class='sp-card-image py-4'/>
                      </div>
                <div class="text-center pt-4">
                  <v-btn class='mx-2 btn-round' href='https://github.com/hatena-hanata/hatena-hanata-portfolio' target='_blank'>Code</v-btn>
                        </div>
                    <div class="text-center px-2 py-4">
                        このページです。<br>
                                開発技術：JavaScript(Vue.js)
                </div>
              </v-expansion-panel-content>
            </v-expansion-panel>

            <!--3つめ-->
            <v-expansion-panel>
              <v-expansion-panel-header class='green lighten-4'>Depth of Reason（研究）</v-expansion-panel-header>
              <v-expansion-panel-content>
                <div class="img_block">
                            <img src='@/assets/depth.png' class='sp-card-image py-4'/>
                      </div>
                <div class="text-center pt-4">
                        <v-btn disabled class='mx-2 btn-round' href='#' target='_blank'>App</v-btn>
                        <v-btn class='mx-2 btn-round' href='https://github.com/hatena-hanata/DOR_APP' target='_blank'>Code</v-btn>
                    </div>
                    <div class="text-center px-2 py-4">
                        Depth of Reasonを判別するWebアプリです。<br>
                        Djangoを用いて開発しました。
                </div>
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
/* パソコンで見たときは"pc"のclassがついた画像が表示される */
.pc { display: block !important; }
.sp { display: none !important; }
/* スマートフォンで見たときは"sp"のclassがついた画像が表示される */
@media only screen and (max-width: 750px) {
.pc { display: none !important; }
.sp { display: block !important; }
}
.btn-round{
  border-radius: 50px;
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