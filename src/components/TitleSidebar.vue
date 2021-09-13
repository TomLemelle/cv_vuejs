<template>
  <section class="titleSidebar">
    <img :src="require(`@/assets/${img}`)"  :alt="{imgDesc}">
    <h3>{{quality}}</h3>
  </section>
  
</template>

<script>
export default {
    props: {
        img: String,
        imgDesc: String,
        quality: String,
    }
}
</script>

<style>
.titleSidebar {
    display: flex;
    align-items: center;
}

img {
    width: 40px;
}

h3 {
    font-weight: bold;
    font-size: 25px;
    color: #03bcff;
    margin-left: 10px;
}
</style>