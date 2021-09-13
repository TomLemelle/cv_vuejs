<template>
  <aside class="sidebar">
    <Picture />
    <SeparatorSidebar />
    <Qualities />
    <SeparatorSidebar />
    <Languages />
  </aside>
</template>

<script>
import Picture from "../components/Picture.vue"
import SeparatorSidebar from "../components/SeparatorSidebar.vue";
import Qualities from "../components/Qualities.vue";
import Languages from "../components/Languages.vue";

export default {
  components: {
      Picture,
      SeparatorSidebar,
      Qualities,
      Languages
  }

}
</script>

<style>

.sidebar {
    width: 374px;
    background: #f0f0f0;
    font-size: 0.65em;
}

</style>