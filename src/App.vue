<script setup>

import Vheader from "@/components/Vheader.vue";
import Vfooter from "@/components/Vfooter.vue";
import Vpromo from "@/components/Vpromo.vue";
import Vprojects from "@/components/Vprojects.vue";
import Vtech from "@/components/Vtech.vue";
import Vfeedback from "@/components/Vfeedback.vue";
</script>

<template>
  <Vheader />
  <main>
    <vpromo />
    <vprojects />
    <vtech />
    <vfeedback />
  </main>
  <vfooter />
</template>

<style scoped>

</style>
