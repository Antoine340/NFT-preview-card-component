<script setup lang="ts">
import NftCard from '~/components/NftCard.vue'
</script>

<template>
  <v-app>
    <v-main>
      <v-container
        class="fill-height d-flex flex-column"
      >
        <v-spacer />
        <div>
          <NftCard />
        </div>
        <div class="attribution text-center w-100 mt-16 text-white">
          Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
          Coded by <a href="https://github.com/Antoine340">@Antoine340</a>.
        </div>
        <v-spacer />
      </v-container>
    </v-main>
  </v-app>
</template>

<style scoped lang="scss">
.attribution {
  font-size: 11px; text-align: center;
  a {
    color: cornflowerblue;
  }
}
</style>
