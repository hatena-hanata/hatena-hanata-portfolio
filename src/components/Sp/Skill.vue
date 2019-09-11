<template>
 
      <v-card class="card">
        <v-card-title class='title blue lighten-3'>
          Skill
        </v-card-title>

        
        <v-card-content>


            <v-expansion-panels class='px-2 py-4'>

              <!--パネル-->
              <v-expansion-panel>
                <v-expansion-panel-header class='blue lighten-4'>言語・フレームワーク</v-expansion-panel-header>
                <v-expansion-panel-content>
                    <ul class='pt-4'>
                      よく使う<br>
                      
                      <li>Python</li>
                      
                      <li>PostgreSQL</li>
                      <li>Django</li><br>
                      たまに使う
                      <li>JavaScript（Vue.js）</li>
                      <li>R</li>
                      <li>C言語</li>
                    </ul>
                </v-expansion-panel-content>
              </v-expansion-panel>

            <!--2つめ-->
            <v-expansion-panel>
              <v-expansion-panel-header class='blue lighten-4'>資格</v-expansion-panel-header>
              <v-expansion-panel-content>
                  <ul class='pt-4 px-2'>
                     <li>統計検定2級</li>
                     <li>基本情報技術者試験合格</li>
                  </ul>
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
</style>