<template>
  <div>
    <h1 class="uppercase font-bold text-3xl mx-4 my-10">Ton résultat :</h1>

    <section class="my-8 mx-5">
      <div
        class="flex justify-center items-center flex-col bg-secondary py-5 rounded-xl"
      >
        <div>
          <p class="text-result uppercase font-bold text-l">Normal</p>
        </div>
        <div>
          <p class="flex justify-center text-6xl font-bold">22.1</p>
        </div>
        <div class="my-7">
          <p class="flex justify-center text-xs font-normal text-textNorm">
            Repère IMC normal :
          </p>
          <p>18.5 - 25kg/m2</p>
        </div>
        <div class="my-6 mx-4">
          <p class="text-center">
            Ta masse corporelle est normale, Félicitation !
          </p>
        </div>
        <div class="flex justify-center bg-sign py-8 px-8">
          <button>
            <p>Sauvegarde ton IMC</p>
          </button>
        </div>
        <div></div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'VResult',
}
</script>
