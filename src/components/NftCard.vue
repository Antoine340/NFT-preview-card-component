<script setup lang="ts">

</script>

<template>
  <v-card
    color="hsl(216, 50%, 16%)"
    rounded="lg"
    class="nft-card pa-6"
    max-width="400"
  >
    <div
      class="mx-2"
    >
      <v-img
        src="/images/image-equilibrium.jpg"
        class="rounded-lg"
      />
    </div>
    <v-card-title
      class="text-white mt-4 mb-2"
    >
      Equilibrium #3429
    </v-card-title>
    <v-card-text>
      <p>Our Equilibrium collection promotes balance and calm.</p>
      <div class="d-flex mt-6">
        <div class="d-flex">
          <v-img
            src="/images/icon-ethereum.svg"
            width="18"
            height="18"
            class="mr-2"
          />
          <p class="text-cyan">
            <strong>0.041 ETH</strong>
          </p>
        </div>
        <v-spacer />
        <div class="d-flex">
          <v-img
            src="/images/icon-clock.svg"
            width="18"
            height="18"
            class="mr-2"
          />
          <p>3 days left</p>
        </div>
      </div>
      <v-divider
        thickness="2"
        color="hsl(215, 51%, 70%)"
        class="my-5 rounded-lg"
      />
      <div class="d-flex align-center">
        <v-avatar
          color="white"
          class="mr-4"
          image="/images/image-avatar.png"
          style="border: 1px solid white;"
        />
        <p>
          Creation of
          <span class="text-white">Jules Wyvern</span>
        </p>
      </div>
    </v-card-text>
  </v-card>
</template>

<style scoped lang="scss">
.nft-card {
  box-shadow: 0px 10px 20px hsla(0, 0%, 0%, 0.6);
}
.text-cyan {
  color: hsl(178, 100%, 50%)
}
</style>
