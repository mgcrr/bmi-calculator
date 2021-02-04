<template>
  <div class="min-h-full">
    <VHeader />
    <div class="flex flex-col justify-center app-wrapper-height">
      <section class="flex mx-5 lg:mx-64">
        <VCard title="Homme" icon="fas fa-mars" />

        <div class="w-5"></div>

        <VCard title="Femme" icon="fas fa-venus" />
      </section>

      <section class="my-5 mx-5 lg:mx-64">
        <VSize />
      </section>

      <section class="flex mb-6 mx-5 lg:mx-64">
        <VWeight title="poids" :value="74" />
        <div class="w-5"></div>
        <VWeight title="Age" :value="19" />
      </section>
    </div>

    <VAppBtn title="Calculer" to="/result" />
  </div>
</template>

<script>
import VCard from '@/components/shared/VCard.vue'
import VHeader from '@/components/global/VHeader.vue'
import VSize from '@/components/shared/VSize.vue'
import VWeight from '@/components/shared/VWeight.vue'
import VAppBtn from '@/components/shared/VAppBtn.vue'

export default {
  components: {
    VCard,
    VHeader,
    VSize,
    VWeight,
    VAppBtn,
  },
}
</script>

<style scoped>
.app-wrapper-height {
  height: calc(100vh - 56px);
}

@media (max-width: 1250px) {
  .add-wrapper-height {
    height: 100%;
  }
}
</style>
