<template>
  <div>
    <VHeader />
    <VResult />
    <VAppBtn title="re-Calcule ton imc" to="/" />
  </div>
</template>

<script>
import VHeader from '@/components/global/VHeader.vue'
import VAppBtn from '@/components/shared/VAppBtn.vue'
import VResult from '@/components/partials/result/VResult.vue'

export default {
  components: {
    VHeader,
    VAppBtn,
    VResult,
  },
}
</script>
