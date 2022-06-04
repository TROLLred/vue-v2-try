<template>
    <v-container fluid>
      <v-app-bar
        color="deep-purple accent-4"
        dark
      >
        <v-spacer/>
        <v-btn class="ml-3">
            <router-link to="/">Главная</router-link>
        </v-btn>
        <v-btn class="ml-3">
            <router-link to="/photo">Фотографии</router-link>
        </v-btn>
      </v-app-bar>
    </v-container>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    
</style>