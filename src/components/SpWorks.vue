<template>

      <v-card class="card">
        <v-card-title class='title green lighten-2'>
          スマホ用Works
        </v-card-title>

        
        <v-card-content>

            <div class="d-flex flex-row">
                    <!--中の小さいカード-->
                    <v-card class="mini-card">
                        <v-card-title class='title green lighten-3'>
                            Key判別AI
                        </v-card-title>

                        <v-card-content>
                            <div class="text-center pt-4">
                                <v-btn class='mx-2' href='https://keyjudgeai.herokuapp.com/kj_ai/' target='_blank'>App</v-btn>
                                <v-btn class='mx-2' href='https://github.com/hatena-hanata/KJA_app' target='_blank'>Code</v-btn>
                                <v-btn class='mx-2' href='https://qiita.com/hanata/items/48e84fb051f4b7e04ac1' target='_blank'>Qiita</v-btn>
                            </div>
                            <div class="text-center px-2 py-4">
                                U-fretに掲載されている楽曲のコード進行から、キーを判別するWebアプリです。<br>
                                Djangoを用いて開発しました。
                            </div>
                        </v-card-content>
                    </v-card>

                <!--中の小さいカード-->
                <v-card class="mini-card">
                    <v-card-title class='title green lighten-3'>
                        TSUTAYA在庫検索フィルター
                    </v-card-title>

                    <v-card-content>
                        <div class="text-center pt-4">
                            <v-btn class='mx-2' href='https://github.com/hatena-hanata/Search_zaiko_app' target='_blank'>Code</v-btn>
                            <v-btn class='mx-2' href='https://qiita.com/hanata/items/0b0f733e87cd67ec8fe7' target='_blank'>Qiita</v-btn>
                        </div>
                        <div class="text-center px-2 py-4">
                            TSUTAYAの在庫検索システムの結果をスクレイピングし、<br>
                            在庫がある店舗名のみを抽出するGUIアプリを開発しました。<br>
                            PythonのGUI開発用ライブラリTkinterを用いて開発しました。
                        </div>
                    </v-card-content>
                </v-card>

                <!--中の小さいカード-->
                <!-- <v-card class="mini-card">
                    <v-card-title class='title green lighten-3'>
                        Depth of Reason（研究）
                    </v-card-title>

                    <v-card-content>
                        <div class="text-center pt-4">
                                <v-btn class='mx-2' href='https://depthofreason.herokuapp.com/select_csv/' target='_blank'>App</v-btn>
                                <v-btn class='mx-2' href='https://github.com/hatena-hanata/DOR_APP' target='_blank'>Code</v-btn>
                            </div>
                            <div class="text-center px-2 py-4">
                                Depth of Reasonを判別するWebアプリです。<br>
                                Djangoを用いて開発しました。
                        </div>
                    </v-card-content>
                </v-card> -->
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
/* パソコンで見たときは"pc"のclassがついた画像が表示される */
.pc { display: block !important; }
.sp { display: none !important; }
/* スマートフォンで見たときは"sp"のclassがついた画像が表示される */
@media only screen and (max-width: 750px) {
.pc { display: none !important; }
.sp { display: block !important; }
}
</style>