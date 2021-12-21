<template>
  <div>
    <img class="rounded-full float-left mx-5 mt-1" :src="dataTeam.img" alt="bebas"/>
    <h4 class="z-20 font-semibold text-white mt-5">{{ dataTeam.name }}</h4>
    <p class="z-20 text-gray-400 mb-10">{{ dataTeam.graduate }}</p>
    <h3 class="z-20 font-bold -mt-5 px-5 text-white relative">{{ dataTeam.bio }}</h3>
    <p class="z-20 px-7 pt-3 text-gray-300">{{ dataTeam.text }}</p>
  </div>
</template>

<script>
export default {
  props: {
    dataTeam: {
      type: Object,
      default: {},
    },
  },
};
</script>

<style></style>
