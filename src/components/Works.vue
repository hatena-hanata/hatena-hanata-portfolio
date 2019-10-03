<template>

      <v-card class="card">
        <v-card-title class='title green lighten-2'>
          Works
        </v-card-title>

        
        <v-card-content>

            <div class="d-flex flex-row">
                    <!--中の小さいカード-->
                    <v-card class="mini-card">
                        <v-card-title class='title green lighten-3'>
                            Key判別AI
                        </v-card-title>

                        <v-card-content class='my-content'>

                          <div class="img_block">
                            <img src='@/assets/keyai.png' class='card-image py-4'/>
                          </div>

                          
                            <div class="text-center pt-4">
                                <v-btn class='mx-2' href='https://keyjudgeai.herokuapp.com/kj_ai/' target='_blank'>App</v-btn>
                                <v-btn class='mx-2' href='https://github.com/hatena-hanata/KJA_app' target='_blank'>Code</v-btn>
                                <v-btn class='mx-2' href='https://qiita.com/hanata/items/48e84fb051f4b7e04ac1' target='_blank'>Qiita</v-btn>
                            </div>
                            <div class="text-center px-2 py-4">
                                U-fretに掲載されている楽曲のコード進行から<br>
                                楽曲のキーを判別するWebアプリです。<br>
                                キーの判別には機械学習を利用しています。<br>
                                開発技術：Python(Django)・機械学習
                            </div>
                        </v-card-content>
                    </v-card>

                <!--中の小さいカード-->
                <v-card class="mini-card">
                    <v-card-title class='title green lighten-3'>
                        TSUTAYA在庫検索フィルター
                    </v-card-title>

                    <v-card-content>
                      <div class="img_block">
                            <img src='@/assets/tutaya.png' class='card-image py-4'/>
                          </div>
                        <div class="text-center pt-4">
                            <v-btn class='mx-2' href='https://github.com/hatena-hanata/Search_zaiko_app' target='_blank'>Code</v-btn>
                            <v-btn class='mx-2' href='https://qiita.com/hanata/items/0b0f733e87cd67ec8fe7' target='_blank'>Qiita</v-btn>
                        </div>
                        <div class="text-center px-2 py-4">
                            TSUTAYAの在庫検索システムの結果をスクレイピングし、<br>
                            在庫がある店舗名のみを抽出するGUIアプリを開発しました。<br>
                            開発技術：Python(Tkinter)
                        </div>
                    </v-card-content>
                </v-card>

            </div>
            <div class="d-flex flex-row">

                <!--中の小さいカード-->
                <v-card class="mini-card">
                    <v-card-title class='title green lighten-3'>
                        Key判別Bot(LINE BOT)
                    </v-card-title>

                    <v-card-content>
                      <div class="img_block">
                            <img src='@/assets/linebot2.png' class='card-image py-4'/>
                          </div>
                        <div class="text-center pt-4">
                            <v-btn class='mx-2' href='https://github.com/hatena-hanata/pupple_bot' target='_blank'>Code</v-btn>
                            <v-btn disabled class='mx-2' href='#' target='_blank'>Qiita</v-btn>
                        </div>
                        <div class="text-center px-2 py-4">
                            U-fretに掲載されている楽曲のコード進行から、キーを判別します。<br>
                            アーティスト名や曲名の入力に対応しています。<br>
                            開発技術：Python(flask)
                        </div>
                    </v-card-content>
                </v-card>

                <!--中の小さいカード-->
                <v-card class="mini-card">
                    <v-card-title class='title green lighten-3'>
                        Portfolio
                    </v-card-title>

                    <v-card-content>
                      <div class="img_block">
                            <img src='@/assets/portfolio.png' class='card-image py-4'/>
                      </div>
                        <div class="text-center pt-4">
                                <v-btn class='mx-2' href='https://github.com/hatena-hanata/hatena-hanata-portfolio' target='_blank'>Code</v-btn>
                            </div>
                            <div class="text-center px-2 py-4">
                                このページです。<br>
                                開発技術：JavaScript(Vue.js)
                        </div>
                    </v-card-content>
                </v-card>

                <!--中の小さいカード-->
                <v-card class="mini-card">
                    <v-card-title class='title green lighten-3'>
                        Depth of Reason（研究）
                    </v-card-title>

                    <v-card-content>
                      <div class="img_block">
                            <img src='@/assets/depth.png' class='card-image py-4'/>
                      </div>
                        <div class="text-center pt-4">
                                <v-btn class='mx-2' href='https://depthofreason.herokuapp.com/select_csv/' target='_blank'>App</v-btn>
                                <v-btn class='mx-2' href='https://github.com/hatena-hanata/DOR_APP' target='_blank'>Code</v-btn>
                            </div>
                            <div class="text-center px-2 py-4">
                                Depth of Reasonを判別するWebアプリです。<br>
                                開発技術：Python(Django)
                        </div>
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
.card-image{
  height: 15vw;
  padding-left: 10%;
  padding-right: 10%;
}

.img_block img{
     display: block;
     margin:auto;
}

</style>