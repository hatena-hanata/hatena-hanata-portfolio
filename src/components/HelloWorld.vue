<template>
  <v-container class="container">
    <v-column>
      
      <v-card class="card">
        <v-card-title>
          Profile
        </v-card-title>
        <v-card-content>
          説明
        </v-card-content>
      </v-card>
      <v-card class="card">
        <v-card-title>
          Works
        </v-card-title>
        <v-card-content>
          説明
        </v-card-content>
      </v-card>
      <v-card class="card">
        <v-card-title>
          Skill
        </v-card-title>
        <v-card-content>
          説明
        </v-card-content>
      </v-card>
    </v-column>
  </v-container>
</template>


<script>
export default {
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
</style>