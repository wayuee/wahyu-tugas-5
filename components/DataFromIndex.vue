<template>
  <div class="flex justify-content item-center min-h-screen bg-gray-800">
    <div class="grid grid-cols-4 gap-4 py-20 px-52">
      <div
        class="col-start-1 col-span-2 rounded-xl border-solid border-2 black bg-blue-900"
      >
        <img
          class="rounded-full float-left mx-5 mt-5"
          :src="dataTeam.imgDaniel"
          alt="Daniel"
        />
        <h4 class="z-20 font-semibold text-white mt-5">
          {{ dataTeam.nameDaniel }}
        </h4>
        <p class="z-20 text-gray-400">{{ dataTeam.graduateDaniel }}</p>
        <svg
          class="ml-96 -mt-14"
          width="120"
          height="100"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M104 102V59.727H84.114c0-5.871.689-11.182 2.068-15.933 1.379-4.75 3.42   -9.287 6.125-13.61C95.01 25.86 98.909 22.257 104 19.375V0c-9.758 4.27-17.712 9.874-23.864 16.813-6.151 6.939-10.712 14.545-13.681 22.818C63.485 47.904 62 59.941 62 75.74V102h42zm-62 0V59.727H22.114c0-5.871.689-11.182 2.068-15.933 1.379-4.75 3.42-9.287 6.125-13.61C33.01 25.86 36.909 22.257 42 19.375V0c-9.652 4.27-17.58 9.874-23.784 16.813C12.01 23.752 7.424 31.358 4.455 39.631 1.485 47.904 0 59.941 0 75.74V102h42z"
            fill="#A775F1"
            fill-rule="nonzero"
          />
        </svg>
        <h3 class="z-20 font-bold -mt-5 px-5 text-white">
          {{ dataTeam.bioDaniel }}
        </h3>
        <p class="z-20 px-7 pt-3 text-gray-300">{{ dataTeam.textDaniel }}</p>
      </div>
      <div class="rounded-xl border-solid border-2 black bg-gray-800">
        <img
          class="rounded-full float-left mt-5 mx-5"
          :src="dataTeam.imgJonathan"
          alt="Jonathan"
        />
        <h4 class="font-semibold text-white mt-5">{{ dataTeam.nameJonathan }}</h4>
        <p class="text-gray-400 pb-5">{{ dataTeam.graduateJonathan }}</p>
        <h3 class="font-bold px-3 pb-3 text-white">{{ dataTeam.bioJonathan }}</h3>
        <p class="px-5 text-gray-300">{{ dataTeam.textJonathan }}</p>
      </div>
      <div
        class="row-span-2 rounded-xl border-solid border-2 black bg-gray-500"
      >
        <img
          class="rounded-full float-left mt-5 mx-5"
          :src="dataTeam.imgKira"
          alt="Kira"
        />
        <h4 class="font-semibold text-white mt-5">{{ dataTeam.nameKira }}</h4>
        <p class="text-gray-400 pb-5">{{ dataTeam.graduateKira }}</p>
        <h3 class="font-bold px-3 pb-3">{{ dataTeam.bioKira }}</h3>
        <p class="px-3 pb-3 text-gray-300">{{ dataTeam.textKira }}</p>
      </div>
      <div class="rounded-xl border-solid border-2 black bg-gray-500">
        <img
          class="rounded-full float-left mt-5 mx-5"
          :src="dataTeam.imgJeanette"
          alt="jeanette"
        />
        <h4 class="font-semibold text-white mt-5">{{ dataTeam.nameJeanette }}</h4>
        <p class="text-gray-400 pb-5">{{ dataTeam.graduateJeanette }}</p>
        <h3 class="font-bold px-3">{{ dataTeam.bioJeanette }}</h3>
        <p class="px-5 pt-3 text-gray-300">{{ dataTeam.textJeanette }}</p>
      </div>
      <div
        class="col-start-2 col-span-2 rounded-xl border-solid border-2 black bg-gray-800"
      >
        <img
          class="col-span-2 rounded-full float-left mt-5 mx-5"
          :src="dataTeam.imgPatrick"
          alt="Patrick"
        />
        <h4 class="font-semibold text-white mt-5">{{ dataTeam.namePatrick }}</h4>
        <p class="text-gray-400 pb-5">{{ dataTeam.graduatePatrick }}</p>
        <h3 class="font-bold px-5 pb-3 text-white">{{ dataTeam.bioPatrick }}</h3>
        <p class="px-5 text-gray-300">{{ dataTeam.textPatrick }}</p>
      </div>
    </div>
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
