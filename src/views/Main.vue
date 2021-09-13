<template>
  <main class="main">
      <Baseline />
      <TitleMain title="Diplômes et Formations" />
      <Diploma />
  </main>
</template>

<script>

import Baseline from "@/components/Baseline";
import TitleMain from "@/components/TitleMain";
import Diploma from "@/components/Diploma";

export default {
  components: {
    Baseline,
    TitleMain,
    Diploma,
  }
}
</script>

<style>

.main {
    background-color: #ffffff;
    flex: 1;
    margin: 0 60px;
}

</style>