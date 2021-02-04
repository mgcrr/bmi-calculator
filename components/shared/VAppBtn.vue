<template>
  <footer
    class="lg:fixed lg:bottom-0 lg:right-0 lg:mr-10 cursor-pointer flex justify-center uppercase text-ms blod py-5 bg-accent lg:bg-transparent"
  >
    <nuxt-link :to="to">
      <div
        class="flex justify-center items-center uppercase font-bold bg-accent lg:w-32 lg:h-32 lg:rounded-full"
      >
        <span> {{ title }}</span>
      </div>
    </nuxt-link>
  </footer>
</template>

<script>
export default {
  name: 'VAppBtn',

  props: {
    title: {
      type: String,
      required: true,
    },

    to: {
      type: String,
      required: true,
    },
  },
}
</script>
