<template>
  <div class="bg-secondary rounded-xl py-5">
    <h2 class="flex justify-center uppercase font-bold text-sm">taille</h2>
    <div class="flex justify-center items-end">
      <p class="font-bold text-6xl leading-none mr-1">183</p>
      <p>cm</p>
    </div>
    <div class="flex justify-center mt-5">
      <input
        class="rounded-lg overflow-hidden appearance-none bg-gray-400 h-3 w-128"
        type="range"
        min="1"
        max="100"
        step="1"
        value="15"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'VSize',
}
</script>
