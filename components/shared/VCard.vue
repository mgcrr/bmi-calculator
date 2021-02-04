<template>
  <div
    class="w-1/2 flex justify-center items-center flex-col bg-secondary py-5 rounded-xl"
  >
    <i :class="icon" class="text-6xl"></i>
    <p class="uppercase font-bold text-sm mt-2">{{ title }}</p>
  </div>
</template>

<script>
export default {
  name: 'VCard',

  props: {
    title: {
      type: String,
      required: true,
    },

    icon: {
      type: String,
      required: true,
    },
  },
}
</script>
