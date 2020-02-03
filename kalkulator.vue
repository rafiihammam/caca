<template>
 <div class="container">
   <form  class="text-center" style="margin-top: 5%">
   <h1 class="text-center">Pertambahan</h1>
   <input type="number" v-model.number="angka_1"> +
   <input type="number" v-model.number="angka_2">
   <h2 class="text-center">{{ angka_1 + angka_2}}</h2>
  </form>
  <form  class="text-center" style="margin-top: 3%">
   <h1 class="text-center">Pengurangan</h1>
   <input type="number" v-model.number="angka_3"> -
   <input type="number" v-model.number="angka_4">
   <h2 class="text-center">{{ angka_3 - angka_4}}</h2>
  </form>
  <form  class="text-center" style="margin-top: 3%">
   <h1 class="text-center">Perkalian</h1>
   <input type="number" v-model.number="angka_5"> *
   <input type="number" v-model.number="angka_6">
   <h2 class="text-center">{{ angka_5 * angka_6}}</h2>
  </form>
  <form  class="text-center" style="margin-top: 3%">
   <h1 class="text-center">Pembagian</h1>
   <input type="number" v-model.number="angka_7"> :
   <input type="number" v-model.number="angka_8">
   <h2 class="text-center">{{ angka_7 / angka_8}}</h2>
  </form>
 </div>
</template>
<script>
export default { data: function () {
  return { angka_1: null, angka_2: null, angka_3: null, angka_4: null, angka_5: null, angka_6: null, angka_7: null, angka_8: null
  }
}
}
</script>
