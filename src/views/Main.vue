<template>
  <main class="main">
      <Baseline />
      <TitleMain title="Diplômes et Formations" />
      <Diploma />
      <div class="main-separator"></div>
      <TitleMain title="Compétences" />
      <Skills />
      <div class="main-separator"></div>
      <TitleMain title="Expériences professionnelles" />
      <Experiencies />
  </main>
</template>

<script>

import Baseline from "@/components/Baseline";
import TitleMain from "@/components/TitleMain";
import Diploma from "@/components/Diploma";
import Skills from "@/components/Skills";
import Experiencies from "@/components/Experiencies";

export default {
  components: {
    Baseline,
    TitleMain,
    Diploma,
    Skills,
    Experiencies,
  }
}
</script>

<style lang="scss">

.main {
    background-color: #ffffff;
    flex: 1;
    margin: 0 60px;

    .main-separator {
      background-color: #dddddd;
      height: 2px;
      width: 100%;
    }
}

</style>