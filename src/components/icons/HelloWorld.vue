<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      "Saya adalah seorang yang bersemangat dan berdedikasi dalam mencapai tujuan karier saya di
      bidang teknologi informasi. Dengan latar belakang pendidikan yang kuat dan pengalaman yang
      beragam, saya bertekad untuk terus mengembangkan diri dan memberikan kontribusi yang berarti
      dalam setiap proyek yang saya jalani. Saya percaya bahwa integritas, kerja keras, dan
      kreativitas saya akan menjadi nilai tambah bagi tim dan perusahaan di mana saya berkarier."
      <a href="https://vitejs.dev/" target="_blank" rel="noopener"></a>
      <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
