<template>
  <main class="main">
      <Baseline />
      <TitleMain title="Diplômes et Formations" />
  </main>
</template>

<script>

import Baseline from "@/components/Baseline";
import TitleMain from "@/components/TitleMain";

export default {
  components: {
    Baseline,
    TitleMain,
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