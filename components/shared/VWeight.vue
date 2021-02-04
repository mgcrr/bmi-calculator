<template>
  <div
    class="w-1/2 flex justify-center items-center flex-col bg-secondary py-5 rounded-xl"
  >
    <div>
      <p class="uppercase font-bold text-sm">{{ title }}</p>
    </div>
    <div>
      <p class="font-bold text-6xl leading-none mr-1">{{ value }}</p>
    </div>
    <div class="flex justify-center items-end">
      <div
        class="w-10 h-10 items-center flex justify-center rounded-full bg-sign"
      >
        <i class="fas fa-minus"></i>
      </div>
      <div class="w-3"></div>
      <div
        class="w-10 h-10 items-center flex justify-center rounded-full bg-sign"
      >
        <i class="fas fa-plus"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'VWeight',

  props: {
    title: {
      type: String,
      required: true,
    },

    value: {
      type: Number,
      required: true,
    },
  },
}
</script>
